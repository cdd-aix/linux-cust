Quirks:
* ~~net-tools~~
Desktop:
* ~~vlc~~
* ~~vdpauinfo~~
* ~~libvdpau-va-gl1~~
* ~~pavucontrol-qt~~
* ~~Disable screen rotation...~~
  * sudo systemctl stop iio-sensor-proxy-service
  * sudo systemctl disable iio-sensor-proxy.service
  * apt-get remove iio-sensor-proxy
* Fix resume from hibernate
* Fix xfce4-terminal-settings.desktop names.
VMWare:
* [ovftool](https://code.vmware.com/web/tool/4.3.0/ovf)
* [PowerCLI](https://www.altaro.com/vmware/install-powercli-ubuntu-linux-18-04-lts/)
  * Install Powershell Preview for Linux
  * In pwsh-preview (run as root) "Install-Module -Name VMware.PowerCLI"

Server:
* /etc/systemd/logind.conf HandleLidSwitch=ignore
