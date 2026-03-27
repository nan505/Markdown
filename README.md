# Registro C#
> Autor: Nan Santos

## Variáveis
> As variáveis são espaços de memória que tem como objetivo guardar/armazenar informações.

1. Números:
    - int
    - double
    - float
2. Textos
    - string
    - char
3. Booleanos
    - bool
4. Listas
    - Listas
    - List<>
    - int[]

## Condições
> if, switch, ternários

Condições é o *método* para **validar** se uma ***informação*** é verdadeira, caso seja _verdadeira_ a __condição__ ___aplicada___ `if` executa somente o código que está dentro dele, com isso temos condições para que o código execute somente o necessário 

```csharp
if (valor1 == valor2)
{
    MessageBox.Show("Os numeros são iguais");
}
```

[Saiba Mais sobre C#](https://learnxinyminutes.com/pt-br/csharp/)

![Imagem logo C#](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/C_Sharp_Logo_2023.svg/960px-C_Sharp_Logo_2023.svg.png)


![My Skills](https://skillicons.dev/icons?i=html,css,mysql,bootstrap,cs,javascript,vscode,visualstudio,markdown,github&perline=6)

### Estilização de texto:

**Texto em negrito** / *Em itálico* / ~~Rasurado~~ / **Negrito com _partes em itálico_** / ***Negrito e itálico*** / <sub>Texto pitico pra baixo</sub> / <sup>Texto pitico pra cima</sup> / <ins>Com underline</ins>

### Citação:

> Essa é uma citação, maneiro demais.

### Citando códigos:

Citando códigos como `MessageBox.Show("Código citado!");`

### Criando blocos de código:

```
MessageBox.Show("Esse código está em um bloco!");
```

Bloco de código com highlight de sintaxe:

``` cs
MessageBox.Show("Esse código está em um bloco com highlight de sintaxe da linguagem C#");
```

### Links e âncoras:

Essa atividade está sendo realizada com a ajuda da página [Documentos do GitHub](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax), e também a utilizei de exemplo para a criação de um link!

Caso queira voltar para o topo, [clique aqui](#registro-c)!

Os gitattributes desse repositório se encontram [aqui](.gitattributes)!

``` html
<a name="ancora-customizada"></a>
Existe uma âncora customizada em cima de mim!
```

<a name="ancora-customizada"></a>
Existe uma âncora customizada em cima de mim!

### Quebras de linha

Quebrando com dois espaços  
Linha após a quebra

Quebrando com barra\
Linha após a quebra

Quebrando com `<br/>`<br/>Linha após a quebra

Quebrando a linha com uma linha em branco

Linha após a linha em branco

### Listas e tarefas (checkbox):

1. Lista com outra lista dentro
    - Lista dentro da lista
        - Lista dentro da lista dentro da lista

- [x] Tarefa completa
- [ ] Tarefa incompleta

### Referências:

Criando referências[^1].

Essas referências podem ter mais de uma linha também[^2], muito massa!

[^1]: Se liga na referência!

[^2]: Referência com duas linhas utilizando os dois espaços  
Iradíssimo!

### Alertas:

> [!NOTE]
> Esse é um alerta de nota, geralmente contém informações que o usuário deveria saber!

> [!TIP]
> Esse é um alerta de dica, geralmente contém informações adicionais para facilitar o entendimento pelo usuário.

> [!IMPORTANT]
> Esse é um alerta importante, geralmente contém informações indispensáveis que o usuário precisa saber.

> [!WARNING]
> Esse é um alerta de aviso, geralmente contém informações para que o usuário não cometa erros.

> [!CAUTION]
> Esse é um alerta de cuidado, geralmente para avisar o usuário sobre ações que podem ser realizadas pela conta e risco do usuário.

### Ignorando a formatação do Markdown:

Era para a palavra \*sabugo\* estar em itálico, mas os caractere `\` impedem a formatação do Markdown.

## Tabelas:

| Nome do Digimon | Atributo do Digimon |
| --- | --- |
| Agumon | Vírus / Vacina |
| Gabumon | Data / Vacina / Vírus |

Formatação da tabela

| Nome do Digimon | Tipo | Atributo |
| :--- | :---: | ---: |
| Agumon | **Réptil** | `Vírus / Vacina` |
| Gabumon | **Réptil** | `Data / Vacina / Vírus` |