# login-kairos

Polymer web component configurable to login in firebase

## <font color=red>VERY IMPORTANT!</font>
Before you go on following the instructions you should have a firebase project to use this component in it. Otherwise, it will be not possible to use it because all the configuration settings are based on firebase projects. :sweat_smile:

## Demo
[login-kairos demo ](https://jsfiddle.net/eparrado/r4q8oa2L/)

          <login-kairos 
            domain="YOUR_FIREBASE_DOMAIN_HERE_WITHOUT HTTPS_PROPTOCOL"
            apikey="YOUR_APIKEY_HERE" 
            provider="google">
          </login-kairos>
## Use

Make sure what is your bower version
      
    bower --version 
 or 
 
    bower --v

In case you do not have bower installed, please use the following instructions:

    npm install bower -g
    cd myproyect
    cd /public "or in the folder where you have your index.html"
    bower install --save https://github.com/ElenaCerezoSwing/LoginKairos.git
    bower install --save polymerfire
    
    
#### Edit your HTML file and put the link to webcomponent into HEAD tags. It is necessary to use the POLYFILL script before the import

    <head>
     ...    
     <script src="/bower_components/webcomponentsjs/webcomponents-loader.js">
     </script>
     <link rel="import" href="/bower_components/login-kairos/login-kairos.html">
     ...
    </head>
    
#### Put the component into the BODY and fill the configure attributes with firebase configuration:

    <body>
      ...
      <login-kairos [attributes]></login-kairos>
      ...
    </body>
    
#### POLYFILLS: To make sure our component is supported in other browsers apart from chrome, write down these tags in your HTML


### Authors
[Estela Parrado](https://github.com/Eparrado) & [Elena Cerezo](https://github.com/ElenaCerezoSwing) , Front-end developers  

### License
This project is licensed under the [MIT License](https://github.com/ElenaCerezoSwing/LoginKairos/blob/master/LICENSE)


 
 
 
 
 
 
