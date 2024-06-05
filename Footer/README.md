# Footer Fixo

Este é um exemplo de código HTML para criar um footer fixo na parte inferior da página.


## Exemplo de Código

```html
<!doctype html>
<html lang="pt-br">
  <head>
    <title>footer</title>

    <style>
      footer {
        text-align: center;
        background: black;
        color: white;
        padding: 23px;
        width: 100%;
        bottom: 0;
        position: fixed;
      }
    </style>

  </head>
  <body>

    <footer>
      <div class="container align-self-center">
        <div class="row">
          <div class="col-md-12">
            Todos os direitos reservados
          </div>
        </div>
      </div>
    </footer>

  </body>
</html>
