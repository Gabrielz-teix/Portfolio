## ReadME 

. Olá, muito prazer, meu nome é Gabriel e esse é meu portfólio pessoal! Aqui nesse ReadME vou falar sobre:
Visão geral do projeto e suas motivações.
Tecnologias usadas e versões recomendadas.
Instruções de instalação (dependências, comandos de build e
execução).
Guia de deploy (hospedagem, variáveis de ambiente, CI/CD).


## Visão geral do projeto e suas motivações 
. Esse foi meu primeiro site de portfólio então creio que há muito o que aprender, mas foi
um bom início principalmente na introdução de novas linguagens e no uso de novas tecnologias
como a de deploy e a de repositório Git. Sendo assim, minhas expectativa de aprender mais
se concretizou e digo motivado a adquirir mais conhecimento com novos projetos.

## Tecnologias usadas e versões recomendadas. 
. A linguagem principal escolhida foi HTML e o CSS, mas com um pequeno uso de JS:
. HTML = <doctype html>, <meta charset>, elementos semânticos (<header>, <main>, <section>, <footer>, <article>).
    Versão recomendada: HTML Living Standard.
.CSS = Arquivo style.css puro, com pequeno uso de JSS para responsivos
    Versão recomendada: CSS Level 3 com suporte a Grid e Flexbox.
.JS = Pequeno script em menu.js para abrir/fechar menu mobile.
    Versão recomendada: ECMAScript 2015 (ES6) ou superior (até ES2022).

. Além disso, há mais tecnologias aplicadas nas fontes, icones, deploy e formulário:
. Google fonts = Uso das fontes Montserrat, Poppins, Roboto via <link> com display=swap.
.Bootstrap icons = CDN do Bootstrap Icons v1.12.1.
. Netlify = para o deploy e formulário.
. Git = Ferramenta de desenvolvimento local

## Instruções de instalação. 
1.Pré-requisitos:

Git instalado.
Node.js & npm.
Editor de código(VS code por exemplo).

2.Clonar o repositório:
No terminal, execute:
git clone https://github.com/Gabrielz-teix/Portfolio.git
cd Portfolio

3.Rodar localmente:
Você pode abrir no navegador...
Basta dar duplo-clique em index.html ou seguir a linha de comando:
open index.html    # macOS
start index.html   # Windows

Ou rodar com o live-server clicando com o botão direito no index.html e selecionando:
Open with Live-server

## Guia de deploy 
. Usei a Netlify, uma plataforma para sites estáticos, além disso há um 
Deploy contínuo via Git.
. Escolhi a Netlify pelo uso dos forms e pela facilidade de deploy ao
linkar meu Git com o site, agora toda atualização feita via Git cai no
site da Netlify, sem precisar subir de novo.
. Para fazer o deploy basta seguir os comandos:
git status
git add .
git commit -m "alteração feita"
git push