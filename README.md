# CFX Finder API
## Preview

![https://cdn.discordapp.com/attachments/837433594376880138/837434545741103104/unknown.png](https://cdn.discordapp.com/attachments/837433594376880138/837434545741103104/unknown.png)

## About
* This is a `CFX Finder API` to see the information of a `FiveM` server, and information of the IP of it. This API is accessible from any type of platform or application since you only have to make a `GET` request and you will get a` JSON` response with all the information

## Disclaimer
* This `API` is made for informational purposes and viewing information. **I am not responsible for the misuse that may be given to this tool.**

## How to get it?
1. Contact with me via Discord: `alejandromume#0884`
2. Open a ticket at my Discord server: [https://discord.gg/jtqfCkWzqg](https://discord.gg/jtqfCkWzqg)

## Real examples
* You can create your own Discord `CFX finder bot` with this `API`. You just will need to do a request. Here is an example:

```js
const  fetch  =  require('node-fetch');

fetch('API_URL')
 .then(res  =>  res.json())
 .then(json  =>  console.log(json));
```

## Next updates
* Web panel for viewing the info easily
* Faster loading times
