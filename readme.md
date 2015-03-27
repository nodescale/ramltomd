#Raml to Markdown
---
A RAML to markdown converter made in modejs

###Install
```sh
$ npm install -g ralmtomd
```




###Usage
####Comand line

```sh
$ ramltomd -i path/to/filename.raml > path/to/output.md
```
#####Help

```
 Usage: ramltomd [options]

  Options:
    -h, --help          output usage information
    -V, --version       output the version number
    -i, --input [path]  path for raml file
```
####As a library

```javascript
var ramlToMd = require('ramltomd');


ramlToMd.render(path).then(function(result){
	
});
```