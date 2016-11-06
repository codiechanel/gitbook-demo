# Cheatsheet 


## Latest React Router
```
npm install react-router@next
```
## Clone
```lang-sh
git clone -b mybranch --single-branch git://sub.domain.com/repo.git
```

{{ gitbook.time }}
{{ gitbook.version }}
## Connect Amazon
```javascript
AWS.config.region = 'us-east-1'; // Region
AWS.config.credentials = new AWS.CognitoIdentityCredentials({
    IdentityPoolId: 'IdentityPoolId',
});

AWS.config.credentials.get(function(){

})
```
