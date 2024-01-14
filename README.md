# PASS-CRACKER
```
____                   ____                _
|  _ \ __ _ ___ ___    / ___|_ __ __ _  ___| | _____ _ __  
| |_) / _` / __/ __|  | |   | '__/ _` |/ __| |/ / _ \ '__| 
|  __/ (_| \__ \__ \  | |___| | | (_| | (__|   <  __/ |
|_|   \__,_|___/___/   \____|_|  \__,_|\___|_|\_\___|_|
```

### Intoduction        
Simple CLI based password hash Craking tool.
Python based Password Cracker and Hash Identifier. This tool works on both linux(Kali linux, termux, ubuntu, etc.) and Windows.
It can identify hash type if you dont know the hash type, and you are confiused which type to be selected.

It supports 6 Different hash types:  
- MD5
- SHA-1
- SHA-224 
- SHA-256 
- SHA-384 
- SHA-512

This tool hash one more additional feature of generating dictionary, with the information you have about the target.

With the help of this tool you can perform dictioary attack over the file or text protected with hash algorithm.

It can be used to crack 
**Hashed String, Zip file, Rar file, MS-office(Excel, Word), and PDF.**


## Tested:
- **Windows**
- **Kali Linux**
- **Termux** 

## Usage:
### - For WINDOWS:
```python
pyhton pass-crcaker-win.py
``` 
- CLI will start.
{Make sure all the required libs/pkgs are installed, if not then install it with the help of: **pip install <pkg name>**}

### - For LINUX:
```bash
  git clone https://github.com/KalyanSingh05/PASS-CRACKER.git
```
```bash
  cd pass-cracker
```
```python
pip -r requirements.txt
```
```Python
python pass-crack-linux.py
```
- The **requirements.txt** will install all the libs required to run this tool.

- ### Dictionary file is also there for testing purpose
- ### SAMPLE ENCRYPTED FILES ARE ALSO THERE SO YOU CAN TEST THIS TOOL  (password:-123456)



