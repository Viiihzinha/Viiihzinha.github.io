<script>
  // Aqui você pode adicionar lógica se necessário, por enquanto está vazio
</script>

<style>
  .fundo {
    background-color: rgb(245, 168, 232);
    padding: 0;
    height: 100vh; /* Ajuste a altura para 100% da tela */
    display: flex;
    justify-content: center; /* Centraliza o conteúdo horizontalmente */
    align-items: center; /* Centraliza o conteúdo verticalmente */
    margin: 0;
  }

  .container {
    position: relative; /* Container com posicionamento relativo */
    text-align: center;
  }

  .logo img {
    max-width: 200%;
    height: auto;
    width: 800px; /* Ajuste o tamanho da imagem conforme necessário */
  }

  form {
    position: absolute; /* Faz o formulário sobrepor a imagem */
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%); /* Centraliza o formulário */
    width: 100%;
    max-width: 400px; /* Limita a largura do formulário */
    background-color: rgba(255, 255, 255, 0.8); /* Fundo semi-transparente */
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  form .mb-3 {
    margin-bottom: 15px;
  }

  form .btn {
    width: 100%;
  }
</style>

<div class="fundo">
  <div class="container">
    <div class="logo">
      <img src="/Like.png" class="img-fluid" alt="Logo">
    </div>
    <form>
      <div class="mb-3">
        <label for="exampleInputEmail1" class="form-label">Email</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
        <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
      </div>
      <div class="mb-3">
        <label for="exampleInputPassword1" class="form-label">Password</label>
        <input type="password" class="form-control" id="exampleInputPassword1">
      </div>
      <div class="mb-3 form-check">
        <input type="checkbox" class="form-check-input" id="exampleCheck1">
        <label class="form-check-label" for="exampleCheck1">Check me out</label>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>
</div>
