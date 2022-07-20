<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172821950-664bb083-8a47-4a26-b43d-e61551716b01.png" alt="MetrosCrypt" width="80px" height="80px">
</p>
<h1 align="center">MetrosCrypt</h1>

## Description
MetrosCrypt is for file encryption/decryption based on the <a href="https://pypi.org/project/cryptocode/">cryptocode</a> algorithm.<br>
It is written in <a href="https://python.org">Python</a> <a href="https://www.python.org/downloads/release/python-3104/">3.10.4</a> with the <a href="https://pypi.org/project/PyQt5/">PyQt5</a> graphics library.<br>
The program is distributed in forms as an open source python file.<br>
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177595608-46573ce5-1c76-430e-8858-5b0ded337d02.png" alt="MetrosCrypt">
</p>

 


## Other versions of the program
- <a href="https://github.com/John-MetrosSoftware/MetrosCrypt">MetrosCrypt</a> (Current)
- <a href="https://github.com/John-MetrosSoftware/MetrosCryptTerminal">MetrosCryptTerminal</a>
- <a href="https://github.com/John-MetrosSoftware/MetrosCryptTerminalGUI">MetrosCryptTerminalGUI</a> 

 


## Installation for python3
### Libraries
- <a href="https://pypi.org/project/cryptocode/">cryptocode</a>
- <a href="https://pypi.org/project/PyQt5/">pyqt5</a>

```
git clone https://github.com/John-MetrosSoftware/MetrosCrypt
cd MetrosCrypt
pip3 install -r requirements.txt
python3 MetrosCrypt.pyw
```




## Usage
### Menu
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177597556-a93a9e33-78db-4f0d-a362-b090817b9169.png" alt="MetrosCrypt">
</p>

#### File
- Quit - Exiting the program.

#### Reference
- <a href="https://github.com/John-MetrosSoftware/MetrosCrypt">Github</a>
- <a href="https://pypi.org/project/cryptocode/">Cryptocode</a>
- <a href="https://pypi.org/project/PyQt5/">Qt5
- <a href="https://www.python.org/downloads/release/python-3104/">Python 3.10.4</a>
- <a href="https://user-images.githubusercontent.com/107058068/177601775-e9b9a168-10eb-4fca-a9a6-cbe9cc11defb.png">MetrosCrypt 1.2</a>


### File action
This list contains two elements. Select the item you need.<br>
To decrypt the file, you do not need to re-enter the password, but in encryption it is needed to avoid problems.
- Encryption file 
- Decryption file  
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177598419-d68e3209-4ee6-4826-9295-782a2f08280a.png" alt="MetrosCrypt">
</p>

### Input file
Input file input field if the file is found, the program will try to get the value of this file after decrypting or encrypting this value after writing it to the output file.<br>
If the input file is not found, then an error about not finding the input file will be displayed in red from below.<br>
It is important to note that if the output file is not found, the program will ask can the resulting output file be recorded?
- You can enter the path to the file manually or double-click on the field or click on the button next to it.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177598738-acb5cbf8-36b0-4663-8005-3b6802afec1a.png" alt="MetrosCrypt">
</p> 
  
### Output file
The output file is the file in which the encrypted or decrypted value will be written, it is not so necessary so that the value can be written to the output file.
- You can enter the path to the file manually or double-click on the field or click on the button next to it.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177598844-6cf60533-8f26-4e01-94b9-36e958e0adf2.png" alt="MetrosCrypt">
</p>

### Password
The password is needed to encrypt or decrypt the contents of the file.<br>
If the decryption password is incorrect, an error will be displayed in red at the bottom.
- Password can be a void.
- You can also click on the button that is on the input line and show or hide password.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177598902-05a66607-62a7-42f0-bda8-42c8e3db7240.png" alt="MetrosCrypt">
</p>

### Confirm Password
Summing up the password is a line in which the password must match the password input line.<br>
If the passwords are not equal to each other, an error will be displayed in red at the bottom.<br>
- You can also click on the button that is on the input line and show or hide password.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177598992-b263526a-356a-4dfe-a727-5d99df94fcae.png" alt="MetrosCrypt">
</p>

### Output result
This checkbox is responsible for not recording the result of encryption or decryption, but simply displaying it on the screen.<br>
Here the output file is not needed and it will not be needed.<br>
If the contents of the file cannot be encrypted or decrypted, an error will be displayed in red at the bottom.<br>
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177599117-e963dcf6-ebfb-46f7-9bc5-b7db12ecdfcf.png" alt="MetrosCrypt">
</p>

#### Encryption example
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177599593-c0353d93-bb82-4530-ba66-440c923f49c3.png" alt="MetrosCrypt">
</p>

#### Decryption example
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177599734-e9baddfd-e103-43ed-9280-7a4fed7338d9.png" alt="MetrosCrypt">
</p>

The example uses text `test` and password `12345678`.

#### Title
In the title of the program you can notice the format:  
```
<action> — <file_path> — <program_info>
```
 

<table>
   <tr>
    <th>Element</th>
    <th>Designation</th>
 
   </tr>
 
   <tr><td>action</td><td>Your choice of action to encrypt and decrypt.</td></tr>
   <tr><td>file_path</td><td>Path to input file.</td></tr>
   <tr><td>program_info</td><td>Information about the program itself. </td></tr>
 
  </table>
  

#### Buttons
There are two buttons at the bottom. Depending on the action you choose to encrypt or decrypt the text of the first button, it will change, it is responsible for launching the algorithm. The second button is responsible for closing the main window.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177600291-18a623ad-7694-47db-9744-d11f38efd597.png" alt="MetrosCrypt">
</p>

#### Messages
If everything is successful, a window with a message will open.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177600217-a33051c2-c93f-424e-b684-b3d2a380b448.png" alt="MetrosCrypt">
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
  <img src="https://user-images.githubusercontent.com/107058068/177600161-25c74116-1ff5-4a0e-b774-38ef66013025.png" alt="MetrosCrypt">
</p>

### Confirm password
If, when comparing data from the password input lines and its confirmation, they are not equal to each other.
- Passwords don\'t match...

### Writing or reading a file
- Failed to record the result.

### Unknown error
If you have any problems with the program, write an email to the address below.
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/177601518-adc14568-b5f7-40d1-8961-6c37805f8489.png" alt="MetrosCrypt">
</p>

## Compilation
This version `1.2` is a version without saving any settings or changing them.<br>
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
 


