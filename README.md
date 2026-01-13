# 📐 Gabarito - Estrutura Bootstrap

![Status](https://img.shields.io/badge/Status-Estável-green)
![Bootstrap](https://img.shields.io/badge/Framework-Bootstrap_5-purple?logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/Code-HTML5-orange?logo=html5&logoColor=white)

> Um ponto de partida (Starter Template) robusto para o desenvolvimento de interfaces responsivas, contendo a arquitetura de arquivos e configurações iniciais pré-definidas.

## 🎯 Motivação e Propósito

Iniciar um projeto web do zero exige configurações repetitivas: criar pastas, arquivos, vincular folhas de estilo, adicionar meta tags de viewport e importar scripts.

O propósito deste repositório é servir como um **Gabarito de Arquitetura**. Ele resolve o problema da "página em branco", fornecendo um ambiente pronto para codar, garantindo que o Bootstrap esteja carregando corretamente e que a organização de pastas siga as boas práticas de desenvolvimento.

## 🛠️ Tecnologias Utilizadas

A base deste template utiliza a stack padrão para prototipagem rápida:

* **[Bootstrap 5](https://getbootstrap.com/):** Framework CSS integrado (via CDN ou Local) para grid system e componentes.
* **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Estrutura semântica com Meta Tags de responsividade configuradas.
* **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Arquivo de estilos customizados (`main.css`) já vinculado e pronto para sobrescrever o framework.

## 📂 Estrutura de Arquivos

A organização segue um padrão lógico de separação de ativos:

```text
gabarito_estrutura_bootstrap/
├── index.html       # Ponto de entrada com todo o setup do <head> e <body>
├── main.css         # Estilização customizada do projeto
├── images/          # Diretório reservado para ativos de imagem
└── README.md        # Documentação
