# Cheatsheet 


## Latest React Router

```npm install react-router@next```

Clone branch only

```git clone -b mybranch --single-branch git://sub.domain.com/repo.git```

## Connect Amazon
```javascript
AWS.config.region = 'us-east-1'; // Region
AWS.config.credentials = new AWS.CognitoIdentityCredentials({
    IdentityPoolId: 'IdentityPoolId',
});

AWS.config.credentials.get(function(){

})
```
