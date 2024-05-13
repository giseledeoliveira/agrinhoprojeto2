<!--Este modelo pode ser reutilizado para os professores e alunos da rede estadual do Paraná -->
<!-- Agrinho 2024 NRE(Ivaiporã) NRE(GUARAPUAVA) NRE(PATO BRANCO) -->
<!-- Desenvolvido por professor Richardson Schawarski -->
<!DOCTYPE html>
<!--começo HTML-->
<html>

  <!--começo cabeçalho de informações internas do site-->
  <head>
    <title>Do campo à cidade, colhendo oportunidades</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="stilo.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Lustria&display=swap"
      rel="stylesheet"/>
    </head
  ><!--fim cabeçalho de informações internas do site-->

  <!--Começo corpo do site BODY-->
  <body>

    <!--section header  -->
    <header>
      <!--começo cabeçalho visual do site-->
      <div class="cabecalho img">
        <img class="logo__principal" src="img/logo.png" alt="Logo" />
        <h1 class="texto__cabecalho">
          Agrofloresta e a importância da polinização.
        </h1>
        <a class="cabecalho__botao" href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=53" 
        target="_blank" >NRE IVAIPORÃ</a>
        <br />
      </div>
    </header>
    <!-- fim cabeçalho visual do site-->

    <!-- primeira seção  -->
    <section class="container">
      <div class="secao1__descricao">
        <p class="secao1__titulo">O que é uma Agrofloresta?</p>
        <p class="secao1__texto">
          Agrofloresta é um sistema de uso da terra que combina árvores,
          arbustos, culturas agrícolas e/ou animais em um arranjo ecológico e
          produtivo. Esses sistemas visam imitar as características das
          florestas naturais, promovendo a biodiversidade, a reciclagem de
          nutrientes, a conservação do solo e a regulação do clima. Eles também
          podem proporcionar uma fonte sustentável de alimentos, produtos
          florestais, medicamentos e outros recursos. É uma prática que tem
          ganhado destaque por sua abordagem sustentável e amigável ao meio
          ambiente.
        </p>
      </div>
      <img
        src="img/bananas.png"
        alt="imagem de um bananal"
        class="secao1__imagem"
      />
    </section>
    <!--  fim da primeira seção -->

    <!-- segunda seção lista  -->
    <section>
      <div class="secao2__titulo">
        <p class="secao2__img__titulo">A produção de mel.</p>
      </div>

      <div class="secao2__imagens">
        <div>
        <img src="img/1.png" alt="Homen colhendo mel" />
      </div>
      <div>
        <img src="img/2.png" alt="Homen colhendo mel" />
      </div>
      <div>
        <img src="img/3.png" alt="homen coletando mel" />
      </div>
      </div>
      </div>

      <div class="secao2__subtitulo">
        <h2 class="secao2__img__subtitulo">
          As abelhas são responsáveis pela produção de mel, cera e outros
          produtos apícolas que podem representar uma fonte adicional de renda
          para os agricultores
        </h2>
      </div>
    </section>
    <!-- fim da segunda seção lista -->

    <!--terceira seção informações  -->
    <section class="container">
      <div class="secao3__imagem img">
        <div class="secao3__texto">
          <h1 class="secao3__info">
            "Descubra a doçura da natureza em cada gota de mel e a versatilidade
            dos produtos da colmeia. Experimente a pureza e os benefícios dos
            nossos produtos apícolas!"
          </h1>
          <p class="secao3__info">LuzIA -02-04-24</p>
        </div>
      </div>
    </section>
    <!-- fim da terceira seção informações -->

    <!-- quarta seção contato   -->
    <section class="container secao4">
      <div class="secao4__imagem">
      <img
        src="img/pote-mel.png"
        alt="ilustração de potes de mel"
      />
    </div>
      <div class="secao4__container">
        <p class="secao4__titulo">Contato</p>
        <p class="secao4__texto">Luzia</p>
        <br />
        <br />
        <p class="secao4__email">
          
          <span>E-mail:  </span><a href="mailto:luzia.siscati@escola.pr.gov.br"> luzia.siscati@escola.pr.gov.br</a>
          
        </p>
        <br />
        <p class="secao4__fone"><span>Telefone: </span><a href="tel:+554334725739">(43)3472 57-39</a></p>
        <br />
        <p class="secao4__endereco">
          <span>Endereço: </span>Av. Minas Gerais, 295 - Ivaiporã, PR, 86870-000
        </p>
      </div>
    </section>
    <!-- fim quarta seção contato -->

     <!--quinta  seção Relogio clima  -->
     <section class="container relogio">
      <div class="aba-conteudo ativo">
        <h3 class="aba-conteudo-titulo-principal">Relogio do clima</h3>
        <h4 class="aba-conteudo-titulo-secundario">Tempo restante para limitar o aquecimento global</h4>
        <div class="contador">
            <div class="contador-digito">
                <p class="contador-digito-numero" id="dias0">7</p>
                <p class="contador-digito-texto">dias</p>
            </div>
            <div class="contador-digito">
                <p class="contador-digito-numero" id="horas0">7</p>
                <p class="contador-digito-texto">horas</p>
            </div>
            <div class="contador-digito">
                <p class="contador-digito-numero" id="min0">7</p>
                <p class="contador-digito-texto">min</p>
            </div>
            <div class="contador-digito">
                <p class="contador-digito-numero" id="seg0">7</p>
                <p class="contador-digito-texto">seg</p>
            </div>
        </div>
    </div>
    </section>
    <!-- fim da quinta seção relogio do clima -->

    <!--rodapé  -->  
    <footer class="rodape">
      <img src="img/logo.png" alt="ceaa" class="rodape__logo" />
      <ul class="rodape__lista">
        <li class="lista__link">
          <a href="https://www.sistemafaep.org.br/agrinho/">AGRINHO 2024</a>
        </li>
        <li class="lista__link">
          <a href="https://www.instagram.com/sistema.faep/">FAEP</a>
        </li>
        <li class="lista__link">
          <a href="https://www.instagram.com/sistema.faep/">SENAR</a>
        </li>
        <li class="lista__link">
          <a
            href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=53"
            >NRE IVAIPORÃ</a
          >
        </li>
        <li  class="lista__link">
          <a  
            href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=50"
            >NRE GUARAPUAVA
          </a>
        </li>
        <li  class="lista__link">
          <a  
            href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=61"
            >NRE PATO BRANCO
          </a>
        </li>
      </ul>
      <p class="rodape__texto">Site modelo Agrinho 2024</p>
      <p class="rodape__texto">® 2024 -NRE IVAIPORÃ</p>
    </footer>
    <!-- fim rodapé-->

    <!--Javascript-->
    <script src="main.js"></script>
    <!--fim Javascript-->
  </body>
  <!--fim corpo site BODY-->
</html>
<!--fim HTML-->
