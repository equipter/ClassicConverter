# ClassicConverter
Classic Converter is a python script that converts Mifare Classic binary files into [FlipperZero's](https://flipperzero.one/) custom .nfc format. 

Worth noting, ClassicConverter also handles all of the below for the file header:
- UID
- SAK
- ATQA
- Storage Size 

**Works for 4-Byte UIDs and 7-Byte UIDs just make sure youre using the correct script when converting :)**

 [Lucaslhm's Amiibo converter script for MFUL](https://github.com/Lucaslhm/AmiiboFlipperConverter) for code inspo

## Download and Usage
### **Requires Python**

1. Download code Either through `git clone` or by simply pressing the green [Code] Button at the top and downloading the zip. 
2. Place your (.bin) Binary files in the "assets" folder or create your own folder(s) and place the files in there. 
3. pick the right converter for you, 4B_Converter is for 4-byte UID classics, 7B_Converter is for 7-Byte UID Credentials, 7B_DI_Converter is for 7-Byte UID Credentials that require a Key A.

**Note:** 7B_DI_Converter converts from bin to nfc and generates necessary keys for Disney infinity figures 
## Syntax 
The Parameters for ClassicConverter are as such 

`-i / --input-path` - mandatory file input location, link to file in directory or whole directory to be converted. 

`-o / --output-path` - optional file output location, if no output path is specified, the generated nfc file will be created in the same directory as the input binary file. 

### Example
in this example ill be using the 4B uid credential converter. use whats right for your card though. 

`python3 4B_Converter.py -i assets/example.bin`
after running you should be met with "Completed Conversion" and a new file appearing in your assets folder with the same name as your binary file but with a .nfc extension and file format. 

![image](https://user-images.githubusercontent.com/72751518/182514125-be1aedb1-59e9-4994-906a-df83f36c0f66.png)

![image](https://user-images.githubusercontent.com/72751518/182514195-c766ca6a-234f-43e9-a779-fce67894f5e6.png)




## Support
If the SAK in your converted file is wrong it's due to an anti-cloning tactic. read about it here and how to fix it [link](https://gist.github.com/equipter/3022aea4e371e585ff6e46de637e7769)

For support, Message Equip on discord

