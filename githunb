sudo apt update && sudo apt upgrade -y && sudo apt install xfce4 -y && wget https://dl.google.com/linux/direct/chrome-remote-desktop_current_amd64.deb -P /tmp && sudo apt install --assume-yes /tmp/chrome-remote-desktop_current_amd64.deb
  
(ENTER THIRD CODE FROM CHROME REMOTE DESKTOP WEBSITE)

 /opt/google/chrome-remote-desktop/chrome-remote-desktop --stop
    
sudo bash -c 'echo "exec /etc/X11/Xsession /usr/bin/xfce4-session" > /etc/chrome-remote-desktop-session'

echo "export CHROME_REMOTE_DESKTOP_DEFAULT_DESKTOP_SIZES=1920x1080,1080x720" \
    >> ~/.profile
    
echo "/opt/google/chrome-remote-desktop/chrome-remote-desktop --start" >> ~/.bashrc
