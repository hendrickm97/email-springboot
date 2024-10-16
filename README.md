<h1 align="center" style="font-weight: bold;">Email Spring Boot 💻</h1>

<p align="center">
    <b>Este projeto é uma aplicação Spring Boot que utiliza as funcionalidades do Spring Web para criar uma API RESTful e do Spring Email para enviar e-mails de forma confiável. A aplicação é projetada para ser altamente customizável, permitindo a configuração de templates de e-mail, credenciais de SMTP e destinatários.</b>
</p>

<h2 id="technologies">💻 Tecnologias</h2>

- Spring Boot
- Spring Web
- Srping Email

<h2 id="started">🚀 Iniciando o projeto</h2>


<h3>Pré Requisitos</h3>
- [Java](https://github.com/)
- [Criar uma conta no mailtrap](https://mailtrap.io/signin)

<h3>Clonando</h3>
```bash
git clone https://github.com/hendrickm97/email-springboot.git
```
<h3>Iniciando</h3>
- Construindo o Projeto:

```bash
.mvnw clean package

```

- Executando Projeto:

```bash
java -jar ./target/email-springboot-0.0.1-SNAPSHOT.jar

```
<h2 id="routes">📍 API Endpoints</h2>

Aqui iremos enviar através do método POST o corpo do nosso email. A api deve retorna um http 200 após o envio do email, e podemos ver o email no console do mailtrap.
​

<h3 id="post-auth-detail">POST /email</h3>

**REQUEST**

```json

  {
    "to": "hendrick@email.com",
    "subject": "Demo Spring Boot Email",
    "body": "Its working!"
}

```

