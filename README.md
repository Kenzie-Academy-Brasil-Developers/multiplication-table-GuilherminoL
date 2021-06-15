# Entrega: Tabela de Multiplicação 

## Visão Geral

Para começar, acesse [este link](https://classroom.github.com/a/5RDmDMXi) e clone o repositório em sua máquina.


Construa uma função que recebe um parâmetro *n* do tipo inteiro que permita a geração de tabelas de diferentes tamanhos (por exemplo, 12x12, 16x16)

Escreva uma página HTML que use Javascript para desenhar uma tabela de multiplicação no console do navegador. A ideia chave aqui é usar dois loops aninhados _(um loop dentro de outro)_ para costruir um array aninhado _(bidimencional)_ que você vai utilizar para desenhar as linhas e colunas da tabela.

Imagine que você está construindo uma tabela para que professores do ensino fundamental a usem em sala de aula. Ela deve ficar mais ou menos assim, executando com o parâmetro n valendo 10:

![](https://i.snag.gy/xf0HnX.jpg)

### Início

Você pode usar o seguinte documento HTML como ponto de partida:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Multiplication Table</title>
    </head>

    <body>
        <h1>Multiplication Table</h1>
        <script>

            function nomeDaSuaFuncao(n) { // Substitua "nomeDaSuaFuncao" por um nome mais apropriado
                // escreve a coluna inicial
                let x = [];
                for (let i = 0; i <= n; i++) {
                    x[i] = [];
                }
                console.table(x)
                // TODO: escrever dois loops aninhados para desenhar o array bidimencional e monstar o restante da tabela no console.
            }
        </script>
    </body>
</html>
```

__Se você quiser entender um pouco mais sobre o [console.table()](https://developer.mozilla.org/en-US/docs/Web/API/Console/table)__ - [Link para documentação](https://developer.mozilla.org/en-US/docs/Web/API/Console/table)

## Envio

Faça o push do código para o seu repositório GitHub e implemente-o GitHub pages. No Canvas, **por favor, envie sua url do GitHub Pages (ex: https://nomedeusuario.github.io/katas2)**, deixe o projeto público e após ser feito a correção, seu projeto deverá ficar privado.
