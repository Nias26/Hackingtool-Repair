An attempt to repair ZN4nzu hackingtool reposity

The installation can't be done with the ZN4nzu installer. You have to do it manually.

!!WARNING It requires python3-pip to install the requirements!

Installation:
```
git clone https://github.com/Nias26/Hackingtool-Patch.git
chmod -R 755 hackingtool
cd hackingtool
sudo pip3 install -r requirement.txt
cd ..
python3 $INSTALL_DIR/hackingtool.py" '${1+"$@"}' > hackingtool
sudo chmod +x hackingtool
sudo cp hackingtool /usr/bin/
rm hackingtool
```
When you finish the installation, type sudo hackingtool to start the program. If it gives you error when you start it, you have to do `sudo python3 /usr/bin/hackingtool/hackingtool.py` to start the program.

If you have any other problems installing, report it on the issues tab. 
Thanks!
