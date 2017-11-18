# Block-Known-Attackers
```
curl https://raw.githubusercontent.com/VarunBatraIT/Block-Known-Attackers/master/bruteforcelogin.txt > bruteforcelogin.txt
while read line; do sudo ufw insert 1 deny from $line to any; done < bruteforcelogin.txt
```
