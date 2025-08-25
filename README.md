# LilyClean - Website Institucional

Este é o repositório do site institucional para a LilyClean, uma empresa de serviços de limpeza residencial e comercial. O site foi desenvolvido para apresentar a empresa, seus serviços, depoimentos de clientes e fornecer um canal de contato direto.

## 📋 Índice

  * [Sobre o Projeto]
  * [Funcionalidades]
  * [Tecnologias Utilizadas]
  * [Estrutura do Projeto]
  * [Como Executar]
  * [Contato]

## Sobre o Projeto

O projeto LilyClean foi criado a partir de um design em PDF com o objetivo de ser um site de página única (*one-page*), responsivo e moderno. Ele serve como o principal ponto de presença online da empresa, detalhando sua proposta de valor "Your Home, Our Care".

-----

## ✨ Funcionalidades

O site possui as seguintes seções:

  * **Header Fixo:** Com logo e navegação para as diferentes seções da página.
  * **Seção Hero:** Uma apresentação de impacto com o slogan da empresa.
  * **Boas-vindas:** Breve introdução sobre a empresa.
  * **Depoimentos (Reviews):** Prova social com avaliações de clientes satisfeitos.
  * **Nossos Serviços:** Uma grade visual que exibe os principais serviços oferecidos.
  * **Sobre Nós:** Um texto mais detalhado sobre a missão e os valores da LilyClean.
  * **Formulário de Contato:** Permite que visitantes enviem mensagens diretamente para a empresa. O formulário captura nome, e-mail e a mensagem.
  * **Rodapé:** Com informações de direitos autorais.

-----

## 🚀 Tecnologias Utilizadas

### Front-End

  * **HTML5:** Para a estruturação semântica do conteúdo.
  * **CSS3:** Para a estilização, layout e responsividade.
      * *Nenhum framework CSS (como Bootstrap ou Tailwind) foi utilizado, o estilo é puro.*

### Back-End (Formulário de Contato)

O formulário de contato (`<form>`) foi projetado para enviar os dados para um script no lado do servidor. A implementação do back-end pode ser feita com:

  * **Python:** Utilizando um micro-framework como Flask ou Django para processar a requisição e enviar o e-mail com bibliotecas como `smtplib`.

-----

## 📂 Estrutura do Projeto

A estrutura de arquivos e pastas recomendada para o projeto é a seguinte:

```
lilyclean-website/
│
├── index.html          # Arquivo principal da estrutura do site
├── styles.css          # Folha de estilos principal
├── README.md           # Este arquivo
│
├── images/             # Pasta para armazenar todas as imagens
│   ├── logo.png
│   ├── hero-background.jpg
│   ├── review-amanda.jpg
│   └── ...
│
└── enviar-email.php    # (Opcional) Script de back-end para o formulário
```

-----

## 🔧 Como Executar

### Front-End

Como este é um site estático, não há necessidade de instalação de dependências.

1.  Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/lilyclean-website.git
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd lilyclean-website
    ```
3.  Abra o arquivo `index.html` diretamente no seu navegador de preferência.

### Back-End (Para o formulário funcionar)

Para que o envio de e-mail do formulário de contato funcione, é necessário um ambiente de servidor.

  * **Se usar Python:** Você precisará ter o Python instalado e executar o script do servidor web (ex: `python app.py`).
  * **Se usar um serviço de terceiro:** Apenas certifique-se de que o atributo `action` da tag `<form>` em `index.html` aponta para a URL fornecida pelo serviço.

-----

## 📫 Contato

**[Diogo Teodoro Lamas]**

  * GitHub: `https://github.com/TheTekig`
  * Email: `Diogo.Teodoro015@gmail.com`
