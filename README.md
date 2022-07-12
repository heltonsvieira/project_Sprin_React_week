# project_Sprin_React_week
Projeto DevSup Semana Sprin x React - DSMeta
HTML e CSS a partir do Figma 1/2: Preparação para Semana Spring React
Principais passos:

1. Instalar Visual Basic Studio;
2. Criar/abrir nova pasta para salvar o projeto;
3. Criar um "new file" chamado "index.html"
	Obs. "index" é um nome padrão (convencionado) nos sites, para usar o padrão inicial no html
4. Faça os seguintes testes:
<html>
    <body>
        <h1> Título da página</h1>
        <p> Sejam bem vindos!</p>
    </body>
</html>

5. Crie um novo arquivo em DSMETA-CSS, chamado "styles.css" e faça os seguintes testes:
h1 {
    color: #ff0000;
}

Obs. Para as cores e seus código numéricos em html: pesquise em w3.schools.com > HTML Color Picker

Depois atualize o código em index.html, assim:
<html>
    <head>
        <link rel="stylesheet" href="styles.css" />
    </head>
    <body>
        <h1> Título da página</h1>
        <p> Sejam bem vindos!</p>

    </body>

</html>

6. Em figma.com encontre layouts para designers de aplicações. 
	Obs1. Link direto do modelo utilizado: https://www.figma.com/file/EN1zFtk4eY3Jgmpgi9YaMG/DSMeta1
	Obs2. O designer da aplicação não é tarefa do Dev, mas sim de um designer

7. Digite o exclamação (!) + enter, e deverá aparecer isso aqui:
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        
    </body>
</html>

7. Altere o nome da página html em "<title>Document</title>"
8. Visualize com botão contrário em "index.html" e depois "Open with Live Server"
9. Comece a espelhar os dados do figma (designers menores primeiro) para o seu projeto html
	Obs1: Export image (+) como "SVG".
	Obs2: O formato de arquivo SVG é uma ferramenta popular para exibir gráficos bidimensionais, 
	tabelas e ilustrações em sites. Além disso, como um arquivo vetorial, ele pode ser aumentado 
	ou reduzido sem perder resolução.
10. Adicione a imagem com a tag "img" + enter na 1ª primeira linha após o <body>
11. Altere a formatação de cor de fundo da página (backgroud-color) e fonte (color) em CSS e depois adicione no html com: link + enter. Ficará assim:
*No CSS:
body, html {
    background-color: #000;
    color: #ffffff;
}
*Faça o link no html:
<link rel="stylesheet" href="">, depois adicione "style.css" em href=.

12. Para estilo das fontes vá em Google Fonts, escolha as fontes e depois:
"link" para o html ou "@import" para usar no CSS. No CSS cole assim:
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');

*{
    font-family: 'Roboto', sans-serif;
}
body, html {
    background-color: #000;
    color: #ffffff;
}

Obs1. "*" se refere a qualquer elemento na página.

13. Inserindo link na página:
<p>Desenvolvido por Helton Vieira
        <a href="https://www.instagram.com/heltonsvieira/?hl=pt%2C">@heltonsvieira</a>
    </p>
Obs1. Para indentar use: shift + alt + f

14. Inserindo um <header> e um <div> dentro do <body> para delimitar o cabeçalho.

Obs1: "div" é uma divisão com significado. Em HTML, as tags "div" e "span" são elementos usados ​​para definir
partes de um documento, para que sejam identificáveis ​​quando uma classificação única for necessária. 
O elemento de divisão HTML <div> é um container genérico para conteúdo de fluxo, que de certa forma 
não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos (usando class
 ou id), ou porque eles compartilham valores de atributos, como lang.

Obs2: Classes são seletores CSS. Utilizaremos seletores CSS para estilizar elementos no HTML, usando o atributo
"class", por exemplo: <div class="blue"></div> em referência à uma classe CSS blue.
No CSS 'chame' o class com .nome_da_class{}

<header>
        <div class="dsmeta-logo-container">
            <img src="logo.svg" alt="DSMeta">
            <h1>DSMeta</h1>
            <p>
                Desenvolvido por Helton Vieira
                <a href="https://www.instagram.com/heltonsvieira/?hl=pt%2C">@heltonsvieira</a>
            </p>
        </div>

15. Inserindo um <main> dentro do <body>:
O elemento <main> define o conteúdo principal dentro do <body> em seu documento ou aplicação. 
