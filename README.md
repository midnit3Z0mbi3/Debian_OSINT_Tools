# Debian_OSINT_VM


## Description
OSINT virtual machine with 100+ OSINT tools, cheatsheets, bookmarks, and other resources to help you in your OSINT investigation. 

<div align="center">
 <br>
 <img src="debian-wallpaper1920x1080.jpg" alt="black and red debian os logo" width="65%" height="65%"> 
</div>
<br><br>

## Over 100+ OSINT Tools

Python(pipx):

ghunt,
socialscan,
holehe,
xeuledoc,
waybackpy,
changedetection.io,
archivebox,
internetarchive,
search-that-hash,
name-that-hash,
h8mail,
domain-stats,
gitem,
whisper-ctranslate2,
checkdmarc,
shodan,
netlas,
ignorant,
masto,
social-analyzer,
recoverpy,
postleaks,
postleaksNg

GitHub Repositories:


Elasticsearch-Crawler,
blackbird,
Carbon14,
maigret,
Cr3dOv3r,
BridgeKeeper,
Elevate,
pwnedOrNot,
phoneinfoga,
EXIF-scanner,
LittleBrother,
WhatsMyName-Python,
gron,
sherloq,
spiderfoot,
theHarvester,
Spiderpig,
WikiLeaker,
ID-entify,
ReverseIP,
UhOh365,
Anon-SMS,
Wordlister,
instashell,
EyeWitness,
Wordlister,
netlas-scripts,
Fresh-Resolvers,
lazyegg,
TrashSearch,
agg,
X-osint,
DumpsterDiver,
proxybroker2,
metagoofil,
recon-ng,
sherlock,
Sublist3r,
Photon,
FinalRecon,
gophish,
anonphisher,
yt-dlp


Apt Package Manager:

ruby-dev, nmap, wireshark, tcpdump, ufw, postgresql, php,
git, python3-venv, pipx, httrack, webhttrack, filezilla,
mycli, pidgin, audacity, gimp, inkscape, librecad, ffuf,
mediainfo-gui, libimage-exiftool-perl, mat2, tor, vlc, marble,
qgis, ffmpeg, idle, ripgrep, jq, crunch, ssh, cherrytree,
keepassxc, remmina, stegosuite, exifprobe, ruby-bundler, mpg123,
thunderbird, curl, sq, python3-lxml, libre-dev,
snapd, proxychains4, flowblade, asciinema,
autopsy, sqlitebrowser, neovim,
build-essential, libcurl4-openssl-dev, libxml2, libxml2-dev,
libxslt1-dev, libgmp-dev, zlib1g-dev, npm


Snap Packages:

seclists, dbeaver-ce, powershell, joplin-desktop, youtube-dl-pro, ngrok, localxpose, telegram-desktop

Go Packages:

waybackurls,
amass,
amass oam-tools,
gobuster,
gospider,
hakrawler,
httprobe,
gowitness,
katana,
gotop

## Resources

OSINT Bookmarks. JSON and HTML.

Custom Search Tools

Templates for OSINT Flowcharts and Documents

BigggChungus onion-links - 2024 Dark Web Links & .Onion Links

01Kevin01 OnionLinksV3 - 2024 Onion Links V3 (Forum&Chat&Markets)

fastfire deepdarkCTI - Collection of Cyber Threat Intelligence sources from the deep and dark web 

cipher387 osint_stuff_tool_collection - A collection of several hundred online tools for OSINT 

cipher387 Dorks-collections-list - List of Github repositories and articles with list of dorks for different search engines 

cipher387 WebCam-Google-Shodan-Dorks - Google & Shodan Dorks for WebCam

cipher387 cheatsheets - High quality and text versions of cheat sheets from Cyber Detective Twitter

swisskyrepo InternalAllTheThings - Active Directory and Internal Pentest Cheatsheets 

andrewjkerr security-cheatsheets - A collection of cheatsheets for various infosec tools and topics. 


## **Install:**

Install <a href="https://www.virtualbox.org/">VirtualBox</a> on host PC.

Create a new <a href="https://www.debian.org/download">Debian 12</a> Virtual Machine on VirtualBox.

Install Debian 12 on Virtual Machine.

Start Virtual Machine

```console

add sbin to $PATH

add $USER to "sudo" group

update and upgrade

install git
```

```console
git clone https://github.com/midnit3Z0mbi3/Debian_OSINT_VM.git

chmod +x *.sh

sudo bash debian_packages_osint.sh

bash debian_pipx_git_osint_tools.sh

sudo bash snoint.sh

```

**Change DNS:**

```console
sudo bash change_dns.sh

reboot

```

**How to install latest version of Go:**

Download the latest version of <a href="https://go.dev/dl/">Go</a>

Extract the archive file

```console

sudo tar -C /usr/local -xzf /home/$USER/Downloads/go{version of GO}linux-amd64.tar.gz

Make sure your PATH contains /usr/local/go/bin

echo $PATH | grep "/usr/local/go/bin"

nano .bashrc

export PATH="/usr/local/go/bin:$PATH"

```

**Install go packages:**

```console

bash go.sh

```
<br>

## **Downloads:**

<a href="https://github.com/jgraph/drawio-desktop/releases/tag/v23.0.2">Draw.io</a>, 
<a href="https://go.dev/dl/">Go</a>, <a href="https://www.maltego.com/downloads/">Maltego</a>, 
<a href="https://portswigger.net/burp/communitydownload">Burp Suite</a>, 
<a href="https://apt.metasploit.com/">Metasploit</a>, 
<a href="https://protonvpn.com/">Protonvpn</a>, 
<a href="https://www.torproject.org/download/">Tor Browser</a>, 
<a href="https://www.google.com/earth/about/versions/">Google Earth Pro</a>, 
<a href="https://support.google.com/chrome/a/answer/9025903?hl=en">Google Chrome</a>

<a href="https://rustup.rs/">Rustup</a> an installer for the systems programming language Rust


## **firefox extensions:**

firefox containers, ublock origin, downthemall, bulk media downloader, fireshot, nimbus, singleFile, exifviewer, user agent switcher, image search options, reveye reverse search,

search by image, ressurrect pages, web archives, copy selected links, onetab, stream detector, joplin webclipper, foxyproxy, adguard, javascript toggle on and off, ghunt companion, download all images, keepassxc

the firefox extension store, firefox ADD-Ons, has a lot of useful AI web extensions, and other extensions that can aid in your research. 

## **chrome web store extensions:**

InVID WeVerify, ublock origin, adguard, downthemall, fireshot, singleFile, onetab, reveye reverse search, web archives

the chrome web store has a lot of useful AI web extensions, and other extensions that can aid in your research.

## Custom Search Tools

extract custom_search_tools.tar.gz to your ~/Desktop directory

Press Ctrl+Shift+o and import osint_bookmarks.json or osint_bookmarks.html

Right-Click on "Custom Search Tools" Bookmark in the "Local Tools" folder, and select "edit bookmark"

edit the URL: section of the bookmark. Change "USER" to your actual username. 

example "file:///home/zombi3/Desktop/tools/index.html"

## OSINT Templates

extract OSINT_Templates_FlowchartsAndDocs.tar.gz to your ~/Templates directory

 
## **Anonymize virtual machines with <a href="https://www.whonix.org/wiki/Download">Whonix</a> for an extra layer of security:**

<div align="center">

  <img src="Anonymizing_virtual_machines_with_Whonix.png" width="80%" height="80%">
  
</div>
<br><br><br>

