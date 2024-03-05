## nlw-together

### Figma

https://www.figma.com/community/file/1009807319507822993

https://efficient-sloth-d85.notion.site/OriginSix-e371b95102074411a6eca3ba640f0ecd


### Aula 01 O começo de tudo

Nesta aula teremos o conhecimento inicial de programação. Estaremos iniciando nosso projeto e adquirindo conhecimentos fundamentais de HTML e CSS, além de iniciarmos um novo vocabulário de palavras desse universo da programação.

### Aula 02 Expandindo o conhecimento

Nesta aula iremos adicionar mais informações, tags html e estilo ao nosso projeto, aumentando nosso vocabulário de propriedades CSS, além do HTML. Daremos início à programação em JavasScript.

### Aula 03 Novos controles



Nesta aula vamos construir novos elementos para o nosso projeto, fazendo ele ficar ainda mais dinâmico e único, com mais programação Javascript e ajustes CSS. Aprenderemos a usar códigos de outros desenvolvedores.

### Corrigindo o bug da lib Swiper

### A paginação não aparece como a do vídeo

Depois da gravação desta aula, a **lib Swiper** foi atualizada e isso está causando um bug que faz com que a paginação dos slides não fique no posicionamento correto. Mas você não precisa se preocupar, esse é um problema bem simples de corrigir. Veja:

De acordo com a documentação do Swiper (https://swiperjs.com/get-started#add-swiper-html-layout), foi adicionado uma classe `swiper` onde, transferindo para o código do OriginSix, está a classe `container`. Logo, para corrigir o erro e não quebrar o CSS do projeto, basta adicionar a classe `swiper` ao lado da classe `container`.

**Abaixo você pode conferir como deve ficar o código da section  #testimonials:**

<!-- TESTIMONIALS -->
      <section class="section" id="testimonials">
        <div class="container swiper"> <!-- Adicionar aqui a classe swiper -->
          <header>
            <h2 class="title">Depoimentos de quem já passou por aqui</h2>
          </header>
          <div class="testimonials swiper-container">
            <div class="swiper-wrapper">
              <div class="testimonial swiper-slide">
                <blockquote>
                  <p>
                    <span>&ldquo;</span>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Rerum blanditiis saepe nam excepturi explicabo ipsa error
                    ipsam neque
                  </p>
                  <cite>
                    <img
                      src="assets/fotos/10.jpeg"
                      alt="Foto de Wanessa Souza"
                    />
                    Wanessa Souza
                  </cite>
                </blockquote>
              </div>

              <div class="testimonial swiper-slide">
                <blockquote>
                  <p>
                    <span>&ldquo;</span>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Rerum blanditiis saepe nam excepturi explicabo ipsa error
                    ipsam neque
                  </p>
                  <cite>
                    <img
                      src="assets/fotos/56.jpeg"
                      alt="Foto de Franciele Venega"
                    />
                    Franciele Venega
                  </cite>
                </blockquote>
              </div>

              <div class="testimonial swiper-slide">
                <blockquote>
                  <p>
                    <span>&ldquo;</span>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Rerum blanditiis saepe nam excepturi explicabo ipsa error
                    ipsam neque
                  </p>
                  <cite>
                    <img
                      src="assets/fotos/26.jpeg"
                      alt="Fotos de Valeska Fabris"
                    />
                    Valeska Fabris
                  </cite>
                </blockquote>
              </div>
            </div>

            <!-- If we need pagination -->
            <div class="swiper-pagination"></div>
          </div>
        </div>
      </section>


### Aula 4: Aprofundando os conceitos


Nesta aula ganharemos maior conhecimento de JavaScript e seus conceitos que irão fazer nossa aplicação ganhar maiores poderes! Adicionaremos os componentes finais da nossa aplicação