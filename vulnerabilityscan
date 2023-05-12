import requests
import os
os.system('clear')
print(""" 
╔═════════════════════╗
║Vulnerability scanner║
╚═════════════════════╝

""")
print()
print()
domain = str(input("ENTER THE  TARGET SITE :"))

headers = requests.get(domain).headers

if 'x-frame-Options' in headers:
        print(" \033[91m [NOT VULNERABLE] " + domain)

else:
    print("\033[92m[VULNERABLE] " + domain)
