# Speedtest dashboard widget for pfSense

## Install

To use this widget you will need to install the speedtest package

```
pkg update ; pkg install -y py37-speedtest-cli
```

Copy the widget file **speedtest.widget.php** to **/usr/local/www/widgets/widgets/** on your pfSense machine.

Install the widget on your dashboard.

More info:
- https://www.speedtest.net/apps/cli
- https://www.joe0.com/2019/11/12/measure-the-speed-of-your-pfsense-routers-wan-connection-by-executing-the-speedtest-net-from-a-pfsense-gui/
