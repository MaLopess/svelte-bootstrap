<script>
	import Button from './MyButton.svelte';
</script>

<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Svelte</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Bootstrap</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/catalog">Catalogo</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Sobre este projeto
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
            </div>
</nav>

<h1>Bem-vindo ao meu projeto</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<Button>Base class</Button>
<button type="button" class="btn">Base class</button>
<Button color= 'primary'> Primary </Button>
<button type="button" class="btn btn-primary">Primary</button>
<Button color= 'secondary'> Secondary </Button>
<button type="button" class="btn btn-secondary">Secondary</button>
<Button color= 'success'> Success </Button>
<button type="button" class="btn btn-success">Success</button>
<Button color= 'danger'> Danger </Button>
<button type="button" class="btn btn-danger">Danger</button>
<Button color= 'warning'> Warning </Button>
<button type="button" class="btn btn-warning">Warning</button>
<Button color= 'info'> Info </Button>
<button type="button" class="btn btn-info">Info</button>
<Button color= 'light'> Light </Button>
<button type="button" class="btn btn-light">Light</button>
<Button color= 'dark'> Dark </Button>
<button type="button" class="btn btn-dark">Dark</button>
<Button color= 'link'> Link </Button>
<button type="button" class="btn btn-link">Link</button>

<Button color='primary' outline >Primary</Button>
<button type="button" class="btn btn-outline-primary">Primary</button>
<Button color='secondary' outline >Secondary</Button>
<button type="button" class="btn btn-outline-secondary">Secondary</button>
<Button color='success' outline >Success</Button>
<button type="button" class="btn btn-outline-success">Success</button>
<Button color='danger' outline >Danger</Button>
<button type="button" class="btn btn-outline-danger">Danger</button>
<Button color='warning' outline >Warning</Button>
<button type="button" class="btn btn-outline-warning">Warning</button>
<Button color='info' outline >Info</Button>
<button type="button" class="btn btn-outline-info">Info</button>
<Button color='light' outline >Light</Button>
<button type="button" class="btn btn-outline-light">Light</button>
<Button color='dark' outline >Dark</Button>
<button type="button" class="btn btn-outline-dark">Dark</button>

<a class="btn btn-primary" href="#" role="button">Link</a>
<button class="btn btn-primary" type="submit">Button</button>
<input class="btn btn-primary" type="button" value="Input">
<input class="btn btn-primary" type="submit" value="Submit">
<input class="btn btn-primary" type="reset" value="Reset">

<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-primary">Left</button>
  <button type="button" class="btn btn-primary">Middle</button>
  <button type="button" class="btn btn-primary">Right</button>
</div>