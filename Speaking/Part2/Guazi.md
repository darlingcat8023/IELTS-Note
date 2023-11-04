## Object-Q2: Describe a piece of good advice that you gave to someone

You should say:

1. Who you gave the advice to
2. What the advice was
3. Why you gave the advice
4. And explain how he/she followed your advice

### Tips

- dilemma: 困境

### Example

Well, today I want to talk about an interesting advice I remember well. That was 2019, I went to a new company. I led a small team and been responsible for a e-sign system for the whole company. 

A new security department had been established at that moment, and dedicated to audit the code which we committed to our system, and ensure there were no risks and sensitive imformation leak. 

They held a system whitch could scan our code carefully, so some of our direct URL start with 'http' or 'https' had been marked as high risk issues, and noticed us that we must fix them. One of my collegue were assigned to deal this. This assignment putted him into dilemma, so he asked me for some help. After an analyse, we realised it was quite difficute, beacuse the system dependecy were very complex and the system could really clash if we missed some details. Too many code called these urls, we cannot eliminate all the risk. So I suggested he can use a hook function. Endoded the direct url first so it wonn't exposed to the security system, then attached the hook to every encoded url, finally if they were called, the hook will execute before calling.  The hook will decode the url as its original. He fallowed my suggestion. 

Many team adopted my method after that. It saves a lot time cost and reduce the risks.