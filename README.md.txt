# Important
All testing is done on 1920x1080 screen, effects on different ratios are unknown

## Setup:
Open the "config.json" file as and change the names in parenthesis to match your PiShock login details, for example

{
  "api_username": "BillJones1",
  "api_apikey": "ffAjXWu7-3985-0563-F8hP-T2Nz6BUUJagY",
  "api_code": "GpE1dNBwH8U",
  "api_throttle_limit": 10,
  "api_name": "MultiShock"
}

Your API key can be found by logging into the PiShock website, going to Menu > Account > Generate API Key

Your API code can be generated in your PiShock controls, copy and paste this into the quotation marks

Place the image that the program will be looking for in the Images folder, do not rename or move this folder or the program may break.
Images within this folder can be named whatever as long as they are in jpeg, jpg, or png format.

All set! 

## Customisation:

The "api_throttle_limit" in the config can be changed to increase the number of requests sent at a time. Lowering this number will allow more requests to be sent, e.g. "api_throttle_limit" : 2, will allow the program to send one request every 2 seconds. This may impact CPU usage.

## Known Issues, report any issues to 'neazho1' on discord

-Trouble detecting smaller images
