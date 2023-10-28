What to do if Internet Service Provider (ISP) is block access to certain websites
The steps you need to take to circumvent these blockings depend on how extensive the efforts from the censoring authorities are.

STEP 1
The most rudimentary way for your Internet Service Provider (ISP) to block access to certain websites, would be to not allow certain domains to be dissolved by their DNS servers. In that case all you need to do is to change the IP address of the DNS server in your computer’s network settings, to a DNS address that is not in control of your ISP, like 1.1.1.1 (Cloudflare) or 8.8.8.8 (Google). You can find a guide on how to make this changes here: https://developers.google.com/speed/public-dns/docs/using

STEP 2
However, if the efforts of the censoring authorities are more sophisticated here is what you can do:

Download the Tor Browser from https://www.torproject.org/download/. If access to the Tor website is already restricted in your country, you can send an email to gettor@torproject.org which only needs to contain which operating system you are using and your locale. So if you are for example using a Windows computer inside of Afghanistan you just email "windows af“ and Tor will respond with an email containing a link from which you can download the Tor browser. Once you have installed the Tor browser try to connect to the internet. If connected, you can visit https://check.torproject.org/ just to be sure that you are actually using the Tor network.

STEP 3
If the connection can not be established, it might be that access to the Tor network is being restricted in your country. In that case, go to the settings in your Tor Browser and select the tab Tor. You will find the option of using Tor bridges, which are hidden entry points to the network. You have 3 options on how to receive the address of a Tor bridge:

You can request the bridge address within the settings of the Tor browser. You will be asked to solve a CAPTCHA in order to request an address.
You can visit https://bridges.torproject.org/ and request a bridge address.
You can email bridges@torproject.org. Leave the subject field empty and write "get transport obfs4“ in the message. However, you can only request bridges from Gmail or Riseup email accounts. Once you have received a bridge address, enter it into your Tor Browser's settings and you should be able to connect to the Tor network.
STEP 4
If all fails, here are a few other tools that you can use to circumvent the censorship in your country: Psiphon (https://www.psiphon3.com/) Lantern (https://getlantern.org/) Freenet (https://freenetproject.org/) I2P (https://geti2p.net/)
