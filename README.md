
# EchoCash

A machine learning project to assist visually imapraired people to detect currency. It can detect USD, EURO and BDT. Trained with YOLO + convolution layers achieving precision of 98.61%

## How to use this model
This project is dsigned to use it on phone and using laptop/computer as local server.

1. Download the project on you laptop.
2. Download ngrok.exe from "**https://ngrok.com/downloads/windows?tab=download**" and run it. 
3. Paste "**ngrok http 5000**" and run on ngrok.exe
4. Take the "**https://xxxxxxxx.ngrok-free.app**" from it and replace the pre-existing line "**var socket = io.connect("wss://xxxxxxxx.ngrok-free.app");**" on static/script.js with your new address.
5. Run the server.py file on laptop/computer.
6. Visit the address you got "**https://xxxxxxxx.ngrok-free.app**" from phone. 
7. Start detecting!
