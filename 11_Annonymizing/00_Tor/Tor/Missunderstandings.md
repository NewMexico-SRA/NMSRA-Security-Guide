#Missunderstandings
Online there are a lot of missunderstandings and missrepresentations of Tor. Some acredit unrealistic levels of security soley to Tor, while most tarnish the Tor reputation. There are alterior motives to both forms of missrepresentaion, or possibly missunderstandings. Unsafe use of Tor is clearly insecure and Tor must be properly utilized for its benefits, however Tor is a trustworthy tool that does as the Tor Project accuratly reports: provide annonominity with proper users.
##### Motives
Over praising Tor as impregnable is either caused by limited technical understanding or malicious intent. If not out of ingorance, someone advising unwarrented trust in Tor likely wishes to trick gulible novices into malware downloads, legal troubles, or one of the many scams on the 'Dark web'.  
Most of the articles on Tor and its supposed vulnerabilities are hosted on VPN sites, or sites which link to VPNs or reviews-- which could only be presumed to be affiliat links. If a site has a monetary insentive to encourage readers to purchase VPNs, it would have an insentive to undersell or missrepressent Tor's capacitites. It is unfortunate that these sites are untruthful, when they could instead highlight the different usecases for Tor and VPNs (see: VPNorTOR.md).
## Against Tor 
Restore Privacy has an extensive (article)[https://restoreprivacy.com/tor/] on Tor's security and trustworthyness.  
Many of the claims are rebuked bellow. An archived HTML file for the article can be found in the file: 'Articles'.
### Tor is compromised  
> [G]overnments can de-anonymize Tor users is another well-known point that's been acknowledged for years.  
> In 2013 the Washington Post broke an article citing reports that US government agencies had figured out how to de-anonymize Tor users on a 'wide scale'.  
According to Restore Privacy, Tor has been compromised since *2013* citing a Washington Post article. It should be noted this method is intrinsic to all forms of communication. The attack: observing the timings of packet transfers to deduct which entry and exit node is being used by a user, then being inbetween the user and entry node (or being the entry node itself) to extract the user's IP address. The probability of which is insubstancial and statistically insignificant, given the diversity of jurisdictions with tor nodes of all kinds. It is exhaustive and improbable; this attack certainly exists, but is only cause for concern at much greater threat models, which have their own methods, however much more challenging.  
The linked article about the 2015 Black Hat convention being pulled featured a quote by alleged researchers:  
> "There is nothing that prevents you from using your resources to de-anonymise the network's users by exploiting fundamental flaws in Tor design and implementation"  
however this attack was not demonstrated, nor are the attacks details clear. The Tor Project suspects it to have been a 'relay attack' which would mark the traffic to be identified at the other end of the onion routing. After its discovery the open source community and the Tor Project worked dilligently to remove the bug. It was quickly removed, making the attack impossible.     
> "There are also researchers who devised attacks allowing them to de-anonymize 81% of Tor users in the wild."  
An astonding rate of deannonymizing, however it has a six percent false positive rate. Additionally it depends on a honeypot scheme and a mallicious download. With Tor set to 'strictest' scripts are blocked, making automatic and hidden downloads practically impossible. Again, this depends on going to a hostile website hosted by an entitie that controls a substantial number of tor nodes, which are incredebly diverse and can be hosted by any person or entity with computing power. Additionally, this is another mutation of the improbable traffic correlation attack.  
To conclude this section the article referrences an unfalsafiable claim that the FBI has an undisclosed attack. The proprietary "classified information" is unstable at best, especially considering the case probably involved downloads and financial transactions which would sooner be traced. Also, the state can't have it's cake and eat it too, in public court the state would have to burn the ace up its sleave. Unless one faces the prospect of a grand jury, this is a bluff worth calling.  
### Government Involvment
The US Navy developed and the government funds the Tor Project. It is a fact that one of the most capable entities in the world with the most to hide developed such a privacy tool. It isn't a conspiracy either, as it depends on wide spread public use to function. If it is such a concern the source can be inspected and individually compiled. The cryptography could be reverse engineered to certify its integrity.  
### Glowsticks
Indeed, Tor users can be identified. Users are glowsticks, yet they are among other glowsticks-- many of which don't have criminal intent. The case sited is of a college student making a bomb threat at his university's library using identifiable credentials. Hopefully it is clear that Tor is not at fault for the outcome of this situation, in fact Tails and Whonix are Tor adjacent tools that would have digitally obfuscated the student's identity. A bridge or VPN would not have acomplished this like the article claims.
### Nodes
Any individual or entity can set up tor nodes. This is the reason behind the diversity and decentralization of the tor network. Indeed mallicious actors can snoop traffic if they opperate exit nodes, however it is all annonymized. More concerning is the potential for those nodes to inject harmful content and send it back with the legitimate date. This risk is real, however due to Tor script blocking and safe Tor use it is entierly avoidable. It is well known by the Tor developers that accessing PDF files while using Tor or running non-Tor internet requests is opening oneself up to avoidable attacks.
> "Over the last few days, we received and read reports saying that several Tor relays were seized by government officials. We do not know why the systems were seized, nor do we know anything about the methods of investigation which were used."
Is a quote from the Tor Project used to galvanize readers to purchase VPNs, due to the intensity of this quote it is easy to forego critical though. If it were possible for a single government or conglomerate to sieze a substanstial vast majority of tor serves and effectively analyze the immense amount of data, there would be many more pressing concerns. Fortunately that is not possible at this time, nor is it probable.  
> "Assuming that some Tor nodes are data collection tools, it would also be safe to assume that many different governments are involved in data collection, such as the Chinese, Russian, and US governments."  
Absolutely. As mentioned above, however, such data is annonymized. It would only prove useful with a vast majority ownership of tor nodes, as well as an extensive investment that is even unlikely for top government entities. This is in contrast to non-onion routed internet traffic which is collected *en mass* and stored by the NSA with far weaker encryption and non-existent annonyminity.  
> "Just a few months after the HSDir issue broke, a different researcher identified a malicious Tor node injecting malware into file downloads."
As mentioned above, malware can be injected into a download. This is the case regardless of Tor use, although Tor users may be suseptable to directed attacks. With proper use this risk is entierly avoidable, such as only using verified downloads or sandboxing, a technique involving suprisingly little sand. **Note:** GNU/Linux is resilient against malware.  
> "Senior U.S. District Court Judge Henry Coke Morgan, Jr. has ruled that the FBI does not need a warrant to hack into a U.S. citizen’s computer system."  
All the more reason to use Tor. This ruling effects Tor and non-Tor users alike.  
> "The judge in this case officially ruled that Tor users lack 'a reasonable expectation of privacy' in hiding their IP address and identity."  
Observe the ruling, the justfication is against Tor users, however doesn't specify which U.S. citizen's can be hacked by the FBI without a warrant.  
### IP Leaks
Tor is not intended to download torrents, as torrents implicitely connect to users IP address. There used to be, although entierly unavoidable bugs that would leak IP by accessing file:// rather than https://, however that has been patch out. Window's users are vulnerable to malware, however that has always been the case, is not exclusive to Tor and is, again, entierly avoidable.
- Tor offers no protection when torrenting and will leak the user’s IP address with torrent clients.  
- Tor may leak IP addresses when accessing files, such as PDFs or other documents, which will likely bypass proxy settings.  
- Windows users are also vulnerable to different types of leaks that will expose the user’s real IP address.
After these claims the article recognizes: "oftentimes de-anonymization is due to user error or misconfiguration. Therefore blame does not lie with Tor itself, but rather with people not using Tor correctly."  
### Target  
It is true that tor nodes are public information, as such some authoritarian governments have prohibited or criminalized the use of Tor. There is a work around, however, which is to connect first to a bridge (or VPN-- if those are not also targeted). The Tor Browser makes connecting to a bridge extreamly simple and reliable.  
### Conclusion  
Use Tor properly, avoiding unknown sites, using 'strictest' setting except in sessions exclusive for trusted sites, such as media sites, and not signing into identifiable accounts-- including frequently used accounts with psydonyms. With proper measures Tor is trustworthy. Tor use comes with responsibilities, however grants many liberties.