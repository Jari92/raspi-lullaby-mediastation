# raspi-lullaby-mediastation
This code uses a bash script to start media files with a half random shutdown sleeptimer (e.g. for bedtime story, lullaby) with auto save. The last played song will be the starting point at the next boot. I wrote this script to have a simple headless media player that does not need any wireless connections.

Hardware:
  * Raspberry Pi 3 B+
  * Speakers connected via  3.5mm Jack

Software:
  * mplayer

How to use:
  * Setup your crontab to start the script after a short waiting period
    
    <code>@reboot sleep 40 && /home/pi/Desktop/autostart_lullaby.sh</code>
