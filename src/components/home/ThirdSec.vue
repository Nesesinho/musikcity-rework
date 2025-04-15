<template>
  <section class="oferecemos">
    <img src="/public/imgs/bg-third.jpg" alt="">
    <h1 class="section-title">O Que Podemos Fazer Pela Sua Música</h1>
    <div class="cards-container">

      <div class="card">
        <h2>🎵 Gravação e Arranjos Profissionais</h2>
        <p class="description">
          Dê vida à sua música com arranjos feitos por um maestro premiado.
        </p>
        <ul class="benefits">
          <li>Gravação instrumental de alta qualidade</li>
          <li>Arranjos orquestrais, pop, samba, gospel, MPB e mais</li>
          <li>Direção artística personalizada</li>
        </ul>
        <button class="btn-saiba-mais">Saiba mais</button>
      </div>

      <div class="card">
        <h2>🚀 Divulgação para Gravadoras e Rádios</h2>
        <p class="description">
          Coloque sua música na vitrine certa com estratégias profissionais.
        </p>
        <ul class="benefits">
          <li>Envio para gravadoras e rádios parceiras</li>
          <li>Presença na MusikCity® e veículos segmentados</li>
          <li>Abordagem comercial e profissional</li>
        </ul>
        <button class="btn-saiba-mais">Saiba mais</button>
      </div>

      <div class="card">
        <h2>✍️ Parceria com Letristas</h2>
        <p class="description">
          Encontre o parceiro ideal para transformar melodia em mensagem.
        </p>
        <ul class="benefits">
          <li>Conexão com letristas experientes</li>
          <li>Coautoria com segurança e contrato</li>
          <li>Desenvolvimento conjunto de letras</li>
        </ul>
        <button class="btn-saiba-mais">Saiba mais</button>
      </div>

      <div class="card">
        <h2>📞 Consultoria Musical Personalizada</h2>
        <p class="description">
          Tire dúvidas e planeje sua carreira com quem entende do mercado.
        </p>
        <ul class="benefits">
          <li>Análise técnica e artística da sua música</li>
          <li>Dicas de produção, posicionamento e estilo</li>
          <li>Orientação estratégica com Hugo Bellard</li>
        </ul>
        <button class="btn-saiba-mais">Agendar</button>
      </div>

      <div class="card">
        <h2>📻 Conexão com o Mercado de Música</h2>
        <p class="description">
          A música certa nas mãos certas. Expanda suas possibilidades.
        </p>
        <ul class="benefits">
          <li>Networking com profissionais da indústria</li>
          <li>Oportunidades em trilhas, coletâneas e mais</li>
          <li>Apoio contínuo em sua jornada musical</li>
        </ul>
        <button class="btn-saiba-mais">Saiba mais</button>
      </div>

    </div>
  </section>
</template>

<style scoped>
img {
  position: absolute;
  top: 100vh;
  left: 0;
  width: 100vw;
  z-index: -10;
}

.oferecemos {
  padding: 60px 20px;
  text-align: center;
}


.section-title {
  font-size: 2.5rem; /* você pode ajustar */
  margin-bottom: 40px;

  font-weight: bold;
  background: linear-gradient(144deg, rgba(0, 212, 255, 1) 9%, rgb(133, 239, 253) 50%, rgba(0, 212, 255, 1) 89%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;

  /* Para compatibilidade com alguns navegadores */
  background-clip: text;
  color: transparent;
}

.cards-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
}

.card {
  background: #131313;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
  padding: 30px 20px;
  max-width: 320px;
  width: 100%;
  text-align: left;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 24px rgba(0, 0, 0, 0.15);
}

.card h2 {
  font-size: 1.4rem;
  color: #9fd4ff;
  margin-bottom: 15px;
}

.description {
  font-size: 1rem;
  color: #ffffff;
  margin-bottom: 15px;
}

.benefits {
  list-style: none;
  padding: 0;
  margin-bottom: 20px;
}

.benefits li {
  margin-bottom: 10px;
  position: relative;
  padding-left: 20px;
  color: #ffffff;
}

.benefits li::before {
  content: '✔';
  position: absolute;
  left: 0;
  color: #0a82d1;
}

.btn-saiba-mais {
  background-color: #0a82d1;
  color: white;
  border: none;
  padding: 10px 18px;
  border-radius: 6px;
  cursor: pointer;
  font-weight: bold;
  transition: background-color 0.3s ease;
}

.btn-saiba-mais:hover {
  background-color: #0669a8;
}

@media (max-width: 768px) {
  .oferecemos {
    position: relative;
  }

    img {
      top: 0;
      width: auto !important;
      height: 100% !important;
    }
}
</style>
