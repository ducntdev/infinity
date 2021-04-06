Ref: https://wiki.archlinux.org/index.php/Advanced_Linux_Sound_Architecture

# Change default driver
sudo nano /usr/share/alsa/alsa.conf  
  defaults.ctl.card 1;
  defaults.pcm.card 1;

# Unmute or increase/decrease volume
alsamixer
