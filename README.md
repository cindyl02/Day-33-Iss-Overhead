## ISS Overhead Email Notification Project (Day 33)
### About
This project uses SMTPLib to send an email when ISS is close to your current position and it is at night.

### How to run
1. Edit configurations and add Gmail account and Gmail App Password to main.py
2. Edit MY_LAT and MY_LONG with your current location using https://www.latlong.net/.
3. Run main.py overnight. The program will check every 60 seconds if ISS is close to your current location and will send you an email notification if it is. 
