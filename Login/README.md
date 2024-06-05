# Formulário de Login

Este repositório contém o código HTML para um formulário de login. Ele inclui campos para email e senha, um checkbox para lembrar do usuário, e um botão para enviar o login.

### HTML

```html
<!doctype html>
<html lang="pt-br">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <title>Login</title>

  </head>
  <body>

    <section class="section6 d-flex">
      <div class="container">
          <div class="row">
              <div class="col-12 mt-5">
                  <h4>Login</h4>
                  <div class="form-floating">
                    <label for="floatingInput">E-mail</label>
                    <input type="email" class="form-control custom-width" id="floatingInput" placeholder="abc@exemplo.com">
                  </div>
                  <div class="form-floating">
                    <label for="floatingInput">Password</label>
                    <input type="password" class="form-control" id="floatingInput">
                  </div>
                  <div class="form-check text-start my-3">
                    <input type="checkbox" class="form-check-input" id="flexCheckdefault" />
                    <label class="form-check-label" for="flexCheckdefault">Lembrar-me</label>
                  </div>
                  <button class="btn btn-primary w-50 py-2">Entrar</button>
              </div>
          </div>
      </div>
    </section>

  </body>
</html>

estilo css

.section6 .form-floating input.form-control {
  width: 550px;
}