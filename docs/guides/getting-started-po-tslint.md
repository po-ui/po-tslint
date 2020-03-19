[comment]: # (@label Começando com PO TSLint)
[comment]: # (@link guides/getting-started-po-tslint)

Este conteúdo tem por finalidade auxiliar a instalação do po-tslint em seu projeto.

### Índice

- [Pré-requisitos](/guides/getting-started-po-tslint#requirements)
- [Instalando em um novo projeto](/guides/getting-started-po-tslint#steps):
  + [Passo 1 - Instalando o PO](/guides/getting-started-po-tslint#step1)
  + [Passo 2 - Instalando o po-tslint](/guides/getting-started-po-tslint#step2)
  + [Passo 3 - Configurando o arquivo tslint.json](/guides/getting-started-po-tslint#step3)
- [Instalando em um projeto já existente](/guides/getting-started-po-tslint#existente)
- [Utilizando](/guides/getting-started-po-tslint#utilizando)

<a id="requirements"></a>
### Pré-requisitos

- Conhecer:
  + [NodeJS](https://nodejs.org/en/)
  + [npm](https://www.npmjs.com/)
  + [Estrutura de aplicação Angular](https://angular.io/guide/architecture)

<a id="steps"></a>
### Instalando em um novo projeto.

<a id="step1"></a>
#### Passo 1 - Instalando o PO.

Inicialmente você deve instalar o PO seguindo o guia [Como instalar o PO](/guides/how-install).

<a id="step2"></a>
#### Passo 2 - Instalando o po-tslint

Execute o comando abaixo para que seja instalado o po-tslint:

``` shell
npm i --save-dev @po-ui/ng-tslint
```

> Com isso, as regras de lint utilizadas no PO serão instaladas e estarão disponíveis para serem usadas no projeto.

<a id="step3"></a>
#### Passo 3 - Configurando o arquivo tslint.json.

Para aplicar as regras do po-tslint você deve, após instalar o pacote, adicionar as seguintes linhas de código no arquivo `tslint.json` encontrado na raiz do seu projeto.

```
"extends": [
  "@po-ui/ng-tslint"
]
```

Seu arquivo deverá ficar parecido com este:

```
{
  "extends": [
    "@po-ui/ng-tslint"
  ],
  "rules": {
    // suas regras personalizadas.
  }
}
```

<a id="existente"></a>
### Instalando em um projeto já existente.

Para instalar em um projeto já existente basta seguir os passos a partir do [Passo 2](/guides/getting-started-po-tslint#step2).

<a id="utilizando"></a>
### Utilizando.

Você pode utilizar os seguintes comandos:

```
ng lint
```

ou 

```
npm run lint
```

Após o tempo de verificação você verá um relatório das regras que não foram seguidas ou uma mensagem:

```
All files pass linting.
```

mostrando que seu código está de acordo com as regras.