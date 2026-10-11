# 🛡️ Security Onion Installation Guide

Security Onion is an open-source platform designed for threat hunting, enterprise security monitoring, and log management. This guide outlines the requirements and sequential steps needed to deploy it using an ISO image.

## 📋 Requirements

Before beginning the installation, ensure your target machine meets the official minimum hardware requirements for a basic IMPORT deployment:
* **Processor:** x86-64 compatible 
* **CPU:** 2 cores
* **Memory:** 4 GB RAM
* **Storage:** 100 GB space

## 📥 Download

You can obtain the latest image directly from the official repository:
* [Download Security Onion ISO](https://securityonion.net)

## 🖥️ Installation Steps

1. **Download** the official Security Onion ISO image.
2. **Verify** the ISO checksum to ensure file integrity and safety.
3. **Create** a bootable USB drive or attach the ISO file to your virtual machine (VM).
4. **Boot** your target hardware or VM using the attached ISO.
5. **Follow** the on-screen installation prompts.
6. **Configure** your administrative username and secure password.
7. **Reboot** the system once the initial installation phase finishes.
8. **Log in** using the credentials you created in step 6.
9. **Wait** for the Security Onion Setup script to launch automatically.
10. **Complete** the setup wizard to finish configuring the system.

## ⚙️ Initial Configuration

During the automated setup phase, you will configure the following platform parameters:
* Hostname
* Management network interface
* IP addressing schemas
* Default gateway and DNS servers
* Security Onion Console (SOC) access
* Local firewall access control lists

## ✅ Verification

Once the configuration wizard completes, log into the web-based Security Onion Console. Check the built-in grid status tools to verify that all necessary monitoring services are up and running properly.

## 📚 Official Documentation

For advanced deployments, architecture guidelines, or troubleshooting, refer directly to the upstream documentation:
* [Security Onion Installation Guide](https://securityonion.net)
* [Security Onion Getting Started Guide](https://securityonion.net)
