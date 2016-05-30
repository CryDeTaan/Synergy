# Synergy

I use Synergy for sharing my mouse and keyboard between multiple computers.
It works on Windows, Mac OS X and Linux.

Download Synergy from:
https://symless.com/account/

 1. Windows Install

 2. Linux Install

  1. Synergy depends on libavahi-compat-libdnssd1
  `apt-get install libavahi-compat-libdnssd1`
  2. Install Synergy
        `dpkg -i synergy.dep`
  3. Configure/run Synergy
    1. Run wizard by opening synergy from the application menu, or
    2. From terminal run `synergyc <SERVER HOSTNAME/IP>`
  4. Auto start
   need to find good way to do this, at the moment added allias to zshrc

 3. Mac Install
