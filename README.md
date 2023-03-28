<div id="inicio"></div>
<h1 align="center"> 
	🚀  totp_nodejs 🚀
</h1>

> Projeto serve para o usuário fazer autenticação de 2 fatores usando um app pra gerar uma chave de acesso única.

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

* Ter o NodeJS instalado no seu computador.
* Extensão REST Client para consumir a API no VS Code.

## 🚀 Configurando totp_nodejs

Execute os seguintes comandos para gerar o DB sqlite para testar o projeto.

```
npm db:migrate
```

```
npm db:push
```

## ☕ Usando totp_nodejs

Para iniciar o projeto execute o seguinte comando: `npm start`.

Existe um arquivo com as rotas para testar o serviço no insomnia. O arquivo está na pasta raiz com o nome `rotas.json`. Mas você também pode testar as rotas usando o arquivo `rotas.http` e instalando a extensão `REST Client`.

Para adicionar a conta cadastrada no app do Google Autenticator, execute a rota Generate OTP e copie o campo `base32` que foi retornado e cole no app. Como nas imagens abaixo.

<img src="src/1.png" height="400em"> <img src="src/2.png" height="400em">

<img src="src/3.png"> 

<img src="src/4.png" height="400em">

<!-- Imagens aqui -->

Para validar o código você pode usar as rotas Validate OTP ou Verify OTP.

Você também pode desabilitar o OTP/TOTP da conta criada.

Você pode acessar a interface do prisma usando o comando `npm db:studio` e acessand a URL `http://localhost:5555/`.

## 🤝 Colaborador

Agradecemos à seguinte pessoa que contribuiu para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/erick-vasconcelos-50baa8150/" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/67069017?v=4" width="100px;" alt="Foto do Erick no GitHub"/><br>
        <sub>
          <b>Erick Vasconcelos</b>
        </sub><br>
        <a href="https://www.buymeacoffee.com/erickzaunlab" target="_blank"><img src="https://raw.githubusercontent.com/appcraftstudio/buymeacoffee/master/Images/snapshot-bmc-button.png" width="100px;"></a>
      </a>
    </td>
  </tr>
</table>


[⬆ Voltar ao topo](#inicio)<br>
