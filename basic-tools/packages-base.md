# Base Packages

Essential packages to get started with a Debian server:

- **vim** – text editor  
  apt install vim

- **nano** – simple text editor  
  apt install nano

- **less** – view files  
  apt install less

- **curl** – fetch URLs  
  apt install curl

- **wget** – download files  
  apt install wget

- **gnupg / gpg** – GPG key management  
  apt install gnupg gpg

- **ca-certificates** – SSL certificates  
  apt install ca-certificates

- **lsb-release** – detect distro version  
  apt install lsb-release

- **apt-transport-https** – enable HTTPS in apt  
  apt install apt-transport-https

- **git** – version control  
  apt install git

- **zip / unzip** – archive management  
  apt install zip unzip

---

## Install All Base Packages

Finally we have:  
apt -y install vim nano less curl wget gnupg gpg ca-certificates lsb-release apt-transport-https git zip unzip
