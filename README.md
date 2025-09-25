# HTTP-Auth
The worst thing a developer can do is leave their API vulnerable. This project utilises JWT `(JSON Web Tokens)` and the `HS256` Algorithm to add authentication to your endpoints. 
The generated JWT strings serve as cryptographic evidence that the request made is authentic and coming from a real browser. **Therefore mitigating the risk of  misuse and abuse through private endpoints.**
# 

**I recommend using techniques to protect anyone from reversing the logic. Simple obfuscation like:**
- Utilising a [JavaScript Obfuscator](https://obfuscator.io/) to make your code unreadable. (Can be reversed)
- Using nonmeaningful variable names to make the code harder for someone to understand.
- Adding nonsensical code that has no real use in the file to make the real logic harder to find.
- Scrambling the Javascript to make it confusing.
<br>

**I believe that this simple auth project is enough for a small or medium website to secure their endpoints from bots.**



#
**To-Do:** <br>
Create a live demo website<br>
Use javascript for generation instead of an endpoint
