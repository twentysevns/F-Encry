# F-Encry
Yet another Iteration Hash based Encryption Algorithm written in Bash (shell).

F-Encry is a simple Iteration symetrics Hash based Encryption algorithm, where is the Decryption key are using Encrypted value itself. These Keys are not part of seclists or other gigantic wordlist, its generate by value itself.



## Installation
```
git clone https://github.com/twentysevns/F-Encry.git
cd F-Encry
chmod +x f-encry
./f-encry
```

```


   _____     _____
  |   __|___|   __|___ ___ ___ _ _
  |   __|___|   __|   |  _|  _| | |
  |___\ v0.1|_____|_|_|___|__\\_  |
                        /_________|
  infosec [at] zphr.xyz
  [Iteration Hash based Encryption]


USAGE:
  ./f-encry -i <iterations> -c <value> [-a algorithm]

REQUIRED OPTIONS:
  -i <iterations>    Number of hash iterations to perform
  -c <value>         Initial value / content to hash

OPTIONAL OPTIONS:
  -a <algorithm>     Hash program to use (default: sha512sum)
                     Examples:
                     - md5sum
                     - sha1sum
                     - sha256sum
                     - sha512sum

  -h                 Show this help message and exit

OUTPUT FILES:
  key.txt             Final (highest sorted) hash
  keys.txt            All generated hashes

EXAMPLES:
  ./f-encry -i 5 -c hello
  ./f-encry -i 10 -c secret -a sha256sum
  ./f-encry -i 3 -c test -a md5sum

```
###

F-Encry inspired by Money Heist, Mr. Robots, and Women Entropy.
