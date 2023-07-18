<script>
	import Button from './MyButton.svelte';
  import Header from './MyHeader.svelte';
  import Alert from './MyAlert.svelte';
  import Badge from './MyBadge.svelte';
  import Carousel from './MyCarousel.svelte';
  import ListGroup from './MyListGroup.svelte';
   </script>

<Header></Header>

<h1>Bem-vindo ao meu projeto</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<Button>Base class</Button>

<Button color= 'primary'> Primary </Button>

<Button color= 'secondary'> Secondary </Button>

<Button color= 'success'> Success </Button>

<Button color= 'danger'> Danger </Button>

<Button color= 'warning'> Warning </Button>

<Button color= 'info'> Info </Button>

<Button color= 'light'> Light </Button>

<Button color= 'dark'> Dark </Button>

<Button color= 'link'> Link </Button>


<Button color='primary' outline >Primary</Button>

<Button color='secondary' outline >Secondary</Button>

<Button color='success' outline >Success</Button>

<Button color='danger' outline >Danger</Button>

<Button color='warning' outline >Warning</Button>

<Button color='info' outline >Info</Button>

<Button color='light' outline >Light</Button>

<Button color='dark' outline >Dark</Button>

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

<div>
<Alert color ='primary'> Primary </Alert> 
<Alert color= 'success'> Success </Alert>
<Alert color= 'danger'> Danger </Alert>
<Alert color= 'warning'> Warning </Alert>

<Alert color='primary' outline >Primary</Alert>
<Alert color='success' outline >Success</Alert>
<Alert color='danger' outline >Danger</Alert>
<Alert color='warning' outline >Warning</Alert>
</div>

<h1>Example heading <span class="badge bg-secondary">New</span></h1>
<h2>Example heading <span class="badge bg-secondary">New</span></h2>
<h3>Example heading <span class="badge bg-secondary">New</span></h3>
<h4>Example heading <span class="badge bg-secondary">New</span></h4>
<h5>Example heading <span class="badge bg-secondary">New</span></h5>
<h6>Example heading <span class="badge bg-secondary">New</span></h6>

<div id="carouselExampleIndicators" class="carousel slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

<div class="list-group">
  <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
    The current link item
  </a>
  <a href="#" class="list-group-item list-group-item-action">A second link item</a>
  <a href="#" class="list-group-item list-group-item-action">A third link item</a>
  <a href="#" class="list-group-item list-group-item-action">A fourth link item</a>
  <a class="list-group-item list-group-item-action disabled">A disabled link item</a>
</div>