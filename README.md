# PASS-CRACKER

![Screenshot 2024-01-14 201332](https://github.com/KalyanSingh05/PASS-CRACKER/assets/95122829/908dcc87-44ec-493f-a24e-4747d807bee7)


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


### - For tesing hash
- **MD5** hash for "password" :
```
5f4dcc3b5aa765d61d8327deb882cf99
```

- **SHA-1** hash for "password" :
```
5baa61e4c9b93f3f0682250b6cf8331b7ee68fd8
```

**NOTE :** The provided Hashes are Example only for Testing;





- ### Dictionary file is also there for testing purpose
- ### SAMPLE ENCRYPTED FILES ARE ALSO THERE SO YOU CAN TEST THIS TOOL  (password:-123456)



