# DocSecure
DocSecure is a simple desktop application that helps verify certificates by scanning QR codes from uploaded certificate images.  
It checks the QR code and confirms whether the certificate is authentic or not.

## Features
- Upload a certificate image from your computer  
- Automatically scan the QR code on the certificate  
- Extract the verification link stored in the QR code  
- Check and confirm if the certificate is genuine  

## Tech Stack
- **Java (Swing)** – for creating the desktop user interface  
- **Python** – for handling QR code scanning  
- **OpenCV / QR detection libraries** – for detecting and reading QR codes  

## Architecture
Java Swing User Interface  
↓  
Python QR Code Scanner  
↓  
Verification Process  
↓  
Display Result to User  

## How To Run
1. Clone or download this repository to your system  
2. Install the required Python libraries (such as OpenCV)  
3. Open and run the Java application  
4. Upload a certificate image and start verification  

## Future Improvements
- Add a certificate search option  
- Store certificate details in a database  
- Keep a history of previous verifications  
