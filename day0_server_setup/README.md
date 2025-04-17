# 🧱 Day 0 – Linux VM Server Setup (Baseline Environment)

**Goal**: Set up a clean, secure, and functional Linux server environment in VMware for the upcoming Linux Admin Challenge and personal lab projects.

---

## ✅ OS & Environment

- **Distro**: Ubuntu Server 22.04 LTS
- **Virtualization**: VMware Workstation
- **VM Specs**:
  - 2 CPUs
  - 4 GB RAM
  - 50 GB Disk (dynamically allocated)
  - 20 GB Backup Disk
  - NAT networking

---

## 🔧 Post-Install Configuration

### System Update
```bash
sudo apt update && sudo apt upgrade -y



### Install Core Utilities
sudo apt install -y git vim curl wget tree net-tools htop mlocate
sudo updatedb


### Tailscale Setup for Secure Access
curl -fsSL https://tailscale.com/install.sh | sh
sudo tailscale up


### Github Configuration

#### Git Identity
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

#### Clone Challenge Repo
git clone git@github.com:yourusername/linux-admin-lab-challenge.git
cd linux-admin-lab-challenge



