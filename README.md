# UniFi_USG_Starlink

By now most Starlink users are aware of using the Static Rout setup when using your own router instead of the Starlink router. However for Ubiquti UniFi Security Gateway users also using a failover WAN the simple static route does not work for you.

In the Ubiquti community forums a user provided a solution using pseudo ethernet in the config.boot. See topic [Starlink, USG-Pro-4, Failover and Static Routes not being honored](https://community.ui.com/questions/Starlink-USG-Pro-4-Failover-and-Static-Routes-not-being-honored/29875219-0057-4eed-b85c-704d58cae9f2).

The file I've posted here is simply a rephrasing of that info for use in a config.gateway.json file on your controler. This should work for the 3 port and Pro Security Gateway devices. You will need to adjust the ports to match your Starlink port.