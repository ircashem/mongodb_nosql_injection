# mongodb_nosql_injection
Blind Nosql injection leads to username/password enumeration in MongoDB using $(regex) and $(ne).

This python script can enumerate all available usernames and passwords from a mongodb database using nosql injection.<br />

Exploit Title: Blind Nosql injection leads to username/password enumeration in MongoDB using $(regex) and $(ne)

Author: Rahul Kumar

github: https://github.com/ircashem

Blog: https://ircashem.github.io

## How to run:

### Usage:
```
nosql_inject_user_pass_mongodb.py [-h] [-u URL] [-e Parameter 2 enumerate]
```

### Example:
```
python  nosql_inject_user_pass_mongodb.py -u http://example.com/index.php -e username
```
![alt test] (screenshot/usage.png)

![alt test] (screenshot/sample.jpg)
