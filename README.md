# Ignews 💻🚀

&nbsp;

![mock1](https://user-images.githubusercontent.com/71772559/113495090-3e529600-94c5-11eb-953c-53ab4f71fc15.png)

## 📚 Informações sobre o projeto

* Esse projeto foi desenvolvido durante um dos capitulos do Ignite da Rocketseat! A ideia era desenvolver do um blog pago onde o usuário loga usando o GitHub e paga sua inscrição usando o Stripe. Usuários que não possuem a inscrição, só conseguem ver alguns parágrafos iniciais do post, orefecendo a inscrição logo abaixo.

&nbsp;

## 💻 O que tem no projeto?

* Integração com o Prismic CMS, para trabalhar com toda a parte do sistema do blog.
* Integração com o Stripe para a parte dos pagamentos das inscrições.
* Integração com o NextAuth para a parte do login com o Github.
* Sistema de verificação de assinatura, o conteúdo exibido varia entre usuários com/sem assinatura paga.
* Dados são salvos no bando do FaunDb.
* Uso do sistema estático do Next.js, onde os posts são mantidos no cache para um melhor carregamento.

&nbsp;


&nbsp;

## 🛠️ Tecnologias/Ferramentas ultilizadas

* [React](https://pt-br.reactjs.org/E)
* [Next.js](https://nextjs.org/)
* [NextAuth](https://next-auth.js.org/)
* [Prismic CMS](https://prismic.io/)
* [Stripe](https://stripe.com/en-br)
* [Fauna](https://fauna.com/)

&nbsp;


&nbsp;

## ⚙️ Instalação
```
# Abra um terminal e copie este repositório com o comando
$ git clone https://github.com/hrkoliveira/ignews.git
```

```
# Acesse a pasta da aplicação
$ cd ignews

# Crie um arquivo .env.local e coloque as variaveis
# de ambiente baseado no arquivo .env.example que
# se encontra na pasta moveit

# Instale as dependências
$ yarn

# Inicie a aplicação
$ yarn start

```

&nbsp;



---

<p align="center">Feito com 💙 por Herik Oliveira</p>

