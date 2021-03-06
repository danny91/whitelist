### Commonly whitelisted domains for Pi-Hole.

These domains are borrowed from various sources including reddit, GitHub and other sources.
You can request additional domains via <a href="https://github.com/anudeepND/whitelist/issues">Issues</a> tab.

#### whitelist.txt
[Pi-hole](https://pi-hole.net) users can quickly add these sites to your whitelist.txt by:

• `git clone https://github.com/anudeepND/whitelist.git`   
• `cd whitelist/scripts`   
• `sudo chmod +x whitelist.sh`    
• `sudo ./whitelist.sh`     

#### referral-sites.txt
Some deals sites like Slickdeals and Fatwallet needs a few sites (most of  them are ads) to be whitelisted to work properly, you can use `referral-sites.txt`file for this.    
(`whitelist.txt` is recommended for every user as it doesn't contain any bad domains, if you use specific services like Fatwallet or Slickdeals etc. you should use `referral-sites.txt`)
 
To add them quickly to whitelist: 

• `git clone https://github.com/anudeepND/whitelist.git`   
• `cd whitelist/scripts`   
• `sudo chmod +x referral.sh`    
• `sudo ./referral.sh`   
  
####   optional-list.txt
This file contain domains that are needed to be whitelisted depending on the service you use. (It may include analytics sites!)


##### How do I determine an ad domain?

##### a). DNSthingy Assistant

<a href="https://chrome.google.com/webstore/detail/dnsthingy-assistant/fdmpekabnlekabjlimjkfmdjajnddgpc">This browser extension</a> will list all of the domains that are queried when a web page is loaded. You can often look at the list of domains and cherry pick the ones that appear to be ad-serving domains.


![Alt text](https://discourse.pi-hole.net/uploads/default/optimized/1X/6ce0e13813df930288677c87bf0fd5861c150898_1_690x320.png)
 
 
 
##### b). Using inbuilt Developer tool
For Chrome ctrl+shift+I will land you in Developer tools menu.
![Alt text](http://i.imgur.com/44CHRLV.png)


