<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172821950-664bb083-8a47-4a26-b43d-e61551716b01.png" alt="MetrosCrypt" width="80px" height="80px">
</p>
<h1 align="center">MetrosCrypt</h1>

## Description
MetrosCrypt is for file encryption/decryption based on the <a href="https://pypi.org/project/cryptocode/">cryptocode</a> algorithm.<br>
It is written in <a href="https://python.org">Python</a> <a href="https://www.python.org/downloads/release/python-3104/">3.10.4</a> with the <a href="https://pypi.org/project/PyQt5/">PyQt5</a> graphics library.<br>
The program is distributed in forms as an open source python file.<br>
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/174428533-86632a84-3765-4cdb-8bd4-cf984460dd23.png" alt="MetrosCrypt">
</p>


## Other versions of the program
- <a href="https://github.com/John-MetrosSoftware/MetrosCrypt">MetrosCrypt</a> (Current)
- <a href="https://github.com/John-MetrosSoftware/MetrosCryptTerminal">MetrosCryptTerminal</a>
- <a href="https://github.com/John-MetrosSoftware/MetrosCryptTerminalGUI">MetrosCryptTerminalGUI</a> 

 


## Installation for python3
### Libraries
- <a href="https://pypi.org/project/cryptocode/">CryptoCode</a>
- <a href="https://pypi.org/project/PyQt5/">PyQt5</a>

```
git clone https://github.com/John-MetrosSoftware/MetrosCrypt
cd MetrosCrypt
pip3 install -r requirements.txt
python3 MetrosCrypt.pyw
```




## Usage
### Menu

<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/174428573-47a5333c-a369-4d68-868b-08ecebde7920.png" alt="MetrosCrypt">
</p>

#### File
- Quit - Exiting the program.


#### Reference
- <a href="https://github.com/John-MetrosSoftware/MetrosCrypt">Github</a>
- <a href="https://pypi.org/project/cryptocode/">Cryptocode</a>
- <a href="https://pypi.org/project/PyQt5/">Qt5
- <a href="https://www.python.org/downloads/release/python-3104/">Python 3.10.4</a>
- <a href="https://user-images.githubusercontent.com/107058068/174428649-31b95b9d-e9b1-4fcd-9e0f-b515e6dd7146.png">MetrosCrypt 1.1</a>


### File action
This list contains two elements. Select the item you need.<br>
To decrypt the file, you do not need to re-enter the password, but in encryption it is needed to avoid problems.
- Encryption file 
- Decryption file  
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/174428773-cfb4bf01-c762-446c-8ccf-96b00457936f.png" alt="MetrosCrypt">
</p>

### Input file
Input file input field if the file is found, the program will try to get the value of this file after decrypting or encrypting this value after writing it to the output file.<br>
If the input file is not found, then an error about not finding the input file will be displayed in red from below.<br>
It is important to note that if the output file is not found, the program will ask can the resulting output file be recorded?
- You can enter the path to the file manually or double-click on the field or click on the button next to it.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172826639-8898d3b4-026a-4c51-b329-d6cc120df451.png" alt="MetrosCrypt">
</p> 
  
### Output file
The output file is the file in which the encrypted or decrypted value will be written, it is not so necessary so that the value can be written to the output file.
- You can enter the path to the file manually or double-click on the field or click on the button next to it.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172827428-2b8337d3-df1a-4793-8128-bb192d38ded8.png" alt="MetrosCrypt">
</p>

### Password
The password is needed to encrypt or decrypt the contents of the file.<br>
If the decryption password is incorrect, an error will be displayed in red at the bottom.
- Password can be a void.
- You can also click on the button that is on the input line and show or hide password.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172828569-d1e4eaac-eb93-4612-8fd6-c3f72cbbc06d.png" alt="MetrosCrypt">
</p>

### Confirm Password
Summing up the password is a line in which the password must match the password input line.<br>
If the passwords are not equal to each other, an error will be displayed in red at the bottom.<br>
- You can also click on the button that is on the input line and show or hide password.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172832993-599e20ea-c87f-4d48-9d56-cb337e8744b5.png" alt="MetrosCrypt">
</p>

