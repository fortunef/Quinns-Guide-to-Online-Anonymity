# Quinns-Guide-to-Online-Anonymity
## Recommended mobile operating systems
### Android based: 
-   [**GrapheneOS**](https://grapheneos.org/) Formerly known as CopperheadOS is a FLOSS privacy focused Operating System that has a replacement for all the nonfree services included in Google's, Google Pixel Devices (Micro G).
-   [**CalyxOS**](https://calyxos.org/) A open-sourced privacy focused Operating System with a UI similar to a Google Pixel comes with mostly free and open-sourced software pre-installed.
-   [**DivestOS**](https://divestos.org/) A free and open-sourced that's FOSS focused. Based off of [**LineageOS**](https://lineageos.org/).
-   [**LineageOS**](https://lineageos.org/) This is what I use. It doesn't come pre-installed with any nonfree services but it does come pre-installed with Google Chrome which is nonfree but you can remove it using App Manager from FDroid
### Linux Based:
-   [**PureOS**](https://www.pureos.net/) A free and open-sourced Operating System. It's FSF approved and it utilises the GNU's Linux-Libre kernel. It's Debian based. It comes with GNU CoreUtils
-   [**postmarketOS**](https://postmarketos.org/) A unique free Operating System. Based off of [**Alphine Linux**](https://www.alpinelinux.org/) so I'm not quite sure if it has GNU CoreUtils
## Recommended Desktop/Laptop operating systems
### (GNU+)Linux(-Libre)-based distros:
-   [**NixOS Unstable (24.05)**](https://nixos.org/) This is the operating system that I personally utilise as my daily driver and i'm using it right now to type this out. NixOS is an easily reproducable, independent, immutable, general purpose, and fast operating system. It has the most packages in a Linux distro/Package Manager/MacOS Package Manager infront of the AUR. By default, it doesn't come with any nonfree software or any bloat either. This distrobution of the GNU/Linux operating system is based around the Nix package manager aka. the best package manager in the world. Theres 2 stable updates per year. The way you configure your whole system is within one file (/etc/nixos/configuration.nix) you can start & install services, packages, from that one file. It's sorta easy to learn atleast for me because I'm autistic but I digress.
  
-   [**Arch Linux**](https://archlinux.org/) A hard to install, easy to use, lightweight GNU/Linux operating system. It comes with a traditional package manager (pacman) to install software from the official repos. This distro is very hard to install because you have to install it using a CLI so you'll probably need a pair of programmming socks for this but once you've installed it, it's pretty simple. The main feature of this distro is the AUR (Arch User Repository) which is where anyone can upload anything to there. This brings alot of freedom but security issues aswell but in my time using Arch Linux, I've never gotten malware from there.
 
-   [**Fedora Silverblue**](https://fedoraproject.org/silverblue/) A ton of people call this distro the best immutable distrobution ever. I've never tried it but it looks like it's very secure and stable. I don't really like Fedora because it's funded by RedHat and is Red Hat Linux-based. It also possibly calls the phone to Red Hat like Ubuntu does with Canonical. Wouldn't recommend for Privacy.

-   [**Parabola GNU/Linux-libre**](https://www.parabola.nu/) FSF Approved version Arch Linux which removes all the nonfree packages such as the NVIDIA GPU Drivers (nvidia) and the AMD GPU Pro Drivers (amdgpupro) and introduces the GNU's Linux-Libre Kernel which is just the Linux Kernel but without the obfuscated code and binary blobs. It comes with a graphical installation with LXDE (Light-weight X Desktop Environment) along with a CLI one.

-   [**QubesOS**](https://www.qubes-os.org/) The famous operating system used by the NSA Whistleblower, Edward Snowden. Everything on this system is virtualised using a Zen, a Type 1 Hypervisor. If you want to run, for example, Firefox, It launches a virtual machine just for launching a window using Firefox on it. Also, It uses systemd and the non-libre Linux kernel which might be a concern for many.
   
-   [**TailsOS GNU/Linux**](https://tails.net/) The Amnesic Incognito Live System. Another Linux distro used by the NSA Whistleblower Edward Snowden. It's designed to be run on a flash drive and not a hard-drive nor Virtual Machine. It's the Linux distro that the Tor Project recommends for browsing Tor on. It uses systemd and the non-libre Linux Kernel which may be a security concern for many.
  
-   [**HeadsOS GNU/Linux-Libre**](https://heads.dyne.org/) HeadsOS is bascially just hardened TailsOS. It uses OpenRC as it's init system unlike systemd which is used in many distros and will probably be exploited one day or another, and it also uses the fully free, FSF Approved, Linux-Libre Kernel which rids of all the binary blobs and obfuscated code in the Linux kernel therefore making it more free and secure than TailsOS. It also has all the features that TailsOS has of course.

## Recommended browsers
### Chromium Based:
-   [**Brave**](https://brave.com/) I wouldn't recommend this because of how bloated it is. It has weird cryptocurrency shinnanagins. But it's open-source and you can ignore all that.
  
-   [**Bromite**](https://www.bromite.org/) Android only. Free and open-sourced with a UI almost exactly like Chromium and comes with an ad-blocker.
  
-   [**ungoogled-chromium**](https://github.com/ungoogled-software/ungoogled-chromium) Completely blocks anything related to Google. Unlike Chromium, ungoogled-chromium doesnt call home to Google. Fully free.
### Firefox Based:
-   [**Firefox (w/user.js)**](https://www.mozilla.org/en-US/firefox/new/) Link goes to Firefox. Link to a user.js (arkenfox) [**here**](https://github.com/arkenfox/user.js/). Both free and open-sourced and the user.js you can modify to the amount of privacy and anonymity you yearn for. Can't be done on IOS and Android.
  
-   [**GNUzilla and IceCat**](https://www.gnu.org/software/gnuzilla/) FSF Approved Browser. Blocks all nonfree and nontrivial Javascript which causes some sites to not work like Youtube but you can use privacy-focused front-ends for them like [**Invidious**](https://invidious.io/) (Youtube).
  
-   [**LibreWolf**](https://librewolf.net/) uBlock Origin pre-installed. Independent Fork of Firefox
  
-   [**Mull**](https://f-droid.org/packages/us.spotco.fennec_dos/) Android only. It is Firefox w/arkenfox-user.js but for Android.
  
-   [**Tor**](https://www.torproject.org/download/) Most secure out of all of these but with the sacrifice of convience. Volunteer ran. Runs your network traffic through 3 nodes from volunteers around the world. **❗❗DO NOT USE TOR WITH A VPN❗❗**
  
-   [**Mullvad Browser**](https://mullvad.net/en/download/browser/) Not to be confused with Mull, Mullvad Browser is a browser made as a collaboration with Mullvad and the Tor Project. It's the second most private browser out of there and it's designed to be used with a VPN (specifically Mullvad VPN). Unlike Tor, most sites don't block Mullvad Browser so I personally use it.
  
## Browser tests
**❗❗MAKE SURE YOUR BROWSER YOUR USER AGENT WHATEVER ISNT TOO UNIQUE BECAUSE IF IT IS THEN ITLL BE EASIER TO TRACE YOUR ACTIVITY. BLEND IN, NOT STAND OUT THATS THE REASON WHY TOR AND MULLVAD BROWSER EXISTS❗❗**
-   https://www.deviceinfo.me I recommend this one
-   https://dnsleaktest.com
-   https://librespeed.org
-   https://privacytests.org
-   https://time.gov
-   https://mullvad.net/en/check and this one too
## Privacy friendly front-ends
-   https://wiki.installgentoo.com/wiki/Privacy_friendly_frontends # Haha funny 4chan.org/g/ board website
## Recommended search engines
-   [**Brave Search**](https://search.brave.com/) Can be used without the Brave browser. Completely uncensored. Completely independent.
  
-   [**Duckduckgo**](https://duckduckgo.com) Basically a privacy front-end for Bing since it gets its results from Bing.
    
-   [**SearX/SearXNG**](https://searx.space/) You can self-host this if you're ultra paranoid. You can index results from multiple search engines and websites like Google, Bing, Yandex, Github, Wikidata etc.
    
-   [**Startpage**](https://www.startpage.com/) Gets its results from Google. Ran by an advertising company if that's a concern.
   
## Privacy oriented DNS
~~-   [**AdGuard**](https://adguard-dns.io/en/welcome.html)~~
~~[**NextDNS**](https://nextdns.io)~~
~~[**Quad9**](https://www.quad9.net/)~~

**❗❗DO NOT USE FOR THEY ARE FREE AND IN CAPITALISM, IF SOMETHING IS FREE YOU ARE 9 OUT of 10 TIMES THE PRODUCT AND THE ADVERTSERS THE CUSTOMERS INSTEAD JUST PAY FOR A VPN LIKE MULLVAD OR PROTON VPN WHICH HAS THERE OWN DNS AND THEIR CLIENTS ARE BOTH OPEN SOURCE❗❗**
## Privacy oriented email
-   [**ProtonMail**](https://proton.me/mail) Emails automatically PGP encrypted when communicating with other Proton Mail users for convience. I'd recommend paying for this one instead of the free tier because you get a VPN, (I'd recommend Mullvad VPN because it's pay as you go [I havent paid for Mullvad VPN for like half of the year]) Cloud storage (The cloud is just someone elses computer remember that), Email Aliases, and some other stuff.Community
   
-   [**Tutanota**](https://tutanota.com/) Emails automatically PGP encrypted when communicating with other Tutanota users for convience.
   
## Recommended Instant Messenger
-   [**Signal**](https://www.signal.org/) P2P Encrypted and fully fre
## BIOS/UEFI replacement (For the serverly paranoid power users)
-   [**coreboot**](https://coreboot.org)
    
-   [**Libreboot**](https://libreboot.org)

    **❗❗WARNING THIS MAY BRICK YOUR COMPUTER IF POSSIBLE BUY A LAPTOP OR A MOTHERBOARD WITH COREBOOT/LIBREBOOT PREINSTALLED FOR EXAMPLE, SYSTEM76 LAPTOPS OR A FRAMEWORK LAPTOP WITH COMES WITH ITS OWN OPEN SOURCE FIRMWARE❗❗**

# License
This text is licensed in the Unlicense License which is a Public Domain License. You are free to do whatever you want with it such as; rebrand it as your own and commercialise it, sell verbatim copies, modify it, say you made this and tell people how bad of a writer you are, etc but with with **ZERO** warranty at **ALL**. For more information, read [this](https://github.com/fortunef/Quinns-Guide-to-Online-Anonymity/blob/main/LICENSE)
