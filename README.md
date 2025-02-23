# Secure Data Hiding in Images Using Steganography

## Overview

This project implements a steganography tool using Python to embed secret messages within image files. It utilizes the Least Significant Bit (LSB) modification technique and a user-provided passcode for basic protection.

*Note:* This is a foundational tool. While a passcode system is in place, it is *crucial* to understand that the current XOR-based passcode is *not secure for real-world applications.* Future development will focus on integrating robust encryption.

## Problem Statement

Develop a steganography tool using Python that can securely embed a secret message within an image file. The tool should utilize a user-provided passcode for basic protection, ensuring that only authorized individuals with the correct passcode can retrieve the hidden message. The implementation must maintain image fidelity, ensuring that the changes caused by embedding the message are imperceptible to the human eye. The solution should be robust, handling various message lengths and image types while providing a user-friendly experience for both embedding and extraction.

## Features

* *Data Hiding:* Embeds text messages within image files using LSB modification.
* *Basic Protection:* Uses a passcode (XOR-based) for hiding and retrieving messages.
* *User-Friendly:* Simple input/output.

## Technologies Used

* *Programming Language:* Python
* *Image Processing:* OpenCV (cv2)  (Assumed based on common steganography implementations)
* *Image Format:* JPG (Assumed based on common usage)

## Installation
pip install OpenCV-python
