# HTTPS proxy

## create sertificate on Linux server
create_cert.sh

## import sertificate as root in Windows
https://www.ssls.com/knowledgebase/how-to-import-intermediate-and-root-certificates-via-mmc/

## start Chrome with proxy
"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --proxy-server="https://localhost:8888" --user-data-dir="%LOCALAPPDATA%\Google\Chrome-proxy01\User Data"


### article
https://medium.com/@mlowicki/http-s-proxy-in-golang-in-less-than-100-lines-of-code-6a51c2f2c38c
