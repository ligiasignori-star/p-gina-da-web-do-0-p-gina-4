div class="pagina">

  <header>
    <h1>Meu blog tech</h1>
    <p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>
  </header>

  <main>

    <div class="logo">
      <img 
        src="https://via.placeholder.com/650x180?text=Imagem+do+Blog"
        alt="Logotipo conceitual de tecnologia e educação"
      >
    </div>

    <article>
      <h2>Meu primeiro post</h2>

      <p class="autor">
        Por: Ligia Natali Signori
      </p>

      <p>
        Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de
        programação e curiosidades da área de tecnologia.
      </p>
    </article>

  </main>

</div>
{
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 8px;
  background-color: #ffffff;
  color: #1a1a1a;
  font-family: Georgia, "Times New Roman", serif;
}

.pagina {
  width: 100%;
  min-height: 350px;
  border: 1px solid #aaa;
  padding: 8px;
}

/* Cabeçalho */
header {
  background-color: #1d4168;
  color: white;
  text-align: center;
  padding: 32px 20px 26px;
}

header h1 {
  margin: 0 0 16px;
  font-size: 28px;
}

header p {
  margin: 0;
  font-size: 14px;
  font-weight: bold;
}

/* Conteúdo */
main {
  padding: 12px 14px;
}

.logo {
  width: 100%;
  margin-bottom: 16px;
}

.logo img {
  display: block;
  max-width: 100%;
  height: auto;
}

/* Post */
article h2 {
  margin: 10px 0 16px;
  color: #183a5c;
  font-size: 21px;
}

.autor {
  margin: 0 0 14px;
  font-size: 14px;
}

article p {
  font-size: 14px;
  line-height: 1.25;
  margin-top: 0;
}
