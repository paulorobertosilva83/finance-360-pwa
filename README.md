FINANCE 360 --- Gestão Financeira Inteligente

Aplicativo local-first em HTML, preparado para instalação como
Progressive Web App (PWA).





Versão: RC0.4.0 PWA



Situação: arquivos enviados ao repositório; publicação pelo
GitHub Pages e testes de instalação ainda pendentes.

Módulos





Gestão financeira: visão geral, entradas, saídas e contas, clientes
e relatórios.



Inteligência: consulta cambial e simulador de compra de dólares.



Agenda produtiva.



FINANCE INVEST V1 Enxuta: simulador local de juros compostos e
aportes mensais.



Operação: agendamento de serviços.



Sistema: configurações, backup e restauração.

Recursos externos, como cotação cambial online e Pesquisa Google,
dependem de conexão com a internet.

Arquivos do PWA





index.html --- aplicativo.



manifest.webmanifest --- identificação e parâmetros de instalação.



sw.js --- Service Worker e cache do aplicativo para abertura
offline.



icons/ --- ícones do aplicativo.



LEIA-ME-PWA.txt --- instruções de publicação e instalação.

Publicação com GitHub Pages





Mantenha index.html, manifest.webmanifest, sw.js, .nojekyll

e a pasta icons/ na raiz do repositório.



Abra Settings → Pages.



Em Build and deployment, selecione Deploy from a branch.



Selecione a branch main e a pasta /(root).



Salve e aguarde a publicação.



Abra o endereço HTTPS publicado no navegador do dispositivo.

A instalação PWA e o Service Worker exigem HTTPS (ou localhost para
desenvolvimento). Abrir o HTML diretamente por file:// não habilita
esses recursos.

Instalação

Android

Abra o endereço HTTPS no Chrome ou navegador compatível e use Instalar
app ou Adicionar à tela inicial.

iPhone e iPad

Abra o endereço HTTPS no Safari, toque em Compartilhar e selecione
Adicionar à Tela de Início.

Armazenamento e limitações





Os dados são armazenados localmente no navegador/dispositivo.



Celular e tablet não compartilham dados automaticamente. Use backup
e restauração para transferi-los.



O modo offline cobre o aplicativo e os recursos locais previamente
armazenados em cache.



Consulta de dólar e Pesquisa Google dependem de internet.



O armazenamento local e os arquivos de backup não possuem
criptografia própria nesta versão.



Esta versão não possui autenticação multiusuário ou sincronização
central.



Antes de utilizar dados pessoais reais de clientes em contexto
comercial, implemente e valide controles de acesso, proteção dos
dispositivos, política de retenção e procedimentos de backup
compatíveis com a LGPD.

Escopo e homologação

Este repositório contém uma versão candidata local-first. A publicação
no GitHub Pages não representa, por si só, homologação comercial ou
liberação para produção. Realize testes funcionais no Chrome/Android e
Safari/iOS, incluindo instalação, abertura offline, persistência local e
backup/restauração.

Licença

Nenhuma licença de uso ou redistribuição foi definida neste repositório.
