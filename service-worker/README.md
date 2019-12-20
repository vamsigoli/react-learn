# react-conf-service-worker

## Clone Project

## Run some type of server in the root of the file. I use http-server
this demo was taken from react conf 2018 video for cross window communication from the
same application. Service worker is used to achieve the functionality. in the standard 
react app also we see a service worker created. it is used for progressive app construction
normally that file is not required so people delete it. 

http-server also supports secure mode with -S option. for that   
 openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
    
Also, the company name should be same as the address you type on the browser.   
If you give 127.0.0.1 as company name in the certificate, then 127.0.0.1 will be trusted and    
things will work as expected if https://127.0.0.1 is given in the browser   

Any other address like local host will cause problem and the example wont work as the    
certificate is not trusted and serviceWorker is not initialized correctly.   

Also in production, service workers will work only in https mode.      
 


