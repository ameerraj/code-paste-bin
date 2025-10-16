How to use: 

1. access this link https://code-paste-bin.vercel.app/
2. Use a custom 2 digit code of your choice (2-4 digits is the allowed range) on the top left corner 
3. hit connect and do the same on your other device
4. You now have a collaborative text box between devices. (which updates at almost live)


Why: 
I needed a quick way of handling transferring of code and debug notices/errors from one device to another. 
My primary work computer is connected to the intranet of a company and makes reaching LLMs or websites to post coding related questions impossible as it was either blocked or made unavailable
The solution was then to implement a simple website on my own to be able to copy paste non-sensitive data to another device outside the intranet. 


How: 
The front end is built on Vercel services pulling the HTML from Github 
Back end is hosted on Google Firebase Cloud Services (this is how I ensure decent performance)
