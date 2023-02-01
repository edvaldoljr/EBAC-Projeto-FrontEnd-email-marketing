# **Projeto Email Marketing**

Esta é uma aplicação de e-mail marketing. A ideia é usar o e-mail como uma forma de promover sua empresa ou produto e estabelecer uma conexão com seus clientes ou potenciais clientes. A mensagem é formatada como uma tabela HTML e inclui um cabeçalho, uma imagem de destaque, um título, um corpo de texto e um botão que leva o destinatário ao site da empresa. A mensagem também inclui um rodapé com informações adicionais sobre a empresa.

## Para desenvolver uma aplicação de e-mail marketing, você precisará:

- Conhecimento de HTML: você precisará criar a estrutura e o layout da mensagem de e-mail usando HTML.

# **Desenvolvimento**

## index.html

Este código é uma página HTML que tem como objetivo ser utilizada como email marketing para uma empresa.

O cabeçalho da página inclui uma meta tag "X-UA-Compatible" que especifica a compatibilidade com o Internet Explorer, uma meta tag "viewport" que especifica a largura da página para dispositivos móveis, e uma tag "title" que define o título da página.

A tag "body" define o corpo da página HTML. Nela, é definido o estilo da fonte como "sans-serif".

O código utiliza uma tabela para organizar o conteúdo. A primeira linha da tabela inclui uma imagem que serve como cabeçalho da página. A segunda linha da tabela é centrada e inclui uma imagem de um notebook, um título em azul e um parágrafo de texto que descreve a empresa. A terceira linha da tabela é um rodapé que inclui um link para o site da empresa.

Ao clicar no botão "Conhecer sobre", o usuário é redirecionado para o site da empresa.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>email marketing</title>
    <style type="text/css">
        body {
            font-family: sans-serif;
        }
    </style>
</head>
<body>
    <table width="100%">
        <tr>
            <td>
                <img src="./img/cabecalho.png" alt="Cabeçalho" width="100%">
            </td>
        </tr>
        <tr align="center">
            <td >
                <img src="./img/imagem.png" alt="Imagem Notbook" width="100%">
                <h1 style="color: #5F3AA2;">Invação para transformar</h1>
                <p >Além de comunicação, estrategia e planejamento, operamos toos os processos buscando pela excelência e otimização de recursos, seja por meio da inovação de nossa plataforma ou de parcerias estratégicas.</p>
                <a href="https://vasto.com.br" target="_blank">
                    <img src="./img/botao.png" alt="Botão Conhecer sobre"/>
                </a>
            </td>
        </tr>
        <tfoot colspan="3" align="center">
            <tr>
                <td colspan="3">
                    <p>Para mais informações acesse:
                        <a href="https://vasto.com.br" target="_blank">vasto.com.br</a>
                    </p> 
                </td>
            </tr>
        </tfoot>
    </table>
</body>
</html>
```

## Hospedagem

Estamos hospedando nosso projeto no GitPages, uma plataforma de hospedagem gratuita para projetos baseados em Git. Com GitPages, podemos compartilhar nosso trabalho com o mundo e de forma fácil e rápida. Além disso, a integração com o GitHub torna ainda mais simples o processo de desenvolvimento, teste e implantação de nossas aplicações.

## Acesso o Link e confira:
https://edvaldoljr.github.io/Projeto-FrontEnd-email-marketing/

![](https://github.com/edvaldoljr/EBAC-Projeto-HTML-Basico/blob/main/img/HTML-BASICO-EBAC.gif?raw=true)

# ⭐️ **Deixe um Star** ⭐️

Obrigado por conferir meu repository! É muito gratificante saber que alguém está interessado no meu trabalho. Se você gostou do que viu, deixar um star seria uma grande ajuda no meu crescimento e me motivaria a continuar fazendo projetos. O apoio de pessoas como você é fundamental para que eu possa seguir evoluindo e produzindo conteúdos cada vez melhores. Obrigado mais uma vez e espero que você possa acompanhar meus futuros projetos!
