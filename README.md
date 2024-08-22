# web-application-using-burp-suite

## Installation process

    wget "https://portswigger.net/burp/releases/download?product=community&version=2023.8.1&type=Linux" -O burpsuite_community_linux.sh
    
    chmod +x burpsuite_community_linux.sh
    
    ./burpsuite_community_linux.sh

## Verification

    burpsuite

## First Step for setting the proxy on brup suite and browser. below the the vedio link for this..

    https://youtu.be/70hvwmwfZeM?si=CciPshMIBFIZ83zD
## Now import burp suite certificate for capturing the https request. this is also avaiable in this vedio. 

   you have to export the certificate from burp suite and the import the same certificate in you browser setting... 
 
     https://youtu.be/70hvwmwfZeM?si=CciPshMIBFIZ83zD

remember to on the intercepter listener in brup suite for listening the browser traffic..

## step for adding the proxy of chrome browser

        To set Burp Suite to use the proxy address 127.0.0.1:8080 on an Ubuntu system, you'll need to configure your system or browser to route traffic through this proxy. Here’s how to do it:

    Option 1: Set Proxy for the Entire System
    Open the Network Settings:
    
    Click on the network icon in the system tray.
    Select "Settings" or "Network Settings."
    Configure the Proxy:
    
    In the Network settings window, look for "Network Proxy" or similar.
    Select "Manual" for the proxy configuration.
    Set the HTTP, HTTPS, and FTP proxy to 127.0.0.1 and port 8080.
    Leave other fields, like Socks Host, empty unless needed.
    Apply the changes.

    or 

## For Google Chrome:
    Google Chrome uses the system proxy settings. Follow Option 1 to set up the proxy for the entire system.
    
    go to the chrome setting and search **proxy** and then > open you computer proxy setting > it will open your system network setting and do obove steps accordingly... 


    Testing the Proxy:
    After setting up the proxy, open your browser and navigate to any website. Burp Suite should intercept the traffic, allowing you to monitor or modify it as needed.

## Adding burpsuite certificate in browser.

    go to browser setting and search certification > open certificate manager > open to authorities section and click **import** and import the burpcacert.der certification on browser from your system... after this restart your browser and search any website on browser. our burp suite will detect the traffic on burp suite software... once you forward packet from burp suite. Then package will get the response and will show this in brup suite...

## vedio link for burp suite web application scanning(penetration testing)

        https://www.youtube.com/watch?v=VP9eQhUASYQ&t=11s
