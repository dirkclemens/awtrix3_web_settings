# web based settings for Awtrix3

For the Ulanzi Pixel Smart Clock TC001  
https://www.ulanzi.de/products/ulanzi-pixel-smart-uhr-2882   
using the firmeware from https://blueforcer.github.io/awtrix3/

To run it on a local server in the same network as the Ulanzi clock, just copy it to the server e.g. to /var/www/ulanzi/index.htm    
and replace the `baseUrl` in the code with your Awtrix IP like 
`const baseUrl = 'http://[Awtrix-IP]/api';`

To run it on the Ulanzi device, go to the Ulanzi web interface http://[your-Awtrix-IP]/edit    
and upload the file to the root folder, but do not rename it. Do not forget to change to Awtrix-IP!    
<img width="60%" alt="webupload" src="https://github.com/user-attachments/assets/9fac36c4-899f-4c2d-a485-bec934c5fa5e">

Tested with Awtrix3 version 0.96

![Awtrix3 Pixel Clock Controller](https://github.com/user-attachments/assets/058752bf-555b-4b7d-ac99-c49051ff36cd)
