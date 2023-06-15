#### OverTheWire : --> [links](https://overthewire.org/wargames/bandit/bandit0.html)

#### Solutions for bandit (0 - 17)

#### Niveau 0:
```sh
ssh bandit.labs.overthewire.org -p 2220 -l bandit0
password: bandit0
exit
```

#### Niveau 0 - 1:
```sh
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
```
> NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL


#### Niveau 1 - 2:
```sh
ssh bandit1@bandit.labs.overthewire.org -p 2220
ls
chat ./-
```
> rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi


#### Niveau 2 - 3:
```sh
ssh bandit2@bandit.labs.overthewire.org -p 2220
ls
cat spaces\ in\ this\ filename
```
> aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG



#### Niveau 3 - 4:
```sh
ssh bandit3@bandit.labs.overthewire.org -p 2220
ls
cd inhere/
ls
ls -1a
cat .hidden
```
> 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe



#### Niveau 4 - 5:
```sh
ssh bandit4@bandit.labs.overthewire.org -p 2220
ls
ls -1a
cd inhere/
ls file ./\*
cat ./-file07
```
> lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR



###" Niveau 5 - 6:
```sh
ssh bandit5@bandit.labs.overthewire.org -p 2220
ls
cd inhere/
ls
find . -size 1033c
cat ./maybehere07/.file2
```
> P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU



#### Niveau 6 - 7:
```sh
ssh bandit6@bandit.labs.overthewire.org -p 2220
find / -user bandit7 -group bandit6 -size 33c
cat /var/lib/dpkg/info/bandit7.password
```
> z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S



#### Niveau 7 - 8:
```sh
ssh bandit7@bandit.labs.overthewire.org -p 2220
ls
cat data.txt | grep millionth
```
> TESKZC0XvTetK0S9xNwm25STk5iWrBvP



#### Niveau 8 - 9:
```sh
ssh bandit8@bandit.labs.overthewire.org -p 2220
cat data.txt | sort | uniq -u
```
> EN632PlfYiZbn3PhVK3XOGSlNInNE00t



#### Niveau 9 - 10
```sh
ssh bandit9@bandit.labs.overthewire.org -p 2220
ls
strings data.txt | grep =
```
> G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s



#### Niveau 10 - 11:
```sh
ssh bandit10@bandit.labs.overthewire.org -p 2220
ls
cat data.txt | base64 --decode
```
> 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

#### Niveau 11 - 12:
```sh
  ->ssh bandit11@bandit.labs.overthewire.org -p 2220
  ->ls
  ->cat data.txt | tr a-zA-Z n-za-mN-ZA-M
```
> JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv

#### Niveau 12 - 13:
```sh
ssh bandit12@bandit.labs.overthewire.org -p 2220
ls
cat data.txt
mkdir /tmp/pavan
cp data.txt /tmp/pavan
cd /tmp/pavan
ls
```
> wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw

#### Niveau 13 - 14:
```sh
ssh bandit13@bandit.labs.overthewire.org -p 2220
ls
ssh -i ./sshkey.private -p 2220 bandit14@localhost
```
> fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq



#### Niveau 14- 15:
```sh
ls
cat data.txt
mkdir/tmp/pavan
cp data.txt/tmp/pavan
cd/tmp/pavan
ls
file data.txt
xxd -r data.txt data1
file data1
mv data1 data2.gz
gzip -d data2.gz
file data2
mv data2 data3.bz2
bzip2 -d data3.bz2
file data3
mv data3 data4.gz
gzip -d data4.gz
file data4
tar -xvf data4
file data5.bin
tar -xvf data5.bin
file data6.bin
mv data6.bin data7.bz2
bzip2 -d data7.bz2
file data7
tar -xvf data7
file data8.bin
mv data8.bin
data9.gz
gzip -d data9.gz
file data9
cat data9
ssh bandit13@localhost
```
> jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt



#### Niveau 15 - 16:
```sh
ssh bandit15@bandit.labs.overthewire.org -p 2220
openssl s_client -connect localhost:30001 -ign_eo
jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt
```
> JQttfApK4SeyHwDlI9SXGR50qclOAil1


#### Niveau 16 - 17:
```sh
ssh bandit16@bandit.labs.overthewire.org -p 2220
nmap -A localhost -p 31000-32000
openssl s_client -connect localhost:31790
```


#### Niveau 17 - 18: 
```sh
ssh bandit17@bandit.labs.overthewire.org -p 2220
ls
diff passwords.old passwords.new
The < sign represents the lines that have been removed and the > sign represents the lines that have been added in its place
The line after the > sign is the password for the next level
```
