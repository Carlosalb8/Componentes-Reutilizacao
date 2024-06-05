# Formulário de Cadastro

Este repositório contém o código HTML para um formulário de cadastro. Ele inclui campos para email, senha, e confirmação de senha, além de um botão para enviar o cadastro. O formulário utiliza o Bootstrap para estilização e responsividade.



### HTML

```html
<!doctype html>
<html lang="pt-br">
  <head>
    
    <title>Cadastro</title>

  </head>
  <body>

    <section class="section6 d-flex">
      <div class="container">
          <div class="row">
              <div class="col-12 mt-5">
                  <h4>Criar um perfil</h4>
                  <div class="form-floating">
                    <label for="floatingInput">Endereço de email</label>
                    <input type="email" class="form-control custom-width" id="floatingInput" placeholder="abc@exemplo.com">
                  </div>
                  <div class="form-floating">
                    <label for="floatingInput">Senha</label>
                    <input type="password" class="form-control" id="floatingInput">
                  </div>
                  <div class="form-floating">
                    <label for="floatingInput">Confirmar Senha</label>
                    <input type="password" class="form-control" id="floatingInput">
                    <p id="pcad">Ao selecionar “Cadastre-se agora”, você concorda com a <a href="politica.html">Política de privacidade</a> e o <a href="contrato.html">Contrato de Usuário</a> da BrasilCash e em receber comunicações de acordo com o <a href="divulgacao.html">Aviso de divulgação e consentimento de assinatura eletrônica.</a></p>
                  </div>
                  <button class="btn btn-primary w-50 mt-2">Cadastre-se agora</button><br>
                  Já tem um perfil? <a href="login.html">Entrar</a>
              </div>
          </div>
      </div>
    </section>


  </body>
</html>

Estilo css

.section6 .form-floating input.form-control {
  width: 550px;
}
