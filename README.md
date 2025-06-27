# 🇮🇩 Indonesian Password Wordlist  
**Curated real Indonesian passwords for penetration testing & security audits**  

## Overview  
This repository contains a specialized collection of Indonesian passwords, designed for ethical hacking, penetration testing, and security assessments. The wordlist is meticulously curated to reflect real-world password patterns in Indonesia, aiding in brute-force attacks, password cracking, and vulnerability validation .  

## Features  
- **Indonesian-Specific Focus**: Includes common names, phrases, and cultural references unique to Indonesia.  
- **Real-World Data**: Aggregated from open-source intelligence (OSINT) and anonymized datasets.  
- **Penetration Testing Ready**: Optimized for tools like **Hashcat**, **John the Ripper**, and **Hydra** .  
- **Ethical Use**: Intended solely for authorized security testing and educational purposes .  

## Usage  
### Clone the Repository  
```bash  
git clone https://github.com/elliottophellia/wordlist.git  
cd wordlist  
```  

### Example Commands  
- **Hashcat**:  
  ```bash  
  hashcat -m 0 -a 0 hash.txt wordlist.txt  
  ```  
- **John the Ripper**:  
  ```bash  
  john --wordlist=wordlist.txt hashes  
  ```  
- **Dirb/Dirbuster**:  
  ```bash  
  dirb http://target.com wordlist.txt  
  ```  

## Disclaimer  
This wordlist is **strictly for educational and authorized security testing**. Unauthorized use for malicious activities is prohibited and may violate local laws. The author assumes no liability for misuse .  


## License  
```
Attribution-ShareAlike 4.0 International

=======================================================================

Creative Commons Corporation ("Creative Commons") is not a law firm and
does not provide legal services or legal advice. Distribution of
Creative Commons public licenses does not create a lawyer-client or
other relationship. Creative Commons makes its licenses and related
information available on an "as-is" basis. Creative Commons gives no
warranties regarding its licenses, any material licensed under their
terms and conditions, or any related information. Creative Commons
disclaims all liability for damages resulting from their use to the
fullest extent possible.
```
