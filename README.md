
# Bech Daal 

It is a dummy OLX app which serves the purpose of buying and selling old products.

FOLLOWING ARE THE API END POINTS AVAILABLE IN THIS APPLICATION

```
     * user/login  : LOGIN PAGE
     
     * user/signup  : SIGNUP PAGE
     
     * user/dashboard  : Dashboard PAGE
     
     * product/all  : All Products page
     
     * product/:id  : Get Single Product Page
     
     * product/delete/:id  : Delete product
     
     * cart/all : VIEW CART PAGE
   
     * cart/add/:id  : Add to cart
  
     * cart/delete/:id  : Delete from cart

     * password/forgot : FORGOT password page

     * password/update : Update password

```

INSTRUCTIONS TO RUN WITHOUT DOCKER

```

1. Clone the repo: https://github.com/PoojaK97/BechDaal.git
2. Change into the directory
3. Run: npm install
4. Run: npm start

```

INSTRUCTIONS TO RUN ON DOCKER

```

1. Run: docker run kruthikakalmali/bech-daal
2. Open "http://<replace with The ip address that your docker is configured with>:8000"

```

YOU CAN ACCESS THE APP HERE (HOSTED ON PIVOTAL-CLOUD FOUNDRY)
https://bech-daal.cfapps.io
