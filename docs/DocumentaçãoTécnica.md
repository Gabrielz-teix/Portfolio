## Documentação Técnica

- Esta seção descreve a estrutura de pastas, a organização do código e os 
principais componentes do projeto, bem como suas responsabilidades.

1. Estrutura das pastas:
Há 2 pastas dentro da nossa principal, uma para o conteúdo usado e outra para
os documentos feitos.
- Images - contém as imagens e gif usados
- Docs - documentação

2. Organização do código:
- HTML (index.html)
. Divide o conteúdo em seções semânticas: <header>, <main>, <footer>.
. Cada área do portfólio fica em <section id="...">:
. inicio (apresentação)
. especialidades (cards de habilidades)
. sobre (seção biográfica)
. portfolio (links para projetos)
. formulario (contato via Netlify Forms)
. Inclusão de fontes externas (Google Fonts) e ícones (Bootstrap Icons) via <link>

- CSS (style.css)
. Reset e base: * { margin: 0; padding: 0; box-sizing: border-box; }
. Variáveis e fontes: definição de font-family, cores e dimensões padrão.
. Layout principal: classes utilitárias:
. interface (centralização e largura máxima)
. flex (display: flex para containers)

Componentes:
. Cabeçalho: estilos de nav desktop, botões e responsividade.
. Menu Mobile: .menu-mobile, .abrir-menu, .overlay-menu.
. Seções (.topo-do-site, .especialidades, .sobre, .portfolio, .formulario): padding, tipografia, responsividade.
. Formulário: estilo de inputs, textarea e botão de envio.
. Rodapé: estilos de link e ícones.
. Animações: @keyframes flutuar aplicado à imagem principal.
. Media Queries: ajustes abaixo de 1020px para stacks verticais e dimensionamento de imagens.

- JavaScript(menu.js)
. Elementos modificados:
. btnMenu = document.getElementById('btn-menu');
. menu = document.getElementById('menu-mobile');
. overlay = document.getElementById('overlay-menu');

. controlar a interação e visibilidade do menu mobile, garantindo
responsidade.