# Ringzer0-Web-CTF-Solve
Write-up OF Web Challenges For Ringzer0team

## JavaScript : Client side validation is so secure 

### First : we will see source code

we will notice That

![1](https://user-images.githubusercontent.com/20526772/43558614-a7b83d0a-960a-11e8-9247-0b1f98caab19.PNG)

so the user name is : **admin**
the password is : **String.fromCharCode(74,97,118,97,83,99,114,105,112,116,73,115,83,101,99,117,114,101)**
so this is **Unicode** and this function decode it auto when u type the password and compare so simply we will jump to **Second stage**
### Second : Decode This Unicode char.
The Best Site For This stuff is (http://jdstiles.com/java/cct.html)
So After Decode it by this site the password will apper
