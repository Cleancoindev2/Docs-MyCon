
**API's**

**REST-full API implantation of mycontract platform**

# **Introduction**

Welcome to the MyContract API! We are the leading platform for Smart Contract Creation, Deployment, Interaction and Token Offering.

# **Authentication**

A JSON Web Token is used to send information that can be verified and trusted by means of a digital signature. It comprises a compact and URL-safe JSON object, which is cryptographically signed to verify its authenticity, and which can also be encrypted if the payload contains sensitive information.
 

Application may request to access routes, services, or resources on behalf of that user. To do so, it uses an access token, which is in the form of a JWT token. user has to provide JWT token in header as a authorization in every subsequent request after login.

```axios.get('https://api.mycontract.co:3001/demo', {headers: {
Authorization:"yRQYnWzskCZUxPwaQupWkiUzKELZ49eM" //JWT Token}
})
```

```axios.post('https://api.mycontract.co:3001/demo', {headers: {Authorization:"yRQYnWzskCZUxPwaQupWkiUzKELZ49eM" //JWT Token},data: //JSON})```
