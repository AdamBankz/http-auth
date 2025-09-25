# HTTP-Auth
The worst thing a developer can do is leave their API vulnerable. This project utilises JWT `(JSON Web Tokens)` and the `HS256` Algorithm to add authentication to your endpoints. 
The generated JWT strings serve as cryptographic evidence that the request made is authentic and coming from a real browser. **Therefore mitigating the risk of  misuse and abuse through private endpoints.**
# 
As a passionate reverse engineer, I understand that anyone who is dedicated to bypassing the authentication can look at the Javascript on your website to mimic the token generation. However, unless you are a big company, I don't think this will be an issue.
# 
Still, I recommend using techniques to protect anyone from reversing the logic. Simple obfuscation techniques like:
* Utilising a [JavaScript Obfuscator](https://obfuscator.io/) to make your code unreadable (Can be reversed)
* Using nonmeaningful variable names to make the code harder for someone to understand
