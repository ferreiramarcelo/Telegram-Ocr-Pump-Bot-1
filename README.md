# Telegram OCR based Pump & Dump Script

## Contributors:   
Soner ABAY  
Contact: sonerabay@ikudeeplearning.com  

Ozan YURTSEVER   
Contact: ozanyurtsever95@gmail.com

## Description

This script was designed to process images from telegram groups and automatically purchase if a coin name is given in the image and to place a sale order at a certain value which you adjusted in script.

## Prerequrities

*Google Tesseract OCR  
*telathon  
*python-binance API

## How to Use

1. Create your telegram session file.  
2. Run image.py
3. test4.py  

After these steps, script will be waiting for an image from your telegram pump group and as soon there is an image, script will analyize the image, catch the coin name, place a buy order then a sell order with pre-adjusted profit.

### Additionally

Run update.py at least once a week to update minimum quantitiy and minimum price
