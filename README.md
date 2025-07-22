# -Windows-EC2-instance-using-PuTTY-with-the-Public-IPv4-address.


**Connect Windows EC2 with PuTTY** 

Get the Public IPv4 Address
Go to AWS Console > EC2 > Instances

Select your Windows instance

Copy the Public IPv4 address
→ Example: 3.110.45.78

**Convert .pem to .ppk (Using PuTTYgen)**
Open PuTTYgen

You can download it from: https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

Click Load

Select your .pem file (set file type to All Files if you don’t see it)

Click Save private key

Save as: your-key.ppk (you can skip the passphrase)

✅ You now have a .ppk file to use in PuTTY
