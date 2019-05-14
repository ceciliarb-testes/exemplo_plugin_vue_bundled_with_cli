# exemplo_plugin_vue_bundled_with_cli
Exemplo de plugin Vuejs empacotado utilizando o próprio `vue-cli-service`
```
vue-cli-service build --target lib --name plugin_teste_2 ./src/index.js
```

## Manutenção e melhorias do plugin
```
git clone https://github.com/ceciliarb-testes/exemplo_plugin_vue_bundled_with_cli.git
cd exemplo_plugin_vue_bundled_with_cli
npm i
npm run build-bundle
npm login
npm version [major|minor|patch]
npm publish --access publis
```

## Uso do plugin
```
npm i plugin_teste_2
```
Disponível em https://www.npmjs.com/package/plugin_teste_2

## Exemplo de uso
https://github.com/ceciliarb-testes/exemplo_app_usando_custom_plugin
