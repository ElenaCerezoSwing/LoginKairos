# login-kairos

Polymer web component configurable to login in firebase

## <font color=red>VERY IMPORTANT!</font>
Before you go on following the instructions please notice this component is configured to operate on a firebase project. Hence, you should have a firebase project to integrate this component. :sweat_smile:  

## Demo
You could find our component demo at the link below    

[login-kairos demo ](https://jsfiddle.net/eparrado/r4q8oa2L/)    

Here, you could appreciate the look and feel of the logo

![loginkairoscode](https://user-images.githubusercontent.com/33294007/44092006-81b79140-9fcf-11e8-9986-40e290a17fd5.png)      

And if you just one to copy and paste, here is the code:  
  
<login-kairos   
domain= **"PUT_YOUR_FIREBASE_DOMAIN_HERE_WITHOUT_HTTPS_PROTOCOL"**   
apikey= **"PUT_YOUR_APIKEY_HERE"**  
hd= **"PUT_YOUR_HOST_DOMAIN_HERE"** 
provider="google">
\</login-kairos>  

*__hd example: "@gamil.com"*__ 


   
## Use

Make sure what is your bower version
      
    bower --version 
 or 
 
    bower --v
    
Make sure your version is up to 1.8.3 or even higher. If not, please update it  


In case you do not have bower installed, please use the following instruction:

    npm install bower -g

You need to create a bower.json to handle the dependencies:

    bower init

Answer to all questions and put Yes on this one:

    set currently installed components as dependencies? Yes

Then, you need to create a .bowerrc file to make sure that the component is installed in the public directory:

    touch .bowerrc
    echo '{
        "directory": "public/bower_components"
    }' > .bowerrc

Finally, install the component and save the dependency

    bower install --save https://github.com/ElenaCerezoSwing/LoginKairos.git    



#### Edit your HTML file and put the link to webcomponent into HEAD tags. It is necessary to use the POLYFILL script before the import  

Just to make even clearer this step you could read [Estela's article](https://medium.com/@E_parrado/polymer-to-chrome-and-beyond-bf4b25dbbc66)

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
    

You could also read at [Elena's article](https://medium.com/@elenacerezo83/mon%C3%B3meros-pol%C3%ADmeros-o-por-qu%C3%A9-est%C3%A1-tan-bien-elegido-el-nombre-de-polymer-c6826210f1b0) how to handle our component and its events.
    
### Authors
[Estela Parrado](https://github.com/Eparrado) & [Elena Cerezo](https://github.com/ElenaCerezoSwing), Front-end developers  

### License
This project is licensed under the [MIT License](https://github.com/ElenaCerezoSwing/LoginKairos/blob/master/LICENSE)


 
 
 
 
 
 
