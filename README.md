# Ringzer0-Web-CTF-Solve
Write-up OF Web Challenges For Ringzer0team

## JavaScript : Client side validation is so secure ?

### First : we will see source code

we will notice That

![1](https://user-images.githubusercontent.com/20526772/43558614-a7b83d0a-960a-11e8-9247-0b1f98caab19.PNG)

so the user name is : **admin**
the password is : **String.fromCharCode(74,97,118,97,83,99,114,105,112,116,73,115,83,101,99,117,114,101)**
so this is **Unicode** and this function decode it auto when u type the password and compare so simply we will jump to **Second stage**
### Second : Decode This Unicode char.
The Best Site For This stuff is (http://jdstiles.com/java/cct.html)
So After Decode it by this site the password will apper

## JavaScript : Is hashing more secure?

### First : We Will Look At Source Code

We Will Find This Hash 

> b89356ff6151527e89c4f3e3d30c8e6586c63962

so we will use this site to know what type of this hash [hash-identification](https://www.onlinehashcrack.com/hash-identification.php#results)

**The hash is Sha-1**

### Second : We Will Decrypt it 

you can use hash-cat or any website to decrypt sha-1 

So the Password is : **adminz**

## SQL-INJECTION : Bypass Me If You Can

so it's Sqli we will try some payloads to understand the sql code 

after lot of payloads u will u the best payload to bypass it is :

**Username** : **Admin**

**Password** : **' or ''='**

