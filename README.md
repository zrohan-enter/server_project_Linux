\# 🐧 Linux Server Project



A repository for tracking configurations, scripts, and documentation for a Linux server project. This includes setting up and managing services like SSH, vsftpd (FTP), Apache/Nginx (Web), Samba, and media streaming.



Project for course `CSE 323`.

\* \*\*Team Member:\*\* \[Your Name]



---



\## Quick Links

\* \*\*Demo Plan:\*\* `docs/demo-plan.md`

\* \*\*Weekly Progress:\*\* `docs/progress/`

\* \*\*Network \& Credentials:\*\* `docs/network-credentials.md` (Use placeholders!)



\## Services

\* \*\*SSH:\*\* `configs/sshd\_config`

\* \*\*FTP (vsftpd):\*\* `configs/vsftpd.conf`

\* \*\*Web (Apache/Nginx):\*\* `web/`

\* \*\*Samba:\*\* `samba/smb.conf`

\* \*\*Media Server:\*\* `media/`



\## How to Reproduce

1\.  Install Ubuntu Server (or specified Linux distro) in a VM.

2\.  Run `scripts/setup.sh` to install all packages.

3\.  Apply the configurations from the `configs/` directory.

4\.  See `docs/demo-plan.md` for service checks.



\## ⚠️ Notes

\* \*\*No secrets:\*\* Real passwords, private keys, or secret API keys should \*\*never\*\* be committed here. Use placeholders like `<PASSWORD>` or `\[SECRET]` in config files.

\* \*\*Large files:\*\* VMs (.ova), ISOs, and large videos are kept out of this repo (see `.gitignore`). They will be shared via Google Drive or a USB drive.

