# GUI DNS changer for linux (version 2)
change dns of your system easily and quickly

tested on `ubuntu` and `mint`

### Screenshots
![main window](icon/Screenshot.png)
![fastest window](icon/Screenshot2.png)

### Installation
```
git clone https://github.com/mrmoein/GUI-DNS-changer-for-linux
cd GUI-DNS-changer-for-linux
sudo apt install python3-pip
python3 install.py
```

search for `DNS changer` app

# Todo
The program edits `/etc/resolv.conf` and at each boot (restart) this file is overwritten by the system and the software changes are removed (reset to default system dns). Find a global way (for all distributions like Ubuntu, Arch, etc.) to configure dns (set dns with terminal).
