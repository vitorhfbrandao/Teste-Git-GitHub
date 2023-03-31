# Títulos
# Título 1 -  Basta usar "# + espaço + Palavra"
## Título 2 -  Basta usar "## + espaço + Palavra"
### Título 3 -  Basta usar "### + espaço + Palavra"
#### Título 4 -  Basta usar "#### + espaço + Palavra"
##### Título 5 -  Basta usar "##### + espaço + Palavra"
###### Título 6 -  Basta usar "###### + espaço + Palavra"

# Palavras em negrito, itálico e riscada
**Negrito** - Basta usar "** no ínicio da palavra e no final"

__Negrito__ - Basta usar "__ no ínicio da palavra e no final"

*Itálico* - Basta usar "* no ínicio da palavra e no final"

_Itálico_ - Basta usar "_ no ínicio da palavra e no final"

~Riscado~ - Basta usar "~ no ínicio da palavra e no final"

~~Riscado~~ - Basta usar "~~ no ínicio da palavra e no final"

~_**Negrito, Itálico e Riscado**_~ - Basta usar "~_** no ínicio da palavra e no final deixar tudo ao contrário"

~__*Negrito, Itálico e Riscado*__~ - Basta usar "~__* no ínicio da palavra e no final deixa tudo ao contrário"

_**Negrito e Itálico**_ - Basta usar "_** no ínicio da palavra e no final inverter o ** para o lugar do _"

__*Negrito e Itálico*__ - Basta usar "__* no ínicio da palavra e no final inverter o * para o lugar do __"

~**Negrito e Riscado**~ - Basta usar "~** no ínicio da palavra e no final inverter o ~ para o lugar do **"

~__Negrito e Riscado__~ - Basta usar "~__ no ínicio da palavra e no final inverter o ~ para o lugar do __"

~_Itálico e Riscado_~ - Basta usar "~_ no ínicio da palavra e no final inverter o ~ para o lugar do _"

~*Itálico e Riscado*~ - Basta usar "~* no ínicio da palavra e no final inverter o ~ para o lugar do *"

# Linhas Horizontais

Para criar linhas horizontais, podemos usar três traços --- ou três asteriscos ***

Exemplo:
---
***

# Listas
### Listas Numeradas
1. Lista 1
   1. Sub Lista 1
1. Lista 2
   1. Sub Lista 2
   1. Sub Lista 2 Teste 
1. Lista 3
1. Lista 4

### Listas Demarcadas
* Lista Demarcada 1
   * Sub Lista Demarcada 1
* Lista Demarcada 2
  * Sub Lista Demarcada 2
  * Sub Lista Demarcada 2 Teste

### Listas de Tarefas
- [ ] Teste Tarefa 1
- [x] Teste Tarefa 2

# Imagens e Links

![Perfil](https://user-images.githubusercontent.com/86865137/229195618-431bc7d7-c04a-4fbf-8e5c-b5506ba016a5.png) - Use "![Nome da Imagem](URL da Imagem)"

[Acesse meu GitHub](https://github.com/oadoficial) - "Use "[Nome do Link](URL do Link)"

# Tabelas

AV | Nome | Nota
--- | --- | ---
AV1 | Vitor Brandão | 9,7
AV2 | Vitor Brandão | 9,8
AVF | Vitor Brandão | 8,5

| Média |
--- |
9,33 |

# Colocando código em Markdown

Não entendo o que significa isso: `document.getElementById()` - para ter esse efeito na palavra basta colocar o caracter "`" no inicio e no final.

Não entendi essa parte desse código:
```
<table border="0" cellpadding="0" cellspacing="0" id="signWrapper" style="border-collapse:collapse;" width="100%"><tbody><tr><td align="left" valign="top">
<table align="left" border="0" cellpadding="0" cellspacing="0" style="max-width:480px; border-collapse:collapse;" width="480"><tbody><tr><td align="left" style="padding:0px;" valign="top">
<table align="left" border="0" cellpadding="0" cellspacing="0" style="max-width:480px; width:100%; border-collapse:collapse;" width="480"><tbody><tr><td align="left" style="padding: 10px; vertical-align: middle; background-color: rgb(255, 255, 255);" valign="top" width="144">
<table align="center" border="0" cellpadding="0" cellspacing="0" style="max-width:135px; border-collapse:collapse;" width="100%"><tbody><tr><td align="center" style="font-size:14px;" valign="top">
<table border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse;" width="100%"><tbody><tr class="signRow"><td align="center" style="text-align: center;" valign="top"><img src="https://a.bybrand.io/img-64247bc226ae7.png" style="display: inline-block; vertical-align: middle; margin: 0px; float: none; max-width: 600px; text-align: center; padding: 0px; border: none; width: 120px; height: 120px;" width="120" height="120"></td></tr></tbody></table>
</td></tr></tbody></table>
</td>
<td align="left" style="padding: 10px 15px; background-color: rgb(255, 255, 255);" valign="top" width="336">
<table align="left" border="0" cellpadding="0" cellspacing="0" style="max-width: 335px; border-collapse:collapse;" width="100%"><tbody><tr><td align="left" valign="top"><strong><span style="font-family: Verdana, Geneva, sans-serif; color: rgb(75, 0, 130);">Vitor Brandão</span></strong><table border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse;" width="100%"><tbody><tr class="signRow"><td style="font-family: arial; line-height: 18px; padding: 2px 0px;"><span style="color: rgb(75, 0, 130); font-family: "Times New Roman", Times, serif, -webkit-standard;">Developer</span></td></tr>
```

Para ter esse efeito basta colocar o caracteres "```" no início e no final do código.

# Citações e Quote Reply's

Caso você queira mencionar alguém basta colocar o @ + o nome da pessoa ou equipe

Exemplo: @oadoficial

Para o reply basta colocar o sinal de maior(>) + uma mensagem (**OBS: Só funciona em Issue's e Discussões**)

Exemplo: > Está chovendo hoje??

# Adicionando Co-Autor em uma file

Em "Commit new file >>> Add an optional extended desciption..." escreva:

`Co-authored-by: nome oficial no github <name@example.com>`

Exemplo:

`Co-authored-by: oadoficial <vitorhfbrandao@gmail.com>`

Caso queira adicionar mais co-autores basta adicionar abaixo mais pessoas.

Exemplo:

`Co-authored-by: oadoficial <vitorhfbrandao@gmail.com>`

`Co-authored-by: jamelao <jamelao@gmail.com>`

# Emoji

Teste - ✋ - Basta escrever ": seguido do nome do emoji"

Teste 2 - :octocat:

[Repositório com Todos os Emojis](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

Caso queira colocar emoji no título de uma Issue, é necessário copiar de um lugar que está em formato unicode. Você pode acessar esse [conteúdo aqui!](https://emojipedia.org)
