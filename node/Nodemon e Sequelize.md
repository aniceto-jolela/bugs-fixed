# <p align='center'> Nodemon and sequelize installation error </p>


## <p align='center'> Bug 🐞 </p>

```c
npm install nodemon
npm ERR! code ENOTFOUND
npm ERR! errno ENOTFOUND
npm ERR! network request to https://registry.npmjs.com/nodemon failed, reason: getaddrinfo ENOTFOUND 28 
npm ERR! network This is a problem related to network connectivity.
npm ERR! network In most cases you are behind a proxy or have bad network settings.
npm ERR! network
npm ERR! network If you are behind a proxy, please make sure that the
npm ERR! network 'proxy' config is set properly. See: 'npm help config'
```


## <p align='center'> Solution 🎉 </p>

<p align='center'>  Run below command in npm command prompt or Visual Studio Code terminal.</p>

- **Step 1**
 ```
    npm config rm proxy
    npm config rm https-proxy
```
- **Step 2**
 ```
    registry.npmjs.org
```
- **Step 3**
```
    registry.npmjs.org registry.npmjs.org:443
```
#

###### Author : Aniceto Jolela 🥰
 My  | [Linkedin](https://www.linkedin.com/in/aniceto-jolela-076547184/))
