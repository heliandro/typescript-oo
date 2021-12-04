# Typescript - Orientação a objetos

Estudo de orientação a objetos utilizando o Typescript (superset do JavaScript).

## Requisitos

* NVM
* Nodejs v14
* Typescript v4 - Transpila os arquivos em Typescript para JavaScript
* (lib) Nodemon - Um watch para observar e rodar os arquivos modificados
* (lib) Concurrently - permite rodar 2 ou mais scripts ao mesmo tempo

## Configuração do compilador TS

Os arquivos "**.ts**" são transpilados para "**.js**" e salvos na pasta **dist**
O tipo de modulo usado é o CommonJS, adotado pelo Nodejs.

```json
{
    "compilerOptions": {
        "outDir": "./dist",
        "target": "ES6",
        "module": "CommonJS"
    },
    "include": ["./src/**/*"]
}
```

## Tópicops abordados de OO

* Herança
* Encapsulamento
* Membros estaticos
* Interfaces
* Composição

## Topicos extras

* Tratamento de erros
* Testes unitários

## Organização

Os topicos abordados estão comitados em suas respectivas branchs.
Por exemplo, para o tópico de `Composição` temos uma branch chamada `feature/composicao` e assim sucessivamente.

## Rodando o código

para rodar o código é muito simples, execute:

```sh
npm run start
```