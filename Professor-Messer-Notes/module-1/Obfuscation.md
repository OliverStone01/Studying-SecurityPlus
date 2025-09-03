#### 🎓 Professor Messer Study Notes

## Obfuscation - CompTIA Security+ SY0-701 - 1.4

[Link to video](https://youtu.be/LfuTMzZke4g?si=sfvFCrdt9nMsOexn)

### Notes

Obfuscation is the process of making something that is usually very clear to understand and making it very difficult to understand.

If you know how the obfuscation was done, then you are able to reverse the process and reveal the original data.

Steganography is the the process of obfuscating data in an image file.

Steganography is Greek for concealed writing.

Becuase you can reverse the process of obfuscation, the term security through obfuscation is not secure at all.

The data in the image is known as the cover text.

You can also use network tcp packets to obfuscate data by sending small bytes in the packet that if the other person reconstructs, they can reveal the original data.

Another type is invisible watermarks. These are commonly seen on printers where small yellow dots are applied to to the print so that you can identify the printer that printed the sheet.

Audio steganography is hiding data in audio files.

Video steganography is hiding data in video files.

Tokenisation is the act of taking sensitive information and replace it with a token. This means when you are sending sensitive information, if someone intercepts that information, they will see the token number and not the sensitive data.

This is what happens with your cards and mobile phone when you pay for something. The token is a one time use only and will not be connected to the information after use.

This means we dont need to encrypt this data when its being sent over the network becuase it can't be traced back if someone intercepts it.

To create these tokens and for the merchant to collect payments. We first send our card information using our device to a remote token service server. This server then returns tokens we can use that link to our card information.

We then use these tokens to send to the merchant who then sends these back to the remote token service server who then provides our banking information.

Once that token has been user, it is discarded by your device. 

Data masking is the act of covering data to prevent others from getting access to that information. This is commonly seen on receipts with your card information. 

We can also reshuffle the number or use random numbers to obfuscate the data.

