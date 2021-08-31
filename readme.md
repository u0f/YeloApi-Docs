# YeloApi Wrapper 

YeloApi is a Multipurpose API to some awesome functions! 

## Installation

Use the package manager [npm](https://nodejs.org/) to install foobar.

```bash
npm i yeloapi
```
## Usage example
- Without requirements:
```js
const YeloApi = require("./lib/index.js");

(async () => {
    const x = await YeloApi.ping()

    console.log(x) // { status: 200, ping: '50ms', testMSG: 'Api Alive at August 31st 2021, 9:29:57 am' }
})();


```
- With requirements: 
```js
const YeloApi = require("yeloapi");
(async () => {
    const x = await YeloApi.genpass(12)

    console.log(x) //Return { pass: 'y5wJcGOVe¿mn' }
})();
```

**Important** __await is necessary always in both cases__
## Endpoints

| Endpoints | Explication |
| ------ | ------ |
| status | This enpoint allows you to see API status |
| endpoints | This endpoint allows you to get endpoints array |
| rcolor | This endpoint allows you to get random hex color! |
| r8ball | This endpoint allows you to get random 8ball response |
| encrypt | This endpoint allows you to encrypt a String |
| decrypt | This endpoint allows you to decrpyt String generated from encrypt endpoint. |
| ping | This endpoint allows you to get API ping in ms | 
| ytthumbnail | This endpoint allows you to get the thumbnail from youtube video in different resolutions |
| genpass | This endpoint allows you to get random password/string with custom length |
| nhentai | This endpoint allows you to get doujin information from nhentai.to |

**More information in** [docs](https://docs.yeloapi.ga)

## License
[MIT](https://choosealicense.com/licenses/mit/)
