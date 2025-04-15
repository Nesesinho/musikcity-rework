<template>
  <header>
    <img src="/public/imgs/musikcity_azulbranco.png " alt="">
    <ul>
      <li>Gravação e Arranjos</li>
      <li>Divulgação</li>
      <li>Parcerias</li>
      <li>Portfólio</li>
      <li>Consultoria</li>
      <li>Sobre</li>
    </ul>
    <img class="menu" src="/public/imgs/menu.png" alt="">
  </header>
</template>

<style scoped>
  header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1rem 0;
    height: 4.5rem;
  }

  header img {
    height: 2rem;
  }

  .menu {
    display: none;
  }

  header ul {
    display: flex;
    align-items: center;
    gap: 1.5rem;
    color: white;
    list-style: none;
  }

  header ul li {
    font-weight: 400;
    font-size: 1.1rem;
  }

  header ul li:hover {
    cursor: pointer;
  }

  @media (max-width: 768px) {
    header ul {
      display: none;
    }

    .menu {
      display: block;
    }
  }
</style>
