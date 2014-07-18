AP-Hotspot
==========

Automatically creates an infrastructure (Access Point mode) wireless hotspot in Ubuntu that should work with Android and Windows Phone devices

Usage
----
    ap-hotspot [argument]

        start          start wireless hotspot
        stop           stop wireless hotspot
        restart        restart wireless hotspot
        configure      configure hotspot
        debug          start with detailed messages



Install
-------
On Debian and Ubunutu run

    sudo apt-get update
    sudo apt-get install libnotify-bin iw dnsmasq
    sudo ./install.sh
    