<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172821950-664bb083-8a47-4a26-b43d-e61551716b01.png" alt="MetrosCrypt" width="80px" height="80px">
</p>
<h1 align="center">MetrosCrypt</h1>

## Description


MetrosCrypt is for file encryption/decryption based on the <a href="https://pypi.org/project/cryptocode/">cryptocode</a> algorithm.<br>
It is written in <a href="https://python.org">Python</a> <a href="https://www.python.org/downloads/release/python-3104/">3.10.4</a> with the <a href="https://pypi.org/project/PyQt5/">PyQt5</a> graphics library.<br>
The program is distributed in forms as an open source python file and an executable file for Linux and Windows.<br>

<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172822319-d5e2fee6-7765-4644-ab1c-529d1ebfafde.png" alt="MetrosCrypt">
</p>
In executable files, the program is exclusively in English with a dark theme without the possibility of changing settings.
When you hover over a program element, a hint will be displayed that this element should contain.

## Installation for linux
<table>
   <tr>
      <th>Name of the executable file</th>
      <th>Version</th>
      <th>MD5</th>
      <th>VirusTotal</th>
      <th>Download</th>
   </tr>
   <tr>
      <td>MetrosCrypt</td>
      <td>1.0</td>
      <td>cf8bc8a3f536c76b0d3601f2556f3e30</td>
      <td><a href="https://www.virustotal.com/gui/file/976468e744ab0785898b2a1b06638a7c70a86a8919c69fcecbe91b05b3dcae9b?nocache=1">VirusTotal</a></td>
      <td><a href="https://github.com/John-MetrosSoftware/MetrosCrypt/releases/tag/MetrosCryptLinux">Download for linux</a></td>
   </tr>
</table>

## Installation for windows
<table>
   <tr>
      <th>Name of the executable file</th>
      <th>Version</th>
      <th>MD5</th>
      <th>VirusTotal</th>
      <th>Download</th>
   </tr>
   <tr>
      <td>MetrosCrypt.exe</td>
      <td>1.0</td>
      <td>4fede90aa1f824304a741ed389b44905</td>
      <td><a href="https://www.virustotal.com/gui/file-analysis/NGZlZGU5MGFhMWY4MjQzMDRhNzQxZWQzODliNDQ5MDU6MTY1NDcxMDMyMQ==">VirusTotal</a></td>
      <td><a href="https://github.com/John-MetrosSoftware/MetrosCrypt/releases/tag/MetrosCryptWindows">Download for windows</a></td>
   </tr>
</table>

## Installation for python3
```
git clone https://github.com/John-MetrosSoftware/MetrosCrypt
cd MetrosCrypt
pip3 install -r requirements.txt
python3 MetrosCrypt.pyw
```
## Usage
### File Action
This list contains two elements. Select the item you need.<br>
To decrypt the file, you do not need to re-enter the password, but in encryption it is needed to avoid problems.
- Encryption file 
- Decryption file  
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172824359-093258f1-ff77-4733-b0a2-0cf73f9fb01c.png" alt="MetrosCrypt">
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
  <img src="https://user-images.githubusercontent.com/107058068/172834177-3d1284d6-8174-47b4-8835-7a6ec17c1c96.png" alt="MetrosCrypt">
</p>

#### Decryption example
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/107058068/172834390-74818807-0b54-4e0e-a866-a6e7dd24f019.png" alt="MetrosCrypt">
</p>

These examples use the text: __test__<br>
And password: __123__<br>
In the title of the program you can notice the format:  
```
[ACTION] - FILE PATH - PROGRAM INFO
```
```
ACTION       - Encrypt or Decrypt.
FILE PATH    - The path to the input file.
PROGRAM INFO - Information about the program itself. 
```
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

