<template>
  <footer class="site-footer">
    <div class="footer-content">
      <!-- Logo e mini bio -->
      <div class="footer-section logo-bio">
        <img src="/public/imgs/musikcity_azulbranco.png" alt="Logo do site" class="logo" />
        <p class="bio">
          MusikCity é referência em produção musical, arranjos e consultoria com Hugo Bellard — maestro e produtor premiado.
        </p>
      </div>

      <!-- Links rápidos -->
      <div class="footer-section links">
        <h3>Links Rápidos</h3>
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/gravacao">Gravação e Arranjos</a></li>
          <li><a href="/divulgacao">Divulgação</a></li>
          <li><a href="/consultoria">Consultoria</a></li>
          <li><a href="/contato">Contato</a></li>
        </ul>
      </div>

      <!-- Contato -->
      <div class="footer-section contato">
        <h3>Contato</h3>
        <ul>
          <li>Email: contato@musikcity.com</li>
          <li>WhatsApp: (11) 99999-9999</li>
          <li>
            Redes:
            <a href="#" target="_blank">Instagram</a> |
            <a href="#" target="_blank">Facebook</a>
          </li>
        </ul>
      </div>
    </div>

    <div class="footer-bottom">
      <p>&copy; 2025 MusikCity. Todos os direitos reservados.</p>
    </div>
  </footer>
</template>

<style scoped>
.site-footer {
  color: white;
  padding: 40px 20px 20px;
  font-family: sans-serif;
}

.footer-content {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 40px;
  max-width: 1200px;
  margin: auto;
}

.footer-section {
  flex: 1 1 250px;
}

.logo-bio .logo {
  width: 140px;
  margin-bottom: 15px;
}

.bio {
  font-size: 0.95rem;
  line-height: 1.6;
  color: #e0e0e0;
}

.links h3,
.contato h3 {
  font-size: 1.2rem;
  margin-bottom: 10px;
  color: #ffffff;
}

.links ul,
.contato ul {
  list-style: none;
  padding: 0;
}

.links li,
.contato li {
  margin-bottom: 8px;
}

a {
  color: #8cd4ff;
  text-decoration: none;
  transition: color 0.3s ease;
}

a:hover {
  color: #ffffff;
}

.footer-bottom {
  text-align: center;
  margin-top: 40px;
  font-size: 0.85rem;
  border-top: 1px solid #14507c;
  padding-top: 20px;
  color: #ccc;
}

/* Responsivo */
@media (max-width: 768px) {
  .footer-content {
    flex-direction: column;
    align-items: flex-start;
  }

  .footer-section {
    width: 100%;
  }

  .logo {
    margin: 0 auto 15px;
    display: block;
  }

  .bio {
    text-align: center;
  }

  .footer-bottom {
    font-size: 0.75rem;
  }
}
</style>
