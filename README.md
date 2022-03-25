# QR-Code-Encoder-Decoder
You will learn how to create your own QR code and decode QR codes from an image by reading this repository. You should be able to include QR code capabilities into your own Python application at the conclusion of this. For this project, I'm utilising the python-qrcode package.

## Content
* [What is QR code?](#what-is-qr-code)
* [What information QR code takes?](#what-information-qr-code-takes)
* [Installation](#installation)
* [Procedure](#procedure)
* [Python code for basic example](#python-code-for-basic-example)

## What is QR code?
A QR code is a type of barcode that can be read easily by a digital device and which stores information as a series of pixels in a square-shaped grid, which can be read by any imaging device such as a camera, and processed to extract the required data from the patterns that are present in the horizontal components of the image.

Standard barcodes can only be read in one direction – top to bottom. That means they can only store a small amount of information, usually in an alphanumeric format. But a QR code is read in two directions – top to bottom and right to left. This allows it to house significantly more data.

The data stored in a QR code can include website URLs, phone numbers, or up to 4,000 characters of text.

## What information QR code takes?
QR code-generating software does not collect personally identifiable information.

The data it does collect – and which is visible to the code’s creators – includes location, the number of times the code has been scanned and at what times, plus the operating system of the device which scanned the code (i.e., iPhone or Android).

The QR codes themselves can’t be hacked – the security risks associated with QR codes derive from the destination of QR codes rather than the codes themselves.

## Installation
```python
pip install qrcode
```

The package will be installed in the system as the version of Python and pip.

Once the installation is complete, create a new Python file and type the following syntax in it.
```python
# importing the required module  
import qrcode
```
## Procedure
* Import module
* Create Qrcode with qrcode.make() and it returns a PilImage object.
* Save into image

## Python code for basic example
