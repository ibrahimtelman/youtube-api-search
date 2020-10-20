# youtube-api-search

[![npm](https://img.shields.io/npm/v/youtube-api-search)](https://www.npmjs.com/package/youtube-api-search)
[![npm bundle size](https://img.shields.io/bundlephobia/min/youtube-api-search?label=code-size)](https://github.com/ibrahimtelman/youtube-api-search) 
[![npm](https://img.shields.io/npm/dt/youtube-api-search)](https://github.com/ibrahimtelman/youtube-api-search) 
[![GitHub](https://img.shields.io/github/license/ibrahimtelman/youtube-api-search)](https://github.com/ibrahimtelman/youtube-api-search) 

### Usage
```js
  var search = require("youtube-api-search");
  
  var opts = {
    key: '',
    q: '',
    maxResults: 10
  };
  
  search(opts, (data)=>{})
```

### Default Options
```js

  var opts = {
    part: 'snippet',
    key: '',
    q: '',
    type: 'video',
    maxResults: 10,
    order: "relevance",
    pageToken: "",
    videoDuraation: ""
  }

```
