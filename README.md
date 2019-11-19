# limitedinternet


limited internet on :    access to specific websites  
limited internet off:    access to all websites

Works with
  * Systemd

It works by changing the
    **/etc/nsswitch.conf** and
    **/etc/hosts**
files.

The following files must be defined
   * /etc/.hosts.limited.internet.on
   * /etc/.hosts.limited.internet.off
   * /etc/.nsswitch.conf.limited.internet.on
   * /etc/.nsswitch.conf.limited.internet.off
