# UPI QR Code Generator

This Python project generates QR codes for UPI payments using a user-entered UPI ID.
It creates three separate QR codes compatible with PhonePe, Paytm, and Google Pay, saves them as images, and displays them automatically.

# Features

Takes UPI ID from the user

Generates QR codes for:

PhonePe

Paytm

Google Pay

Saves each QR code as a PNG file

Displays each QR code after generation

Simple and lightweight (only needs the qrcode library)


# How It Works

The script constructs a UPI payment URL in this format:

upi://pay?pa=<upi_id>&pn=Recipient%20Name&mc=1234

This URL is then converted into a QR code for each supported payment app.
