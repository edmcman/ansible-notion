# Intro

This is an Ansible role to install and configure Notion on Linux.  It installs sessions for running Notion in several modes
- Standalone
- With GNOME 3
- With Unity
- With GNOME Flashback (recommended).

I recommend Notion with GNOME Flashback.

Only tested on Ubuntu 22.04.3 LTS.

# Installation

Run: `ansible-playbook --connection=local -i localhost, local.yml --tags all,initial -K`
