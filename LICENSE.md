
7 months ago

adicionando aula 08

7 months ago

subindo aula 10
      <!-- If we need navigation buttons -->
      <div class="swiper-button-prev"></div>
      <div class="swiper-button-next"></div>

    </div>

    <div class="card">
      <div class="card__descrição">
        <div class="descrição">
          <h3 class="descrição__titulo">Talvez você também se interesse por...</h3>
          <h2 class="descrição__titulo-livro">Angular 11 e Firebase</h2>
          <p class="descrição__texto">
            Construindo uma aplicação integrada com a plataforma do Google.
          </p>
        </div>
        <img src="img/Angular.svg" class="descrição__imagem" />
      </div>
      <div class="card__botões">
        <ul class="botões">
          <li class="botões__item">
            <img src="img/Favoritos.svg" alt="Favoritar livro" />
          </li>
          <li class="botões__item">
            <img src="img/Compras.svg" alt="Adicionar no carrinho de compras" />
          </li>
        </ul>
        <a href="#" class="botões__ancora">Saiba mais</a>
      </div>
7 months ago

adicionando aula 08
    </div>
7 months ago

adicionando aula 9

7 months ago

adicionando aula 08
  </section>

7 months ago

subindo aula 11
  <section class=”carrossel”>
    <h2 class="carrossel__titulo">Mais vendidos</h2>
    <div class="swiper">
      <!-- Additional required wrapper -->
      <!-- If we need pagination -->
      <div class="swiper-pagination"></div>

      <div class="swiper-wrapper">
        <!-- Slides -->
        <div class="swiper-slide"><img src="img/ApacheKafka.svg"
            alt="Livro sobre apache kafka e spring boot da alura books"></div>
        <div class="swiper-slide"><img src="img/Liderança.svg" alt="Livro sobre liderança em design da alura books">
        </div>
        <div class="swiper-slide"><img src="img/Javascript.svg" alt="Livro sobre javascript assertivo da alurabooks">
        </div>
        <div class="swiper-slide"><img src="img/Guia Front-end.svg" alt="Livro Guia front end"></div>
        <div class="swiper-slide"><img src="img/Portugol.svg" alt="Livro sobre portugol"></div>
        <div class="swiper-slide"><img src="img/Acessibilidade.svg" alt="livro sobre acessibilidade"></div>
      </div>

      <!-- If we need navigation buttons -->
      <div class="swiper-button-prev"></div>
      <div class="swiper-button-next"></div>
    </div>

    <div class="card">
      <!-- 1º linha -->
      <div class="card__descrição">
        <!-- 1º coluna -->
        <div class="descrição">
          <img src="img/Estrelinhas.svg" alt="Avaliação 5 estrelas">
          <h3 class="descrição__titulo">Autora do Mês</h3>
          <h2 class="descrição__titulo-livro">Juliana Agarikov</h2>
          <p class="descrição__texto">Analista de sistemas e escritora, Juliana é especialista em Front-End.
          </p>
        </div>
        <!-- 2º coluna -->
        <img src="img/Escritora.svg" class="descrição__imagem">
      </div>

      <!-- 2º linha -->
      <div class="card__botões">
        <!-- 1º coluna -->
        <ul class="botões">
          <li class="botões__item"><img src="img/Favoritos.svg" alt="Favoritar livro"></li>
          <li class="botões__item"><img src="img/Compras.svg" alt="Adicionar no carrinho de compras"></li>
        </ul>
        <!-- 2º coluna -->
        <a href="#" class="botões__ancora">Saiba mais</a>
      </div>
    </div>



  </section>

  <section class="tópicos">
    <h2 class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
    <ul class="tópicos__lista">
      <li class="tópicos__item"><a href="#" class="tópicos__link">Android</a></li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Marketing Digital</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Agile</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Startups</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">HTML & CSS</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Python</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">OO</a>
      </li>
      <li class="tópicos__item">
        <a href="#" class="tópicos__link">Java</a>
      </li>
    </ul>
  </section>

6 months ago

subindo aula 12
  <section class="contato">
    <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
    <p class="contato__texto">
      Atualizações de e-books, novos livros, promoções e outros.
    </p>
4 months ago

atualização aula 13
    <input type="email" placeholder="        Cadastre seu e-mail" class="contato__email" />
6 months ago

subindo aula 12
  </section>

  <hr />

  <footer class="rodapé">
    <h2 class="rodapé__titulo">Grupo Alura</h2>
  </footer>

7 months ago

adicionando aula 9
  <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
  <script>
    const swiper = new Swiper(".swiper", {
      spaceBetween: 10,
      slidesPerView: 3,
      pagination: {
        el: ".swiper-pagination",
        type: "bullets",
      },
    });
  </script>
7 months ago

adicionando aula 2
</body>

7 months ago

adicionando aula 3
</html>
