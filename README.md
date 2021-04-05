# windows10.dns.list
This is an exhaustive list of all Windows 10 DNS names that call back to Microsoft. There are over 1000 domains. This will block everything Microsoft has listed in their privacy documentation. Blocking includes Facebook, Bing, Outlook, Office, Edge, Skype, Xbox, Microsoft.com, Windows Update, Defender Update, Azure, and anything else that phones home to Microsoft.

The network icon will show that you have no internet connectivity, this is because of msftconnecttest.com. Occasionally your browser will pop open and go to this domain to force a connection home. It won't work and the page will be blank. To fix this go to networkproguide.com link below to modify your registry settings.

It was created for the people who need to use Windows 10 but do not want any data leaving their computer.
It can be used in the Windows 10 Host file, Pihole, PFsense PFblockerNG, or Firewall.
The sources were gathered from Microsoft privacy site, Microsoft WSUS servers, Reddit, and StackExchange. 

Registry Fix:

https://networkproguide.com/fix-connect-attempts-to-www-msftconnecttest-com-windows-server-2016/

Sources:

https://answers.microsoft.com/en-us/windows/forum/windows_other-networking/need-windows-update-servers-ip-address-range-to/0b0d3618-f74c-411d-bb46-58bd605f7abe

https://docs.microsoft.com/de-de/security-updates/windowsupdateservices/18127640

https://docs.microsoft.com/en-us/answers/questions/121284/wsus-update-url.html

https://docs.microsoft.com/en-us/windows/deployment/update/windows-update-troubleshooting#why-am-i-offered-an-older-updateupgrade

https://docs.microsoft.com/en-us/windows/privacy/

https://superuser.com/questions/363120/block-access-to-windows-update

https://www.microsoft.com/en-us/download/confirmation.aspx?id=53602

https://www.reddit.com/r/MoneroMining/comments/8l5wpt/block_windows_update_with_firewall/

https://www.reddit.com/r/sysadmin/comments/g345cj/windows_update_official_list_of_ips_or_domains/

https://www.reddit.com/r/Windows10/comments/3j8909/does_anyone_have_an_exhaustive_list_of_ip_ranges/