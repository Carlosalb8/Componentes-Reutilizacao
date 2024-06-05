# Navbar

A barra de navegação (navbar) é uma parte importante de muitos sites, fornecendo uma maneira conveniente de navegar entre diferentes páginas ou seções do site. Vamos analisar como a navbar é estruturada e como ela funciona:

## Estrutura HTML

A navbar é composta por uma série de elementos HTML, incluindo um cabeçalho (`header`) e uma navegação (`nav`) com links para diferentes páginas. Aqui está a estrutura HTML básica:

```html
<header>
  <nav class="navbar navbar-expand-lg navbar-light fixed-top navbar-transparente">
    <div class="container">
      <a href="index.html" class="nav-brand">
        <span class="branco">BRASIL</span> <span class="verde">CASH</span>
      </a>

      <button class="navbar-toggler" data-toggle="collapse" data-target="#nav-principal">
        <i class="fa-solid fa-bars text-white"></i>
      </button>

      <div class="collapse navbar-collapse" id="nav-principal">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a href="empresa.html" class="nav-link">Empresa</a>
          </li>
          <li class="nav-item">
            <a href="suporte.html" class="nav-link">Suporte</a>
          </li>
          <li class="nav-item">
            <a href="cadastrar.html" class="nav-link">Cadastrar</a>
          </li>
          <li class="nav-item">
            <button onclick="window.location.href='login.html'" type="button" class="btn btn-secondary ">Entrar</button>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</header>


Estilo css

nav.navbar-transparente {
	background: black;
	padding: 15px 0px;		
}

.navbar-light .navbar-nav .nav-link {
	color: white;
}

.navbar-light .navbar-nav .nav-link:hover {
	color: #9bf0e1;
}

.branco{
	color: white;
}

.verde{
	color: green;
}

.nav-brand:hover {
  text-decoration: none;
}
