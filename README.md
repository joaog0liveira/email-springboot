## Email Springboot
 
Este é um projeto simples que demonstra como enviar e-mails usando o Spring Boot.

## Sobre
Este projeto consiste em uma aplicação Spring Boot que permite enviar e-mails através de uma API RESTful. Ele utiliza o framework Spring para configurar e enviar e-mails de forma simplificada.

## Configuração
Para executar esta aplicação, você precisará de:

* JDK 8 ou superior instalado em seu sistema.

* Um servidor de e-mail SMTP configurado para enviar e-mails. Este projeto utiliza a biblioteca JavaMailSender do Spring para enviar e-mails, portanto, é necessário configurar as propriedades do servidor de e-mail no arquivo application.properties. (Obs: no projeto já se encontra configurado)

## Como testar
Você pode testar a funcionalidade de envio de e-mails utilizando o HTTPie, uma ferramenta de linha de comando para fazer requisições HTTP.

## Passos para testar:
Certifique-se de que a aplicação está sendo executada localmente.
Abra um terminal e execute o seguinte comando para enviar um e-mail:
``` http POST http://localhost:8080/email to="destinatario@example.com" subject="Assunto do Email" body="Corpo do Email" ```

Substitua "destinatario@example.com", "Assunto do Email" e "Corpo do Email" pelos valores desejados.

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- Nome: João Gabriel de Oliveira Meireles
- Email: joaog.meireles@outlook.com
- LinkedIn: https://www.linkedin.com/in/joaogomeireles/
