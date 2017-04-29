Escrever isso pelo prompt: npm install connect serve-static

Crie o arquivo server.js e adicionar o seguinte código:

var connect = require('connect');
var serveStatic = require('serve-static');
connect().use(serveStatic(__dirname)).listen(8080, function(){
    console.log('Server running on 8080...');
});

Escrever no prompt: node server.js
