# WSL Installation

A quick reference guide for installing and configuring WSL (Windows Subsystem for Linux) on Windows, including checking for an existing setup, upgrading to WSL 2, and installing a Linux distro — with Frappe's Ubuntu requirement in mind.

Setting up WSL involves a few key checks and steps:

- **Pre-check** — verifying whether WSL is already installed (`wsl --status`) and whether a required distro already exists (`wsl -l -v`), to avoid unnecessary reinstalls
- **Installation & Versioning** — installing WSL if missing, confirming the installed version, and upgrading to WSL 2 if it's still on version 1
- **Distro Setup** — listing available Linux distros and installing the one needed (Ubuntu, for Frappe compatibility)

This repo walks through the full setup: checking for an existing WSL installation, installing/upgrading WSL, listing available distros, and installing Ubuntu for local Frappe development.

📖 **Full notes, sample outputs, and step-by-step commands:** [WSL Installation — Notion Notes](https://app.notion.com/p/WSL-Installation-3b609049c3a78098ace5cd9231641f9b?source=copy_link)