### Output result
This checkbox is responsible for not recording the result of encryption or decryption, but simply displaying it on the screen.<br>
Here the output file is not needed and it will not be needed.<br>
If the contents of the file cannot be encrypted or decrypted, an error will be displayed in red at the bottom.<br>
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172833779-bf808017-0c5b-416b-b5ba-ffe7a6259dac.png" alt="MetrosCrypt">
</p>

#### Encryption example
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/174428956-99bc1e48-1817-4817-88b3-b8a9a4b069c4.png" alt="MetrosCrypt">
</p>

#### Decryption example
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/174428985-65c447c8-16ca-45e7-b22a-0fc8863b593c.png" alt="MetrosCrypt">
</p>

These examples use the text: __test__<br>
Password: __123__<br>
In the title of the program you can notice the format:  
```
[ACTION] — FILE PATH — PROGRAM INFO
```
```
ACTION       — Encrypt or Decrypt.
FILE PATH    — The path to the input file.
PROGRAM INFO — Information about the program itself. 
```

#### Buttons
There are two buttons at the bottom. Depending on the action you choose to encrypt or decrypt the text of the first button, it will change, it is responsible for launching the algorithm. The second button is responsible for closing the main window.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/174428839-119d82e7-a1da-4de8-bb25-c24362d64a90.png" alt="MetrosCrypt">
</p>

#### Messages
If everything is successful, a window with a message will open.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172839319-6a47160a-1d2c-4c39-9950-12d57498231d.png" alt="MetrosCrypt">
</p>


 


## Possible errors
### Encryption file
- Apparently this file cannot be <b>encrypted</b>...

### Decryption file
- Apparently this file cannot be <b>decrypted</b>...

### Input file
Program could not find the input file.<br>
- The <b>input</b> file could not be found...

### Output file
If the program could not find the output file.<br>
- If you select <b>yes</b> then the result of encryption or decryption is recorded exactly the input file.<br>
- If you select <b>no</b>, the window will simply close.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172836221-e9e61e59-f32a-4469-a03a-a8bcb3fe4086.png" alt="MetrosCrypt">
</p>

### Confirm password
If, when comparing data from the password input lines and its confirmation, they are not equal to each other.
- Passwords don\'t match...

### Writing or reading a file
- Failed to record the result.

### Unknown error
If you have any problems with the program, write an email to the address below.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172838488-e17908cc-de72-41a9-9250-ee21b51e055f.png" alt="MetrosCrypt">
</p>

