# Profile card

#### Profile card é um desafio do Frontend Mentor feito com HTML e CSS. Esse projeto, apresar de ser uma landing page, traz elementos bem interessantes nessas linguagens. Obrigado por chegar até aqui. Confira o código.

## Índice

- [Captura de tela](#captura-de-tela)
- [Links](#links)
- [Construído com](#construído-com)
- [O que aprendi](#o-que-aprendi)
- [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Recursos úteis](#recursos-úteis)
- [Fernando Mendes](#autor)

### Captura de tela

#### Tela Desktop

<img src="./images/desktop.png" alt="Tela desktop exibindo funcionalidades">

#### Tela Ipad

<img src="./images/ipad.png" alt="Tela tablet exibindo funcionalidades">

#### Tela Mobile

<img src="./images/mobile.png" alt="Exibindo responsividade no mobile">

### Links

- Site URL: https://nandosti.github.io/profile-card/

### Construído com

<div style="display: inline_block"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">       
</div>

### O que aprendi

Nesse projeto envolvendo HTML e CSS, aprendi conceitos importantes. Através do CSS, aprendi a dar estilo e formatar elementos HTML, explorando propriedades como cores, fontes, posicionamento,animações, responsividade, pseudo classes e pseudo elemento. No processo de aprendizado, foi importante entender os conceitos fundamentais de cada linguagem. Praticar esses conceitos em projetos reais nos ajuda a aprimorar nossas habilidades e explorar diferentes técnicas e soluções para os desafios que encontramos.

## Trechos de códigos

```
.container{
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container .wrapper{
    text-align: center;
    max-width: 420px;
    background-color: #fff;
    border-radius: 12px;
    overflow: hidden;
    margin: 1rem;
}


.container .wrapper .content img{
    width: 100px;
    height: 100px;
    border-radius: 50%;
    border: 4px solid #fff;
    margin-top: -50px;
    margin-bottom: 20px;
}

```

### Desenvolvimento contínuo

Pretendo continuar focado em construir um conhecimento sólido nessas limguagens. Ainda há muitos conceitos importantes para serem desenvolvidos. Todos os dias são gradativamente adicionados ao meu repertório de ferramentas.

### Recursos úteis

- [W3School](https://www.w3schools.com/css/default.asp) - Esse site sempre me ajuda a resolver qualquer problema relacionados a códigos de uma maneira fácil e muito rápida.
- [Dev em Dobro](https://www.youtube.com/@DevemDobro) - Este é um canal onde encontro muito material. Tem muito conteúdo relacionado ao desenvolvimento. Recomendo a todos que querem aprender sobre esse e outros conceitos relacionados.

## Autor

[Fernando Mendes](https://www.linkedin.com/in/fernandomendesti/)
@media(max-width: 425px){

    .container .wrapper .main img{
        width: 100%;
    }
    .container .wrapper .main{
        flex-direction: column;
        text-align: center;
    }

    .container .wrapper .main .hero-text h1{
        font-size: 26px;
    }

    .container .wrapper .social{
        text-align: center;
        margin-top: 50px;
    }

    .container .wrapper .main .hero-text a{
        padding: 10px 70px;
    }

}
