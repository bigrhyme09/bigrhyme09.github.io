/*
Ghaji Mahbub
CSCI 39548
Professor Arezoo Bybordi
EMPLID 24127489
*/

QUESTIONS
1. Describe the path an HTTP Request takes from a browser to your GitHub Pages site.
Answer: /* 
When we enter bigrhyme09.github.io into our browser then the browser first performs a DNS lookup to translate that domain name into GitHub's numerical IP address. 
Once the IP address is identified the browser establishes a secure connection to GitHub's server using a TCP handshake followed by a TLS handshake for HTTPS encryption. 
It then transmits an HTTP GET request asking for the root webpage.
Upon receiving the request, GitHub's server reads the domain name, routes it directly to the  repository and locates my root index.html  file. 
The server returns a status along with my HTML code. 
As the browser reads through the document it then discovers the linked stylesheet and image, immediately sending follow-up requests to download style.css and headshot.jpeg before 
finally rendering the finished visual resume on the screen.

2. Use of AI.
Answer: Gemini AI. Prompt used- "Here is my resume that I have created, what would be the CSS code if I wanted to display it on a live site similar to https://about.me/waizrahim"
