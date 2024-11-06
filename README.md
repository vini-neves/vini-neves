<div>
  
Skip to content
DEV Community
Powered by
Algolia
Log in
Create account
Andressa Santos
Andressa Santos

Posted on 23 de fev. de 2022 • Updated on 6 de mar. de 2022
23 7 1 1 1
Tutorial Fácil de Customização do Perfil do GitHub
#github
#beginners
#readme
#tutorial

Esse tutorial tem o objetivo de ajudar as pessoas a desenvolverem seus próprios perfis personalizados do GitHub, de maneira mas simplificada possível
Categorias

    Primeiros passos
        Requisitos
        Criando
        Customizando
    Link Utilizados

Requisitos

    Único requisito para prosseguir nesse tutorial é ter uma conta criada no site GitHub.

Criando

    O primeiro passo é criar seu diretório de perfil GitHub. Para isso, clique em + ap lado de sua foto de perfil e após em New Repository

Animação

    Feito isso, você colocará o nome desse novo repositório. Ele precisa ser necessariamente igual ao seu nome de perfil do GitHub. Como o meu é andressansantos foi esse que coloquei.

create-repo

Por fim, marque a opção Add a README file e por ultimo, no botão Create
Customizando Readme

Ele veem totalmente vazio ao ser criado.
Nele, você poderá colocar uma breve descrição do que você trabalha/estuda hoje.
Assim como em HTML, o Markdown como liguagem de marcação possuí os mesmos recursos que juntos com o HTML te dão maior flexibilidade.
Por isso, utilize os mesmos quando necessário sabiamente.

A primeira coisa importante é conhecer um pouco de Markdown. E para isso, você poderá acessar o link aqui para ter um tutorial mais completo.

Crie uma breve apresentação, e se quiser coloque emoticons. Poderá utilizar o site EmojiPedia para isso.
edit-perfil

Agora, utilizaremos as informações do GitStats, um repositório no GitHub para colocar as estatisticas no nosso perfil.

Comecemos colocando uma < div > e dentro dela, colocaremos a informação do tema que queremos e nosso usuario.

 <img height="180em" src="https://github-readme-stats.vercel.app/api?username=andressansantos&show_icons=true&theme=tokyonight"/>
 <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=andressansantos&layout=compact&theme=tokyonight"/>

Não esqueça de mudar no campo username para o nome do seu usuário de GitHub. Na ultima parte, de Theme ao final do código, poderá escolher o que
desejar na pagina do GitStats.

E esse será o resultado:

Adicione as redes sociais, para recrutadores ou outras pessoas queiram entrar em contato com você. Para isso, coloque o código conforme exemplo:

[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/n9KBKHPA3H)

Nesse código, a primeira parte é o nome da rede, a segunda parte o link no post do Dev.To e a terceira parte o link da sua rede. Nesse meu caso, foi da comunidade no Discord do Ehmuitodrama. Para ter acesso a todos os Badges de redes sociais, acesse ao post completo com mais de 150 Badges no Dev.to

E esse será o resultado ao acabar e colocar o link e verificando no preview.

Discord

Agora iremos para a última parte que é adicionar as tecnologias que estamos aprendendo/dominando/trabalhando. Nessa parte, utilizaremos o site Dev Icon
O código que utilizaremos sempre será o SVG

  <img align="center" alt="Andressa-html" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/>

No código passado, colocamos um nome, além de dimensões utilizando a tag img do HTML. A seguir no src, colocando a imagem do SVG

E o resultado será esse:

Andressa-html

    Veja o resultado completo de como ficará no meu perfil, clicando aqui!
    Acesse ao vídeo tutorial no Youtube

Links utilizados

A seguir, listareis todos os sites consultados para a criação de Readme.

Emoticon:

Criação de Gifs ScreenToGif:

Icones Tecnologias:

Post Dev.To de Badges:

Criador de Gif com sua foto:

Repositório do GitHub Stats:
Top comments (0)
Subscribe
pic
Code of Conduct • Report abuse
Read next
msh_sayket_6a8d9f36faac8a profile image
How to deploying Laravel projects on a live server – Complete Step-by-Step Guide

Msh Sayket - Oct 12
navv23 profile image
Complete Linux Essentials!

Navaneethan Ghanti - Nov 3
arshisaxena26 profile image
Exploring Nuances of the Java Scanner Class

Arshi Saxena - Nov 4
sertxudev profile image
Clear screen at MariaDB CLI

Sergio Peris - Oct 16
Andressa Santos
Eterna estudante tentando codar algo > Twitch LiveCoder instagram.com/andressacodes/ twitch.tv/andressacodes BLUSKY: bsky.app/andressacodes.dev YT: youtube.com/@AndressaCodes

    Location
    Brazil
    Joined
    24 de nov. de 2021

More from Andressa Santos
A Mágica do JSX no React: Por Que Usá-lo e Como Ele Funciona
#javascript #react #beginners #programming
Por que alguns desenvolvedores conseguem empregos rapidamente e outros não?
#softskill #beginners #webdev #programming

 <img height="180em" src="https://github-readme-stats.vercel.app/api?username=andressansantos&show_icons=true&theme=tokyonight"/>
 <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=andressansantos&layout=compact&theme=tokyonight"/>

Thank you to our Diamond Sponsor Neon for supporting our community.

DEV Community — A constructive and inclusive social network for software developers. With you every step of your journey.

    Home
    DEV++
    Podcasts
    Videos
    Tags
    DEV Help
    Forem Shop
    Advertise on DEV
    DEV Challenges
    DEV Showcase
    About
    Contact
    Free Postgres Database
    Guides
    Software comparisons

    Code of Conduct
    Privacy Policy
    Terms of use

Built on Forem — the open source software that powers DEV and other inclusive communities.

Made with love and Ruby on Rails. DEV Community © 2016 - 2024.

</div>
