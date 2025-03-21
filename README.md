Tool Usage :- 
1) Download the tool .
2) Place it in /usr/local/bin
3) chmod +x /usr/local/bin/crawl
4) crawl -u https://example.com/ -o textfile -t threads
For example, the tool can crawl a domain like apple.com and fetch all the sensitive information found in its source code. It can then fetch JavaScript (JS) files and crawl them for sensitive information, as well as other links or paths associated solely with the domain. The tool is capable of crawling and providing links and secrets that match the domain and its subdomains, ensuring that no third-party links or paths are shown.



More Regex patterns on the way , still under development . Soon it will be able to disclover the tokens , keys , secrets like NPM_TOKEN , JWT_TOKEN, SQL_PASSWORDS, etc .
