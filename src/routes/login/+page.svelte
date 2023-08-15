<script>
  import Header from "../MyHeader.svelte";
  let password = "senha";
  let email = "";
  let checkbox = false;

  function entrar(params) {
    alert("Entre com suas credenciais para acessar o conteudo");
  }
</script>

<Header />

<body>
  <div class="container mt-4">
    <div class="row align-items-center">
      <div class="col-sm-3 m-auto col-lg-3">
        <form class="p4 was-validated p-md-3 border rounded-4 bg-info">
          <div class="form-floating mb-3" />

          <form>
            <div class="mb-3">
              <label>Login</label>
              <input
                type="email"
                class="form-control"
                placeholder="Informe seu email"
                id=""
                aria-describedby="emailHelp"
                bind:value={email}
              />
            </div>

            <div class="mb-3">
              <label>Senha</label>
              <input
                type="password"
                class="form-control"
                placeholder="Insira sua senha"
                bind:value={password}
              />
            </div>

            <div class="mb-3 form-check">
              <input
                type="checkbox"
                class="form-check-input"
                id="exampleCheck1"
                bind:checked={checkbox}
              />
              <label class="form-check-label" for="exampleCheck1"
                >Lembre-me</label
              >
            </div>

            <div class="d-grid gap-2">
              <button type="submit" class="btn btn-secondary" disabled={!checkbox|| email===""||password===""} on:click={entrar}>
                 Entrar
              </button>
            </div>
          </form>
        </form>
      </div>
    </div>
  </div></body
>
