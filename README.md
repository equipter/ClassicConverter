# ClassicConverter
Classic Converter is a python script that converts Mifare Classic binary files into [FlipperZero's](https://flipperzero.one/) custom .nfc format. 

**Note: Currently this is only for Mifare Classics with 4-Byte UIDs. further support is being added i just made this quickly**
  

## Acknowledgements
| [Github](https://github.com/equipter) | [Twitter](https://twitter.com/Equip0x80) | [Reddit](https://www.reddit.com/user/equipter) | equip paypal: equipter@outlook.com | [Discord](https://discord.gg/e9XzfG5nV5) |
| :---: | :---: | :---: | :---: | :---: |

 [Lucaslhm's Amiibo converter script for MFUL](https://github.com/Lucaslhm/AmiiboFlipperConverter) for code inspo

## Download and Usage
### **Requires Python**

1. Download code Either through `git clone` or by simply pressing the green [Code] Button at the top and downloading the zip. 
2. Place your (.bin) Binary files in the "assets" folder or create your own folder(s) and place the files in there.  
## Syntax 
The Parameters for ClassicConverter are as such 

`-i / --input-path` - mandatory file input location, link to file in directory or whole directory to be converted. 

`-o / --output-path` - optional file output location, if no output path is specified, the generated nfc file will be created in the same directory as the input binary file. 

### Example
`python3 ClassicConverter.py -i assets/example.bin`
after running you should be met with "Completed Conversion" and a new file appearing in your assets folder with the same name as your binary file but with a .nfc extension and file format. 

![image](https://user-images.githubusercontent.com/72751518/182514125-be1aedb1-59e9-4994-906a-df83f36c0f66.png)

![image](https://user-images.githubusercontent.com/72751518/182514195-c766ca6a-234f-43e9-a779-fce67894f5e6.png)




## Support

For support, Message Equip on discord Equip#1515 or join The discord server [Link](https://discord.gg/e9XzfG5nV5)

