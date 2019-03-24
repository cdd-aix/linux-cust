# Linux Customization Scripts

Collection of scripts to customize a Linux host for specific purposes

## DevDesktop

My preferred environment for a development desktop
* Desktop
* VMWareTools
* emacs25
* git
* groovy for Jenkinsfile checking
* jsonlint
* python-flake8
* python3-flake8
* rubocop ruby linting
* shellcheck
* tidy for html linting

Todo
* quicktile and the required wnck library
* my emacs config
* mypy

## Desktop

Common desktop requirements
* Quirks
* fonts-noto so obscure unicode can resolve
* libvdpau-va-gl1 for accelerated video playback
* lxqt
* openbox-lxde-session
* pavucontrol-qt so mixer from volume in panel works
* vdpauinfo to check video acceleration
* vlc for video playback
* xfce4-terminal
* xfwm4
* xfwm4-theme-breeze
* xserver-xorg-input-synaptics-hwe-18.04

Disable the accelerometer based display tilt

TODO:
* Fix hibernate resume configuration
* Fix xfce4-terminal-settings.desktop name

## Quirks

Used by all environments
* curl because it's cleaner in pipelines
* net-tools because 'netstat -rn' is hardcoded into my hands
* ntpdate
* openssh-server
* uptimed
* vim

Remove
* gnome-software-plugin-snap
* snapd because the docker snap did not behave as expected

## VMWareTools

Provide tools to manage vmware from Linux CLI
* [ovftool](https://code.vmware.com/web/tool/4.3.0/ovf)
* [PowerCLI](https://www.altaro.com/vmware/install-powercli-ubuntu-linux-18-04-lts/)
  * Install Powershell Preview for Linux
  * In pwsh-preview (run as root) "Install-Module -Name VMware.PowerCLI"

## FamilyDesktop

Desktop for extended family members
* google-chrome because it has less lag showing church live streaming
* libreoffice

## 
