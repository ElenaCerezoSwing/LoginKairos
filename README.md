# login-kairos

Polymer web component configurable to login in firebase

## Demo
[login-kairos demo ](https://jsfiddle.net/eparrado/d3wsfbxp/)

          <login-kairos 
            domain="YOUR_FIREBASE_DOMAIN_HERE_WITHOUT HTTPS_PROPTOCOL"
            apikey="YOUR_APIKEY_HERE" 
            provider="google>
          </ogin-kairos>
## Use

> npm install bower -g
> mkdir myproyect && cd myproyect
> bower install --save https://github.com/ElenaCerezoSwing/LoginKairos.git
Edit your HTML file and put the link to webcomponent into HEAD tags

><head>
>   ...
>   <link rel="import" href="./bower_components/login-kairos/login-kairos.html">
>   ...
></head>


Put the component into the BODY and fill the configure attributes with firebase configuration:

><body>
>  ...
>  <login-kairos [atributos]></login-kairos>
>  ...
></body>

### Authors
[Estela Parrado](https://github.com/Eparrado) & [Elena Cerezo](https://github.com/ElenaCerezoSwing) - Front-end developers - 

### License
This project is licensed under the MIT License 


 
 
 
 
 
 