## Compilation
This version 1.0 is a version without saving any settings or changing them.<br>
All software is provided in English with executable files, these parameters cannot be changed.<br>
I usually compile my projects using the <a href="https://pypi.org/project/pyinstaller/">pyinstaller</a> compiler with the following parameters:
```
pyinstaller -F MetrosCrypt.pyw
```
Adding an icon for the executable file. You can use yours.
```
pyinstaller -F --icon=icon.ico MetrosCrypt.pyw
```
The icon 'icon.ico' can be downloaded from the <a href="https://download.flaticon.com/ru/download/icon/7721624?icon_id=7721624&author=3428&team=3428&keyword=%D0%97%D0%B0%D0%B1%D0%BB%D0%BE%D0%BA%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D1%82%D1%8C+%D1%82%D0%B5%D0%BB%D0%B5%D1%84%D0%BE%D0%BD&pack=7721572&style=Mixed&style_id=1285&format=png&color=%23000000&colored=2&size=512%2C256%2C128%2C64%2C32%2C24%2C16&selection=1&premium=&type=standard&token=03AGdBq27PWtVknlV1cRpjntK0Skz1AKUs7v05aWKzNZG9F9F1yHLUbVoqqHLhDfpK8xmzCy_x9G2NGGQQSrw0vEChiPOHlZmgZPetu8P7LXSfDhcC8z3JA3jzq1jBOmu6HY2-HXP0KnM0xxGUS5jHMiLMzbL2MkqQXPH-m4qb5HotPEgIVxndwWTEd9Cj-1J23E1mzETB-PDKitdhrT1poO-OUZMn6frg7_UeNLZZ2sejSqPLt7Da9jwr6RR7QX6_Is5EtM6kMfgGbXU2Zua2mZ8_todQdwNcm9scGi5CBQIpE4L93P1NfJBx18LhAzLutDC1lev_cHJ2RbgXUzZHX9kgvAD7v9j5kz5gfzBOGTEQtgcqwXxNWv2uL_O3Lg341o1TADm083QAFiJrJmoI1fCR8NrnHKyCJ6A795xI84u7pleo2Mm6FwhdFTUic9VUNzFt-dzvOvu_IuxAoE2D_V0dAlI2uS5jIfbAC1NvlL7Vndmc7SyxN_Zhx_0AE3sjvlcsYs2ougeWHcb7-G9nWyM1HXC5iHxp2nIT_ubAyOzDywS_MRYPq3vShzWtSKeJFuLcxNt9s1aWx-OMjRAj0HWu4LODOx3aotaLOXvpyQU0G1K_g2qpB6w3lSb-8V44LTZB5S1JUM3EivTDeMuMxATLXSOzWV6EJ3mNW5Auh3zdvJPMBX5qpXtmt1NeSGJN4K7gO-Ze5Cfuo7522pm_Mrlhbl2IwCnist4R8Y7mFSUIFSOUtEodfyj7X3PlhzIHWJ967QOilHLyxzoJxB3xZYWDIkVZshyNuorF6PjgaRmNLO7SL5ZmrRLirjhDEPPsY53LZjY-_yvg6BfdFstRv2dtYsZhZV5vwelpC8RkPMYITKRk4xdb7ivHMRb7_ZBpw68wmh8G3Sor0H7uT6INgbtjzJm0q4P9GT6RqXzF0ubFQojUofLfBA2jO355l5unIkwQgh-xoxamxGoSRdvVL_6qAJG7Bk9yuqkbimEmCRuplzgwbtLy_KsyTyi6nsWrGnhjASAv4UyA_AieVjmThe-e7g6ZXzuPXCLGjsVKEjb4XE_cQ2m5n14jxx4B8FgRydFbueUa4E7fLh1koHFJvB_YJK8_8r8BwuwSia2Q5CXHOmKJwUiMC6tvnyBIgFAW4TiMapmX2jMXO9A67kUr6M80V2P7hWietInTDOnAykx5vG032oz4o41UdehHbd6fuRVXrAAK1f10MNfrGn9jOyZG2ELmGCvxVcnhw-aAlgPLjr3ZGbcZVRGsYX0BTlc-XptVKZfIKN9b1UZVAlCa4ZctuNrXk2JEAhrKvFKQ6Oa_mb62Vt3cY2xOk_57QEHp9P-eNzh02Fv3OxfMUFtrvTQLp35G8VIzfWmDFTi4sGbBvbi9PUhF1RXwG7kGDda87u9a6RyWW6z8BPyi4KI2TOfbthI9A-A-IJgZi16Qms0tI1GmccP_aXw1FpZEAbvX46MlBhOmJsIu9hE89YOhwc3vhYmP0itR79A1oJw_EMK87KR1DM-JB4MMpt8y0kR71vhJgtqHeUFO&search=%D0%B7%D0%B0%D0%BC%D0%BE%D0%BA+%D0%B7%D0%B0%D0%BA%D1%80%D1%8B%D1%82%D1%8B%D0%B9">link</a>.<br>

## PEP8
<a href="https://pypi.org/project/autopep8/">autopep8</a> automatically formats Python code to conform to the PEP 8 style guide. It uses the pycodestyle utility to determine what parts of the code needs to be formatted. autopep8 is capable of fixing most of the formatting issues that can be reported by pycodestyle.
```
autopep8 MetrosCrypt.pyw --recursive --in-place
```
 
## Developer 
Telegram : https://t.me/metrossoftware



