# Instashell v1.5.4
## Author: github.com/Gokuljokul

### Don't copy this code without give me the credits, 
Instashell is an Shell Script to perform multi-threaded brute force attack against Instagram, this script can bypass login limiting and it can test infinite number of passwords with a rate of +400 passwords/min using 20 threads.

## Legal disclaimer:
Usage of InstaShell for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

![insta]### Features
- Multi-thread (400 pass/min, 20 threads)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Usage:
```
git clone https://github.com/Gokuljokul/instashell
cd instashell
chmod +x instashell.sh
service tor start
sudo ./instashell.sh
```

### Install requirements (Curl, Tor, Openssl):

```
chmod +x install.sh
sudo ./install.sh
```
### Install Tor:

Download the tor browser file and launcher file,

```
cd Downloads/
ls
tar -xvf tor-browser-linux64-8.5.4_en-us.tar.xz
clear
ls
cd /root
cd downloads/
ls
cd tor-browser_en-US/
ls
cd browser/
ls
./start-tor-browser
git clone http://github.com/Gokuljokul/Instashell.git
service tor start
cd instashell
chmod 775 instashell.sh
chmod 775 instashell.sh
./instashell.sh
```
Give the Instagram Account ID

```
passwords.lst
```
limit (like <20 to 50000)

### Usage:
```
git clone https://github.com/Gokuljokul/instashell
cd instashell
chmod +x instashell.sh
service tor start
sudo ./instashell.sh
```


### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR and rotating the ip address to avoid blocking. 
The script uses Instagram-py algorithm.
