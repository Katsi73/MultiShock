# Important
This should work on Python version 3.11.4, if the program is struggling to run make sure you update here https://www.python.org/downloads/release/python-3114/
All testing is done on a 1920x1080 screen, effects on different ratios are unknown

## Setup:
Open the "config.json" file in notepad and change the names in parenthesis to match your PiShock login details, for example

{

  "api_username": "BillJones1",
  
  "api_apikey": "ffAjXWu7-3985-0563-F8hP-T2Nz6BUUJagY",
  
  "api_code": "GpE1dNBwH8U",
  
  "api_throttle_limit": 10,
  
  "api_name": "MultiShock"
  
}

Your API key can be found by logging into the PiShock website, going to Menu > Account > Generate API Key

Your API code can be generated in your PiShock controls, copy and paste this into the quotation marks

Simply trigger an event in a game, such as taking damage.
Find the most obvious visual indicator for that event, such as missing hearts or a certain number.
Screenshot it, and save it as a png, jpg, or jpeg.
Place the image the program will be looking for in the Images folder, do not rename or move this folder or the program may break.
Images within this folder can be named whatever as long as they are in jpeg, jpg, or png format.

### All set!
Run the .exe, and enjoy your game!

## Customisation:

The "api_throttle_limit" in the config can be changed to increase the number of requests sent at a time. Lowering this number will allow more requests to be sent, e.g. "api_throttle_limit" : 2, will allow the program to send one request every 2 seconds. This may impact CPU usage.

"detection_threshold" can be changed to increase or decrease how strict the image detection is from 0.1 - 1. 1 being exactly the same image and 0.1 being very generous in detection. Use this if you are having trouble detecting an image. Default is 0.5.

"capture_delay" can be changed to increase or decrease the delay between scans of your screen in ms. Default is once every 500ms. Lowering this number will impact CPU.

## Known Issues, report any issues to 'neazho1' on discord

-Trouble detecting smaller images.  This can be helped by lowering the "detection_threshold" value in the config file. Make sure it is between 0.1 and 1 (0.5 default)
