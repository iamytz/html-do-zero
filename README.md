# ESTUDANDO FRONT END
## HTML -> Hyper Text Markup Language.

.html cria a estrutura da web, imagens, textos etc.

html trabalham com tags <> e </>

abertura de tag
````html
<title>
Conteudo
</title>
````
alguns exemplos de tags -> listas
````html
<ul>
    <li>Arroz</li>
    <li>Feijão</li>
    <li>Maçã</li>
</ul>
````

---
## Primeiro passo

````html
<!DOCTYPE html> 
````

## Depois cria o copo do site

````html
<html>
    <head>
        <title> Quiz Para Programadores </title>
    </head>

    <body>
    </body>
</html>
````

## Então adicionamos metadados ao site

````html
<html>
    <head>
        <title> Quiz Para Programadores </title>
        <meta name="description" content="Quiz interativo para testar conhecimentos">
    </head>
    <body>
    </body>
</html>
````

## Padrão de sites
1. Cabeçalho
2. Conteudo Principal
3. Rodapé

````html
<html>
    <head>
        <title>Quiz para programadores</title>
        <meta charset="UTF-8" name ="description" content="Quiz para programadores">
    </head>
    <body>
        <header>
            <h1>Quiz Interativo para Programadores</h1>
        </header>
            <main></main>
            <footer></footer>
    </body>
</html>
````
## Adicionando um Paragrafo
````html
<html>
    <head>
        <title>Quiz para programadores</title>
        <meta charset="UTF-8" name ="description" content="Quiz para programadores">
    </head>
    <body>
        <header>
            <h1>Quiz Interativo para Programadores</h1>
            <p>Teste Seus Conhecimentos em programação e veja qual pontuação você consegue fazer!</p>
        </header>
        <main>
            
        </main>
        <footer></footer>
    </body>
</html>
````

## Tags -> Section 
tag semantica para dividir o conteudo em seções

````html
<html>
    <head>
        <title>Quiz para programadores</title>
        <meta charset="UTF-8" name ="description" content="Quiz para programadores">
    </head>
    <body>
        <header>
            <h1>Quiz Interativo para Programadores</h1>
            <p>Teste Seus Conhecimentos em programação e veja qual pontuação você consegue fazer!</p>
        </header>
        <main>
            <section>
                <h2>Sobre esse quiz</h2>
                <p>Este quiz foi desenvolvido com o objetivo de testar os conhecimentos de programação dos participantes. Ele abrange diversas linguagens e conceitos fundamentais, proporcionando uma experiência educativa e divertida.</p>
                <p>Ao final do quiz, você receberá uma pontuação baseada em suas respostas
            </section>
        </main>
        <footer></footer>
    </body>
</html>
````
## para destacar texto, se utiliza

````html
                <p><strong> Este quiz</strong> foi <em>desenvolvido com o objetivo</em>  de testar os conhecimentos de programação dos participantes. Ele abrange diversas linguagens e conceitos fundamentais, proporcionando uma experiência educativa e divertida.</p>

````

## quebra de linha

````html
                <p><strong> Este quiz</strong> foi <em>desenvolvido com o objetivo</em>  de testar os conhecimentos de programação dos participantes. <br> Ele abrange diversas linguagens e conceitos fundamentais, proporcionando uma experiência educativa e divertida.</p>


````

## utilizando abreviações

````html
                <p>Ao final do quiz, você receberá uma pontuação baseada em suas respostas, permitindo que você avalie seu nível de conhecimento em <abbr title="Hyper Text Markup Language"><strong>HTML</strong></abbr> e <abbr title="Cascading Style Sheets"><strong>CSS</strong></abbr> e identifique áreas para aprimoramento.</p>


````

## ADicionando Entradas de Informações 










