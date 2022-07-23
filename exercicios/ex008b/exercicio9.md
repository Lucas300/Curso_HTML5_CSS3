# Outras formatações
## Código fonte/pré formatção
* com  comando ``` <code></code>``` você exibe uma estrutura de códigos:
* usando o ```<pre> <code></code> </pre> ``` conseguimos pre-formartar para não deixar o código em uma unica linha.
    ```
    <pre>
        <code>
            num = int(input('Digite um número'))
            if num % 2 == 0:
                print(f'O número {num} é PAR')
            else
                print(f'O numero {num} é IMPAR')
            print('fim do programa')
        </code>
    </pre>
    ```

    ## Citação simples
    * usamos a tag ``` <q></q> ``` para fazer citações simples:
    ```
    Como diria o pai de um amigo: <q>o computador é um burro muito rápido.</q>
    ```
    ## Citação longa ou bloco de citações</h2>
    * Serve para fazer uma citação como a de livros e artigos , ja vem com um espaçamento pré-definido e ainda podemos colocar o link de onde tiramos, mas é só semântico pois o usuário não acessará o link.
    ```
    Segundo Jeff Noble, no seu livro HTML para leigos:</p><blockquote cite="https://www.google.com.br/books/edition/HTML_XHTML_e_CSS_Para_Leigos/E8ZtDwAAQBAJ?hl=pt-BR&gbpv=1&dq=jeff+noble&printsec=frontcover">
        A diferença entre elementos inline e um bloco de texto é importante. Os elementos neste capítulo descrevem os blocos de texto.
    </blockquote>
    ```

    ## Abreviações
    * Usadas para quando o usuário passar o mouse mostrar o que significa a determinada sigla ou abreviação.
    * Usamos a tag ```<abbr title="HyperText Markup language">HTML</abbr> ```
    ```
    <p>Estou estudando<abbr title="HyperText Markup language">HTML</abbr>e <abbr title="Cascading Style Sheets">CSS</abbr>.Estou adorando!</p>
    ```
    ## Texto Invertido
    * Usamos a tag ```<bdo dir="rtl ou ltr">``` para inverter a frase
    ```
    <bdo dir="rtl">Estou aprendendo a criar coisas em HTML</bdo>
    ```
    FIcaria assim: <bdo dir="rtl">Estou aprendendo a criar coisas em HTML</bdo>