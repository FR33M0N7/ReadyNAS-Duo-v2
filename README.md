# ReadyNAS-Duo-v2

Steps to make **NETGEAR RND2000v2 (ReadyNAS Duo v2)** https://www.netgear.com/support/product/rnd2000v2_readynas_duo_v2/
work on modern browsers (too old TLS issue):

1. Install Firefox (any new one is fine as well).
2. Go to "about:config".
3. Set "security.tls.version.min" to "1".
4. Log in to ReadyNAS admin by heading to https://NAS_IP/admin (if you don't have access to the router, the NAS IP can be checked in RAIDar).
6. Update ReadyNAS Apache to 2.2.34 to resolve TLS issues by installing <Apache2_2.2.34-arm-0.0.1.bin> through NAS Add-ons (direct link and thanks to: https://github.com/rdynsxtrs/r5bin/blob/master/apache2/README.md)
5. (Optional) Install <EnableRootSSH_1.0-arm.bin> to enable SSH (direct link: https://www.downloads.netgear.com/files/ReadyNAS/ADDON/4.2(X86)/EnableRootSSH_1.0-arm.bin).
6. DONE! NAS is accessible in all modern browsers (tested using Brave).

Steps to make the **RAIDar app** work on silicon Mac:

1. Install <RAIDar 6.5 for MacOS> (direct link: https://www.downloads.netgear.com/files/GDC/READYNAS-COMMON/RAIDar_6.5.0.dmg from https://kb.netgear.com/20684/ReadyNAS-Downloads)
2. Install <macOS x64 (10.7.3 and above)> (direct link: https://javadl.oracle.com/webapps/download/AutoDL?BundleId=251401_0d8f12bc927a4e2c9f8568ca567db4ee from https://www.java.com/en/download/manual.jsp)
3. DONE! 

List of add-ons for ReadyNAS duo v2: https://kb.netgear.com/24586/RAIDiator-5-3-Add-ons
