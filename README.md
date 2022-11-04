# Gatitobook

## Dependências usadas
- npm install --save-dev prettier
- npm install --save-dev tslint-config-prettier
- npm install --save-dev tslint-plugin-prettier
- npm i bootstrap font-awesome

- No arquivo tslint.json, coloque a seguinte configuração no atributo extends:
```
"extends": ["tslint:recommended", "tslint-plugin-prettier", "tslint-config-prettier"]
```

- *Adicionar os caminhos do bootstrap no **angular.json** para que o angular reconheça as libs*
```
"scripts": [
    "./node_modules/bootstrap/dist/CSS/bootstrap.min.CSS",
    "./node_modules/font-awesome/CSS/font-awesome.CSS"
]
```