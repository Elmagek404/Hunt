A Python-based exploit script for the Escape_202 web challenge on CyberTalents. The script automates the exploitation process by sending a crafted HTTP POST request, searching for .txt files through the vulnerable search functionality,
and attempting to extract and display the challenge flag from the server's response.

**Challenge**: Escape_202 

**Level**: Medium

**Vulnerability**: PHP Remote Code Execution   

## Features
**Automated Exploitation**: Sends a crafted POST request to the target endpoint.

**Command Injection Payload**: Uses a specially crafted search parameter to attempt to read matching text files.

**Flag Detection**: Checks the HTTP response for the Flag{...} pattern.

**Install the required dependency:**

```pip install requests```

## install  

```
git clone https://github.com/Elmagek404/Hunt
```

## Usage 
```
python exploit.py -u "http://TARGET_URL/"

```
