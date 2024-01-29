# clone_disneyplus
**Comandos**

link do repositorio:

[Aqui](https://github.com/ogiansouza/clone_disneyplus/blob/main/index.html)

```
npm init -y

npm install --save-dev sass

npm install --save-dev gulp gulp-sass

npm install --save-dev gulp-imagemin@7.1.0

npm i --save-dev gulp-uglify

```

**Introdução**

Para importar fontes externas utilize:

```
@font-face {     
    font-family: nome da fonte;      
    src: url (caminho até o arquivo da fonte);      
    font-weight: variação onde a fonte será válida;
     }

```

**Letter-spacing**

Com a propriedade letter-spacing, podemos aplicar um espaçamento entre as letras de um texto, exemplo:

```
h1 {     
    letter-spacing: 2px; 
    }

```

**Repeat**

A função repeat serve para criar o sistema de grid. Com ela podemos escrever um código menos verboso. Exemplo: 

```
// sem repeat 
grid-template-columns: 1fr 1fr 1fr 1fr 1fr; 
// com repeat 
grid-template-columns: repeat(5, 1fr)

```

**Pseudo-elementos**

Existem alguns elementos que são inseridos automaticamente pelo navegador, são eles:

**::after:** insere algo depois do elemento;
**::before:** insere algo antes do elemento;
**::first-letter:** selecione a primeira letra de um texto;
**::first-line:** seleciona a primeira linha de um texto;
**::marker:** seleciona o bullet de uma lista;
**::selection:** seleciona a seleção do usuário.

**Overflow**

Esta propriedade define o que deve acontecer caso o conteúdo de um container escape dele, não respeite os limites de dimensão definidos. Ela considera um plano cartesiano, eixo X e Y, isso é, horizontal (X) e vertical (Y). A partir disso, consideremos que uma página possui rolagem na horizontal, estamos falando da propriedade overflow-x, e na vertical overflow-y. A propriedade overflow, sem mencionar o eixo será aplicada para ambos casos.

Os principais valores para a propriedade de overflow são:

**visible:** irá exibir o conteúdo que extrapolou o container;
**scroll:** irá gerar uma rolagem no container, a barra de rolagem irá existir mesmo que o conteúdo caiba no container;
**auto:**  parecido com scroll, porém só irá exibir a rolagem se necessário, se o conteúdo extrapolar o container;
**hidden:** ocultará o conteúdo que extrapolou o container.