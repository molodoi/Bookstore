Create Magento 2.1.3 Theme
========================

Technologies & versions:
- Magento 2.1.3
- Less
- Grunt
- and more

Content
========================
- Create a basic storefront theme and structure for magento

Install
========================
- Git clone this project to app/design/frontend/Ticme/ : git clone https://github.com/molodoi/Ticme-Bookstore.git
- Return to root project folder, delete : rm -fR var/*
- Always in root project folder, delete : rm -fR pub/static/*
- Clean Cache : php bin/magento cache:clean
- Deploy : php bin/magento setup:static-content:deploy --area="frontend"