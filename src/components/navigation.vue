<template>
  <div class="navigation-container1">
    <div class="navigation-container2">
      <div class="navigation-container3">
        <DangerousHTML html="<style>
  @media (prefers-reduced-motion: reduce) {
  .navigation, .navigation-logo, .navigation-toggle, .navigation-link, .navigation-menu, .navigation-backdrop, .navigation-item {
    animation: none;
    transition: none;
  }
  }
  </style>"></DangerousHTML>
      </div>
    </div>
    <nav id="mainNavigation" class="navigation">
      <div class="navigation-container">
        <a href="#inicio">
          <div aria-label="Milintegral - Inicio" class="navigation-logo">
            <div class="navigation-logo-icon">
              <img src="@/assets/logo.png" alt="Milintegral Logo" width="64" height="64">
            </div>
            <span class="navigation-logo-text">Milintegral</span>
          </div>
        </a>
        <button id="navigationToggle" aria-label="Alternar menú de navegación" aria-expanded="false"
          class="navigation-toggle">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
            class="navigation-navigation-toggle-icon1">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M4 5h16M4 12h16M4 19h16"></path>
          </svg><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
            class="navigation-navigation-toggle-icon2">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M18 6L6 18M6 6l12 12"></path>
          </svg>
        </button>
        <div id="navigationMenu" class="navigation-menu">
          <ul class="navigation-list">
            <li class="navigation-item">
              <a href="#catalog-title">
                <div class="navigation-link"><span>Productos</span></div>
              </a>
            </li>
            <li class="navigation-item">
              <a href="#propuesta-valor">
                <div class="navigation-link"><span>Beneficios</span></div>
              </a>
            </li>
            <li class="navigation-item">
              <a href="#main-content">
                <div class="navigation-link"><span>Nosotros</span></div>
              </a>
            </li>
            <li class="navigation-item">
              <a href="#calidad-heading">
                <div class="navigation-link"><span>Calidad</span></div>
              </a>
            </li>
            <li class="navigation-item">
              <a href="#contacto-heading">
                <div class="navigation-link"><span>Contacto</span></div>
              </a>
            </li>
          </ul>
          <div class="navigation-cta">
            <a href="#pedido">
              <div class="btn btn-primary"><span>Hacer Pedido</span></div>
            </a>
          </div>
        </div>
      </div>
      <div id="navigationBackdrop" class="navigation-backdrop"></div>
    </nav>
    <div class="navigation-container4">
      <div class="navigation-container5">
        <DangerousHTML html="<style>
          @keyframes navigationFadeSlide {from {opacity: 0;
  transform: translateY(-10px);}
  to {opacity: 1;
  transform: translateY(0);}}
          </style> "></DangerousHTML>
      </div>
    </div>
    <div class="navigation-container6">
      <div class="navigation-container7">
        <DangerousHTML html="<script defer data-name='navigation'>
  (function(){
    const navigationToggle = document.getElementById('navigationToggle')
    const navigationMenu = document.getElementById('navigationMenu')
    const navigationBackdrop = document.getElementById('navigationBackdrop')
    const navigationLinks = document.querySelectorAll('.navigation-link')
  
    function toggleNavigation() {
      const isOpen = navigationToggle.getAttribute('aria-expanded') === 'true'
  
      navigationToggle.setAttribute('aria-expanded', !isOpen)
      navigationMenu.classList.toggle('navigation-menu--open')
      navigationBackdrop.classList.toggle('navigation-backdrop--active')
  
      if (!isOpen) {
        document.body.style.overflow = 'hidden'
      } else {
        document.body.style.overflow = ''
      }
    }
  
    function closeNavigation() {
      navigationToggle.setAttribute('aria-expanded', 'false')
      navigationMenu.classList.remove('navigation-menu--open')
      navigationBackdrop.classList.remove('navigation-backdrop--active')
      document.body.style.overflow = ''
    }
  
    navigationToggle.addEventListener('click', toggleNavigation)
    navigationBackdrop.addEventListener('click', closeNavigation)
  
    navigationLinks.forEach((link) => {
      link.addEventListener('click', () => {
        if (window.innerWidth <= 991) {
          closeNavigation()
        }
      })
    })
  
    window.addEventListener('resize', () => {
      if (window.innerWidth > 991) {
        closeNavigation()
      }
    })
  
    let lastScroll = 0
    const navigation = document.querySelector('.navigation')
  
    window.addEventListener(
      'scroll',
      () => {
        const currentScroll = window.pageYOffset
  
        if (currentScroll > lastScroll && currentScroll > 100) {
          navigation.style.transform = 'translateY(-100%)'
        } else {
          navigation.style.transform = 'translateY(0)'
        }
  
        if (currentScroll > 50) {
          navigation.style.boxShadow = 'var(--shadow-level-2)'
        } else {
          navigation.style.boxShadow = 'var(--shadow-level-1)'
        }
  
        lastScroll = currentScroll
      },
      { passive: true }
    )
  })()
  </script>"></DangerousHTML>
      </div>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/vue'

export default {
  name: 'Navigation',
  props: {},
  components: {
    DangerousHTML,
  },
}
</script>

<style scoped>
.navigation-container1 {
  display: contents;
}

.navigation-container2 {
  display: none;
}

.navigation-container3 {
  display: contents;
}

.navigation-navigation-toggle-icon1 {
  color: var(--color-on-surface);
  opacity: 1;
  position: absolute;
  transform: rotate(0deg);
  transition: all var(--animation-duration-fast) var(--animation-curve-primary);
}

.navigation-navigation-toggle-icon2 {
  color: var(--color-on-surface);
  opacity: 0;
  position: absolute;
  transform: rotate(90deg);
  transition: all var(--animation-duration-fast) var(--animation-curve-primary);
}

.navigation-container4 {
  display: none;
}

.navigation-container5 {
  display: contents;
}

.navigation-container6 {
  display: none;
}

.navigation-container7 {
  display: contents;
}
</style>
