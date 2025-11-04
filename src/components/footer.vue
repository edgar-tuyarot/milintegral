<template>
  <div class="footer-container1">
    <div class="footer-container2">
      <div class="footer-container3">
        <DangerousHTML
          html="<style>
  a.footer-contact-text:hover {
    color: var(--color-on-surface);
  }
  @media (prefers-reduced-motion: reduce) {
  .footer-organic-shape, .footer-logo-icon, .footer-newsletter-icon-wrapper {
    animation: none;
  }
  .footer-social-link:hover, .footer-contact-item:hover, .footer-nav-link:hover {
    transform: none;
  }
  }
  </style>"
        ></DangerousHTML>
      </div>
    </div>
    <footer id="footer-Milintegral" class="footer-main">
      <div class="footer-background-texture"></div>
      <div class="footer-organic-shape"></div>
      <div class="footer-container">
        <div class="footer-brand-section">
          <div class="footer-logo-wrapper">
            <div class="footer-logo-icon">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="32"
                height="32"
                viewBox="0 0 24 24"
              >
                <g
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                >
                  <path
                    d="M11 20A7 7 0 0 1 9.8 6.1C15.5 5 17 4.48 19 2c1 2 2 4.18 2 8c0 5.5-4.78 10-10 10"
                  ></path>
                  <path
                    d="M2 21c0-3 1.85-5.36 5.08-6C9.5 14.52 12 13 13 12"
                  ></path>
                </g>
              </svg>
            </div>
            <h3 class="footer-brand-name">Milintegral</h3>
          </div>
          <p class="footer-brand-description">
            Nutriendo tu bienestar con productos integrales de calidad natural.
            Sabor auténtico, salud integral.
            <span v-html="rawbtlh"></span>
          </p>
          <div class="footer-social-links">
            <a href="#facebook">
              <div aria-label="Facebook" class="footer-social-link">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                >
                  <path
                    fill="none"
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"
                  ></path>
                </svg>
              </div>
            </a>
            <a href="#instagram">
              <div aria-label="Instagram" class="footer-social-link">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                >
                  <g
                    fill="none"
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                  >
                    <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                    <path
                      d="M16 11.37A4 4 0 1 1 12.63 8A4 4 0 0 1 16 11.37m1.5-4.87h.01"
                    ></path>
                  </g>
                </svg>
              </div>
            </a>
            <a href="#twitter">
              <div aria-label="Twitter" class="footer-social-link">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                >
                  <path
                    fill="none"
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M22 4s-.7 2.1-2 3.4c1.6 10-9.4 17.3-18 11.6c2.2.1 4.4-.6 6-2C3 15.5.5 9.6 3 5c2.2 2.6 5.6 4.1 9 4c-.9-4.2 4-6.6 7-3.8c1.1 0 3-1.2 3-1.2"
                  ></path>
                </svg>
              </div>
            </a>
          </div>
        </div>
        <div class="footer-nav-grid">
          <div class="footer-nav-column">
            <h4 class="footer-nav-title">Navegación</h4>
            <nav class="footer-nav-list">
              <a href="#inicio">
                <div class="footer-nav-link"><span>Inicio</span></div>
              </a>
              <a href="#productos">
                <div class="footer-nav-link"><span>Productos</span></div>
              </a>
              <a href="#nosotros">
                <div class="footer-nav-link"><span>Sobre Nosotros</span></div>
              </a>
              <a href="#beneficios">
                <div class="footer-nav-link"><span>Beneficios</span></div>
              </a>
            </nav>
          </div>
          <div class="footer-nav-column">
            <h4 class="footer-nav-title">Nuestros Productos</h4>
            <nav class="footer-nav-list">
              <a href="#granos">
                <div class="footer-nav-link"><span>Granos Integrales</span></div>
              </a>
              <a href="#cereales">
                <div class="footer-nav-link"><span>Cereales</span></div>
              </a>
              <a href="#snacks">
                <div class="footer-nav-link"><span>Snacks Saludables</span></div>
              </a>
              <a href="#harinas">
                <div class="footer-nav-link"><span>Harinas Naturales</span></div>
              </a>
            </nav>
          </div>
          <div class="footer-nav-column footer-contact-column">
            <h4 class="footer-nav-title">Contacto</h4>
            <div class="footer-contact-list">
              <div class="footer-contact-item">
                <div class="footer-contact-icon">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="18"
                    height="18"
                    viewBox="0 0 24 24"
                  >
                    <path
                      fill="none"
                      stroke="currentColor"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M13.832 16.568a1 1 0 0 0 1.213-.303l.355-.465A2 2 0 0 1 17 15h3a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2A18 18 0 0 1 2 4a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v3a2 2 0 0 1-.8 1.6l-.468.351a1 1 0 0 0-.292 1.233a14 14 0 0 0 6.392 6.384"
                    ></path>
                  </svg>
                </div>
                <a href="tel:+1234567890">
                  <div class="footer-contact-text">
                    <span>
                      +1 (234) 567-890
                      <span v-html="raw9r2a"></span>
                    </span>
                  </div>
                </a>
              </div>
              <div class="footer-contact-item">
                <div class="footer-contact-icon">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="18"
                    height="18"
                    viewBox="0 0 24 24"
                  >
                    <g
                      fill="none"
                      stroke="currentColor"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                    >
                      <path d="m22 7l-8.991 5.727a2 2 0 0 1-2.009 0L2 7"></path>
                      <rect width="20" height="16" x="2" y="4" rx="2"></rect>
                    </g>
                  </svg>
                </div>
                <a href="mailto:info@Milintegral.com?subject=">
                  <div class="footer-contact-text">
                    <span>
                      info@Milintegral.com
                      <span v-html="rawpjou"></span>
                    </span>
                  </div>
                </a>
              </div>
              <div class="footer-contact-item">
                <div class="footer-contact-icon">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="18"
                    height="18"
                    viewBox="0 0 24 24"
                  >
                    <g
                      fill="none"
                      stroke="currentColor"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                    >
                      <path
                        d="M17.97 9.304A8 8 0 0 0 2 10c0 4.69 4.887 9.562 7.022 11.468m12.356-4.842a1 1 0 0 0-3.004-3.004l-4.01 4.012a2 2 0 0 0-.506.854l-.837 2.87a.5.5 0 0 0 .62.62l2.87-.837a2 2 0 0 0 .854-.506z"
                      ></path>
                      <circle cx="10" cy="10" r="3"></circle>
                    </g>
                  </svg>
                </div>
                <span class="footer-contact-text">
                  Calle Principal 123, Ciudad
                </span>
              </div>
            </div>
          </div>
        </div>
        <div class="footer-newsletter-section">
          <div class="footer-newsletter-content">
            <div class="footer-newsletter-icon-wrapper">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <g
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                >
                  <path
                    d="M11 20A7 7 0 0 1 9.8 6.1C15.5 5 17 4.48 19 2c1 2 2 4.18 2 8c0 5.5-4.78 10-10 10"
                  ></path>
                  <path
                    d="M2 21c0-3 1.85-5.36 5.08-6C9.5 14.52 12 13 13 12"
                  ></path>
                </g>
              </svg>
            </div>
            <div class="footer-newsletter-text">
              <h4 class="footer-newsletter-title">Mantente Conectado</h4>
              <p class="footer-newsletter-description">
                Recibe recetas saludables y ofertas exclusivas
                <span v-html="rawyptr"></span>
              </p>
            </div>
          </div>
          <form
            aria-label="Suscripción al boletín"
            class="footer-newsletter-form"
          >
            <div class="footer-form-wrapper">
              <input
                type="email"
                placeholder="Tu correo electrónico"
                aria-label="Correo electrónico"
                required="true"
                class="footer-email-input"
              />
              <button type="submit" class="footer-submit-btn btn btn-primary">
                Suscribirse
                <span v-html="rawkati"></span>
              </button>
            </div>
          </form>
        </div>
        <div class="footer-wave-divider">
          <svg
            viewBox="0 0 1200 60"
            preserveAspectRatio="none"
            class="footer-wave-svg"
          >
            <path
              d="M0,30 Q300,10 600,30 T1200,30 L1200,0 L0,0 Z"
              fill="currentColor"
              opacity="0.1"
            ></path>
          </svg>
        </div>
        <div class="footer-bottom">
          <p class="footer-copyright">
            &amp;copy; 2025 Milintegral. Todos los derechos reservados.
            <span v-html="rawlrwl"></span>
          </p>
          <div class="footer-legal-links">
            <a href="#privacidad">
              <div class="footer-legal-link">
                <span>
                  Política de Privacidad
                  <span v-html="rawxb79"></span>
                </span>
              </div>
            </a>
            <span class="footer-legal-separator">|</span>
            <a href="#terminos">
              <div class="footer-legal-link">
                <span>Términos de Servicio</span>
              </div>
            </a>
            <span class="footer-legal-separator">|</span>
            <a href="#cookies">
              <div class="footer-legal-link"><span>Cookies</span></div>
            </a>
          </div>
        </div>
      </div>
    </footer>
    <div class="footer-container4">
      <div class="footer-container5">
        <DangerousHTML
          html="<style>
          @keyframes footer-shape-float {0%,100% {transform: translate(0, 0) rotate(0deg);
  border-radius: 63% 37% 54% 46% / 55% 48% 52% 45%;}
  33% {transform: translate(-20px, 20px) rotate(5deg);
  border-radius: 54% 46% 63% 37% / 48% 55% 45% 52%;}
  66% {transform: translate(20px, -20px) rotate(-5deg);
  border-radius: 46% 54% 37% 63% / 52% 45% 55% 48%;}}@keyframes footer-logo-pulse {0%,100% {border-radius: 50% 40% 50% 40%;
  transform: scale(1);}
  50% {border-radius: 40% 50% 40% 50%;
  transform: scale(1.05);}}@keyframes footer-newsletter-rotate {0%,100% {border-radius: 40% 50% 40% 50%;
  transform: rotate(0deg);}
  50% {border-radius: 50% 40% 50% 40%;
  transform: rotate(10deg);}}
          </style> "
        ></DangerousHTML>
      </div>
    </div>
    <div class="footer-container6">
      <div class="footer-container7">
        <DangerousHTML
          html="<script defer data-name='footer'>
  (function(){
    // Newsletter Form Handler
    const footerForm = document.querySelector('.footer-newsletter-form')
    const emailInput = document.querySelector('.footer-email-input')
    const submitBtn = document.querySelector('.footer-submit-btn')
  
    if (footerForm && emailInput && submitBtn) {
      footerForm.addEventListener('submit', function (e) {
        e.preventDefault()
  
        const email = emailInput.value.trim()
  
        if (email && email.includes('@')) {
          // Visual feedback
          const originalText = submitBtn.textContent
          submitBtn.textContent = '¡Suscrito!'
          submitBtn.style.background = 'var(--color-accent)'
  
          // Reset form
          emailInput.value = ''
  
          // Reset button after 3 seconds
          setTimeout(function () {
            submitBtn.textContent = originalText
            submitBtn.style.background = ''
          }, 3000)
        }
      })
  
      // Add floating animation on focus
      emailInput.addEventListener('focus', function () {
        this.style.transform = 'translateY(-2px)'
        this.style.transition = 'transform 0.3s ease'
      })
  
      emailInput.addEventListener('blur', function () {
        this.style.transform = 'translateY(0)'
      })
    }
  
    // Smooth scroll for internal links
    const footerLinks = document.querySelectorAll(
      '.footer-nav-link, .footer-legal-link'
    )
  
    footerLinks.forEach(function (link) {
      link.addEventListener('click', function (e) {
        const href = this.getAttribute('href')
  
        if (href && href.startsWith('#') && href !== '#') {
          const targetElement = document.querySelector(href)
  
          if (targetElement) {
            e.preventDefault()
            targetElement.scrollIntoView({
              behavior: 'smooth',
              block: 'start',
            })
          }
        }
      })
    })
  
    // Add ripple effect to social links
    const socialLinks = document.querySelectorAll('.footer-social-link')
  
    socialLinks.forEach(function (link) {
      link.addEventListener('click', function (e) {
        const ripple = document.createElement('span')
        ripple.style.position = 'absolute'
        ripple.style.borderRadius = '50%'
        ripple.style.background = 'rgba(255, 255, 255, 0.6)'
        ripple.style.width = '20px'
        ripple.style.height = '20px'
        ripple.style.pointerEvents = 'none'
  
        const rect = this.getBoundingClientRect()
        ripple.style.left = e.clientX - rect.left - 10 + 'px'
        ripple.style.top = e.clientY - rect.top - 10 + 'px'
  
        this.style.position = 'relative'
        this.appendChild(ripple)
  
        setTimeout(function () {
          ripple.style.transform = 'scale(4)'
          ripple.style.opacity = '0'
          ripple.style.transition = 'all 0.6s ease'
        }, 10)
  
        setTimeout(function () {
          ripple.remove()
        }, 600)
      })
    })
  })()
  </script>"
        ></DangerousHTML>
      </div>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/vue'

export default {
  name: 'Footer',
  props: {},
  components: {
    DangerousHTML,
  },
  data() {
    return {
      rawbtlh: ' ',
      raw9r2a: ' ',
      rawpjou: ' ',
      rawyptr: ' ',
      rawkati: ' ',
      rawlrwl: ' ',
      rawxb79: ' ',
    }
  },
}
</script>

<style scoped>
.footer-container1 {
  display: contents;
}
 
.footer-container2 {
  display: none;
}
 
.footer-container3 {
  display: contents;
}
 
.footer-container4 {
  display: none;
}
 
.footer-container5 {
  display: contents;
}
 
.footer-container6 {
  display: none;
}
 
.footer-container7 {
  display: contents;
}
</style>
