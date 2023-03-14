import requests
import sys


def main():
    if len(sys.argv) != 2:
        print(f"Usage: python3 {sys.argv[0]} https://<targetIP>/hpoa")
        return

    postheaders = {"Origin":"Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/47.0.2526.106 Safari/537.36",
            "Referer":"https://127.0.0.1/", #This is really not needed but what ever.
            "Accept-Encoding":"gzip, deflate",
            "Accept-Language":"en-US,en;q=0.8"
            }

    postdata = """<?xml version="1.0"?><SOAP-ENV:Envelope xmlns:SOAP-ENV="http://www.w3.org/2003/05/soap-envelope" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:wsu="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-wssecurity-utility-1.0.xsd" xmlns:wsse="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-wssecurity-secext-1.0.xsd" xmlns:hpoa="hpoa.xsd"><SOAP-ENV:Body><hpoa:getSoapInterfaceInfo/></SOAP-ENV:Body></SOAP-ENV:Envelope>"""


    p = requests.post(sys.argv[1],data=postdata,headers=postheaders,verify=False)

    print(p.text)

if __name__ == "__main__":
    main()
