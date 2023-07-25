<script>
	import Button from './MyButton.svelte';
  import Header from './MyHeader.svelte';
  import Alert from './MyAlert.svelte';
  import Badge from './MyBadge.svelte';
  import Carousel from './MyCarousel.svelte';
  import ListGroup from './MyListGroup.svelte';
  import Card from './MyCard.svelte';
   </script>

<Header></Header>

<h1>Bem-vindo ao meu projeto</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<div>
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
</div>

<div></div>
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

<div><Badge></Badge></div>

<div>
<Alert color ='primary'> An example alert with an icon</Alert> 
<Alert color= 'success'> An example success alert with an icon </Alert>
<Alert color= 'danger'> An example danger alert with an icon </Alert>
<Alert color= 'warning'> An example warning alert with an icon </Alert>

<Alert color='primary' outline >An example alert with an icon</Alert>
<Alert color='success' outline >An example success alert with an icon</Alert>
<Alert color='danger' outline >An example danger alert with an icon</Alert>
<Alert color='warning' outline >An example warning alert with an icon</Alert>
</div>

<Carousel></Carousel>

<ListGroup></ListGroup>

<Card></Card>


