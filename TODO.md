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

Server:
* /etc/systemd/logind.conf HandleLidSwitch=ignore
