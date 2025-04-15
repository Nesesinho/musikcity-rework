<template>
  <section>
      <div>
        <h1>Leve sua música ao próximo nível com quem já levou grandes nomes ao sucesso.</h1>
        <p>Produção musical profissional, arranjos orquestrais e divulgação nacional — com o maestro Hugo Bellard, premiado com discos de ouro.</p>
        <ul>
          <li>Agendar Consultoria</li>
          <li>Enviar Minha Música</li>
          <li>Ouça Trabalhos Realizados</li>
        </ul>
      </div>
      <img src="/public/imgs/maestro.png" alt="">
    </section>
</template>

<style scoped>
section {
    display: flex;
    align-items: end;
    justify-content: space-between;
    width: 100%;
    height: 70vh;
  }

  section div {
    display: flex;
    flex-direction: column;
    height: 80%;
    margin: auto 0;
  }

  section h1 {
    color: white;
    font-size: 1.8rem;
    font-weight: 700;
  }

  section p {
    color: white;
    font-size: 1.2rem;
    padding: 1rem 0;
  }

  section ul {
    display: flex;
    padding-inline-start: 0;
    gap: 3rem;
    padding-top: 4rem;
  }

  section ul li {
    background: #00D4FF;
    background: linear-gradient(144deg,rgba(0, 212, 255, 1) 9%, rgba(9, 108, 121, 1) 50%, rgba(0, 212, 255, 1) 89%);
    font-size: 1.2rem;
    padding: .5rem .5rem;
    font-weight: 500;
    color: white;
    text-align: center;
    width: fit-content;
    border-radius: 5px;
  }

  section ul li:hover {
    cursor: pointer;
  }


  img {
    object-fit: contain;
    width: 40%;
    height: auto;
  }

  @media (max-width: 768px) {
    section {
      height: max-content;
    }

    section div {
      height: 100%;
    }

    img {
      display: none;
    }
    section ul {
      flex-direction: column;
      align-items: center;
    }

    section ul li {
      width: 80%;
      padding: 1rem 0;
    }
  }

  </style>
