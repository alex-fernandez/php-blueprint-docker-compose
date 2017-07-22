Docker Compose setup for Magento 2

## Instructions

docker-compose up


  Need to copy the styles.css to /media/


      http://magento2-demo.nexcess.net/pub/media/styles.css
 
   
 Recreate static files on /pub/static


    php bin/magento setup:static-content:deploy


 Stores -> Configuration -> Developer -> Static File Settings  = no