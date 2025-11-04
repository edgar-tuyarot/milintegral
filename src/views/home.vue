<template>
  <div class="home-container1">
    <app-navigation></app-navigation>
    <div class="home-container2">
      <div class="home-container3">
        <DangerousHTML
          html="<style>
  @media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
  }
  }
  </style>"
        ></DangerousHTML>
      </div>
    </div>
    <a href="#main-content">
      <div class="skip-link"><span>Saltar al contenido principal</span></div>
    </a>
    <section
      id="hero-section"
      role="banner"
      aria-labelledby="hero-title"
      class="hero-section"
    >
      <div class="hero-panel">
        <div class="hero-visual">
          <div class="hero-image-container">
            <img
              src="https://images.pexels.com/photos/1756062/pexels-photo-1756062.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Pan artesanal integral con granos enteros sobre fondo natural"
              id="hero-main-image"
              loading="eager"
              class="hero-image"
            />
            <div class="hero-image-overlay"></div>
          </div>
        </div>
        <div class="hero-content">
          <h1 id="hero-title" class="home-hero-title hero-title">
            Milintegral  Tienda Saludable
            <span v-html="rawgzmq"></span>
          </h1>
          <p class="hero-description">
            Cocina integral que nutre cuerpo y planeta: recetas elaboradas con
            granos, semillas y productos de estación, transformadas en platos que
            reconfortan y sorprenden.
            <span v-html="rawd00q"></span>
          </p>
          <p class="hero-mission">
            Experiencia gastronómica serena, sostenible y profundamente sabrosa.
            <span v-html="rawtbyg"></span>
          </p>
        </div>
      </div>
    </section>
    <section
      id="main-content"
      aria-labelledby="sobre-marca-title"
      class="sobre-marca-section"
    >
      <div class="sobre-panel">
        <div class="sobre-hero-column">
          <div class="sobre-image-wrapper">
            <img
              src="https://images.pexels.com/photos/348689/pexels-photo-348689.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Cultivo hidropónico sostenible de vegetales orgánicos frescos"
              id="sobre-image"
              loading="lazy"
              class="sobre-hero-image"
            />
            <div class="sobre-image-backplate">
              <h2 class="sobre-vision-headline">Visión</h2>
              <p class="sobre-vision-text">
                Ser la referencia de la cocina integral que celebra lo natural:
                sabores completos, ingredientes enteros y prácticas que regeneran
                tierra y comunidad.
                <span v-html="rawrs6d"></span>
              </p>
            </div>
          </div>
        </div>
        <div class="sobre-cards-column">
          <article id="sobre-mission" class="sobre-card sobre-card-mission">
            <div class="card-icon-wrapper">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="32"
                height="32"
                viewBox="0 0 24 24"
                class="card-icon"
              >
                <path
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M11 20A7 7 0 0 1 9.8 6.1C15.5 5 17 4.48 19 2c1 2 2 4.18 2 8c0 5.5-4.78 10-10 10"
                ></path>
                <path d="M2 21c0-3 1.85-5.36 5.08-6C9.5 14.52 12 13 13 12"></path>
              </svg>
            </div>
            <h3 class="sobre-card-title">Misión</h3>
            <p class="sobre-card-body">
              Elaborar productos comestibles integrales con rigor gastronómico y
              diseño sostenible. Seleccionamos ingredientes de proximidad,
              técnicas que conservan nutrientes y presentaciones que invitan a
              disfrutar con conciencia.
              <span v-html="rawhy5t"></span>
            </p>
          </article>
          <article id="sobre-commitment" class="sobre-card sobre-card-commitment">
            <div class="card-icon-wrapper">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="32"
                height="32"
                viewBox="0 0 24 24"
                class="card-icon"
              >
                <path
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z"
                ></path>
              </svg>
            </div>
            <h3 class="sobre-card-title">Compromiso</h3>
            <p class="sobre-card-body">
              Transparencia total en origen y proceso, empaques biodegradables y
              alianzas con productores locales. Prometemos calidad premium, sabor
              auténtico y una experiencia que conecta al comensal con la
              naturaleza.
              <span v-html="rawvusk"></span>
            </p>
          </article>
        </div>
      </div>
    </section>
    <section aria-labelledby="propuesta-title" class="propuesta-valor-section">
      <div class="propuesta-container">
        <h2 id="propuesta-title" class="propuesta-headline section-title">
          Propuesta de Valor
          <span v-html="rawinqb"></span>
        </h2>
        <div class="propuesta-grid">
          <div class="propuesta-left">
            <article
              role="group"
              aria-label="Por qué elegir Milintegral"
              class="value-card"
            >
              <h3 class="value-card-title">Por qué elegir Milintegral</h3>
              <p class="value-card-text">
                Productos integrales concebidos para nutrir cuerpo y entorno.
                Seleccionamos granos, semillas y frutos en su forma más completa
                para ofrecer sabor intenso, textura honesta y beneficios reales en
                tu mesa diaria.
                <span v-html="rawqqfv"></span>
              </p>
            </article>
            <article
              role="group"
              aria-label="Beneficios cotidianos"
              class="value-card"
            >
              <h3 class="value-card-title">Beneficios cotidianos</h3>
              <p class="value-card-text">
                Energía sostenida, digestión equilibrada y sensación de saciedad
                sin artificios. Nuestros productos mantienen fibra, vitaminas y
                aceites naturales para que cada porción funcione como comida y
                cuidado.
                <span v-html="raw49c6"></span>
              </p>
            </article>
            <article
              role="group"
              aria-label="Sabor y experiencia"
              class="value-card"
            >
              <h3 class="value-card-title">Sabor y experiencia</h3>
              <p class="value-card-text">
                Recetas diseñadas para potenciar matices naturales — tostados
                ligeros, notas terrosas y dulzor sutil — presentadas con estética
                minimalista que invita a comer con calma y conciencia.
                <span v-html="rawqoaz"></span>
              </p>
            </article>
          </div>
          <div class="propuesta-right">
            <div class="vignette-wrapper">
              <figure class="value-vignette">
                <img
                  src="https://images.pexels.com/photos/7421305/pexels-photo-7421305.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
                  alt="Semillas orgánicas variadas en tarros de vidrio"
                  loading="lazy"
                />
                <div class="vignette-overlay"></div>
              </figure>
              <figure class="value-vignette">
                <img
                  src="https://images.pexels.com/photos/3735150/pexels-photo-3735150.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
                  alt="Granola crujiente casera natural"
                  loading="lazy"
                />
                <div class="vignette-overlay"></div>
              </figure>
            </div>
            <div class="routine-list">
              <h4 class="routine-title">Cómo encaja en tu rutina</h4>
              <ul class="routine-items">
                <li><span>Desayunos nutritivos sin complicación</span></li>
                <li><span>Lunch balanceado y sabroso</span></li>
                <li><span>Snacks que cuidan y satisfacen</span></li>
                <li><span>Bienestar práctico y sostenible</span></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section aria-labelledby="catalog-title" class="catalog-section">
      <div class="catalog-container">
        <div class="catalog-hero">
          <div class="catalog-hero-content">
            <h2 id="catalog-title" class="catalog-headline section-title">
              Catálogo Visual
              <span v-html="raw8zfm"></span>
            </h2>
            <p class="catalog-subhead">
              Selección curada de productos integrales, fotografiados en luz
              natural para mostrar textura y origen. Cada pieza destaca por su
              sabor auténtico y compromiso sostenible.
              <span v-html="rawmywe"></span>
            </p>
          </div>
          <div class="catalog-hero-visual">
            <img
              src="https://images.pexels.com/photos/7541727/pexels-photo-7541727.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Pan artesanal con corteza dorada perfecta"
              loading="lazy"
            />
          </div>
        </div>
        <div class="bento-grid">
          <article
            role="group"
            aria-label="Pan de masa madre integral"
            class="bento-panel panel-large"
          >
            <img
              src="https://images.pexels.com/photos/1775039/pexels-photo-1775039.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Baguettes frescas con espigas de trigo"
              loading="lazy"
            />
            <div class="panel-content">
              <h3 class="panel-title">Pan de masa madre integral</h3>
              <p class="panel-caption">
                Miga densa, corteza dorada y fermentación lenta
                <span v-html="rawwb23"></span>
              </p>
            </div>
          </article>
          <article
            role="group"
            aria-label="Granola ancestral"
            class="bento-panel"
          >
            <img
              src="https://images.pexels.com/photos/3872428/pexels-photo-3872428.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Mezcla de avena, nueces y frutas"
              loading="lazy"
            />
            <div class="panel-content">
              <h3 class="panel-title">Granola ancestral</h3>
              <p class="panel-caption">Energía limpia</p>
            </div>
          </article>
          <article
            role="group"
            aria-label="Tostadas rústicas"
            class="bento-panel"
          >
            <img
              src="https://images.pexels.com/photos/166021/pexels-photo-166021.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Pan integral tostado en rodajas"
              loading="lazy"
            />
            <div class="panel-content">
              <h3 class="panel-title">Tostadas rústicas</h3>
              <p class="panel-caption">Lino, chía, sésamo</p>
            </div>
          </article>
          <article
            role="group"
            aria-label="Barritas energéticas"
            class="bento-panel"
          >
            <img
              src="https://images.pexels.com/photos/6009489/pexels-photo-6009489.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Bowl de smoothie con frutas y semillas"
              loading="lazy"
            />
            <div class="panel-content">
              <h3 class="panel-title">Barritas energéticas</h3>
              <p class="panel-caption">Almendras y dátiles</p>
            </div>
          </article>
          <article role="group" aria-label="Galletas salvado" class="bento-panel">
            <img
              src="https://images.pexels.com/photos/5203504/pexels-photo-5203504.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Bowls de granola con chocolate y nueces"
              loading="lazy"
            />
            <div class="panel-content">
              <h3 class="panel-title">Galletas salvado &amp; cacao</h3>
              <p class="panel-caption">Dulzura equilibrada</p>
            </div>
          </article>
          <article role="group" aria-label="Mix de cereales" class="bento-panel">
            <img
              src="https://images.pexels.com/photos/7633749/pexels-photo-7633749.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Avena cayendo de un tarro de vidrio"
              loading="lazy"
            />
            <div class="panel-content">
              <h3 class="panel-title">Mix de cereales</h3>
              <p class="panel-caption">Para bowls y porridge</p>
            </div>
          </article>
          <article role="group" aria-label="Pasta artesana" class="bento-panel">
            <img
              src="https://images.pexels.com/photos/162456/bread-cereals-bake-baked-162456.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Pan de centeno con espigas de trigo"
              loading="lazy"
            />
            <div class="panel-content">
              <h3 class="panel-title">Pasta integral artesana</h3>
              <p class="panel-caption">Secado tradicional</p>
            </div>
          </article>
          <article role="group" aria-label="Cremas vegetales" class="bento-panel">
            <img
              src="https://images.pexels.com/photos/19143771/pexels-photo-19143771.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1500"
              alt="Bowl de granola sostenido en mano"
              loading="lazy"
            />
            <div class="panel-content">
              <h3 class="panel-title">Cremas vegetales</h3>
              <p class="panel-caption">Ingredientes locales</p>
            </div>
          </article>
        </div>
      </div>
    </section>
    <section aria-labelledby="calidad-heading" class="calidad-section">
      <div class="calidad-container">
        <h2 id="calidad-heading" class="calidad-headline section-title">
          Calidad y Sostenibilidad
          <span v-html="raw5zkj"></span>
        </h2>
        <div class="magazine-layout">
          <article
            role="region"
            aria-label="Calidad que nutre"
            class="calidad-hero"
          >
            <div class="hero-badge">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="28"
                height="28"
                viewBox="0 0 24 24"
                class="badge-icon"
              >
                <path
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M11.525 2.295a.53.53 0 0 1 .95 0l2.31 4.679a2.12 2.12 0 0 0 1.595 1.16l5.166.756a.53.53 0 0 1 .294.904l-3.736 3.638a2.12 2.12 0 0 0-.611 1.878l.882 5.14a.53.53 0 0 1-.771.56l-4.618-2.428a2.12 2.12 0 0 0-1.973 0L6.396 21.01a.53.53 0 0 1-.77-.56l.881-5.139a2.12 2.12 0 0 0-.611-1.879L2.16 9.795a.53.53 0 0 1 .294-.906l5.165-.755a2.12 2.12 0 0 0 1.597-1.16z"
                ></path>
              </svg>
              <span>Certificado</span>
            </div>
            <h3 class="calidad-hero-title">Calidad que nutre</h3>
            <p class="calidad-hero-body">
              Seleccionamos granos, semillas y cereales integrales de origen
              trazable, cultivados por pequeños productores que practican
              agricultura regenerativa. Cada ingrediente llega a nuestra cocina
              con certificaciones y pruebas de calidad para garantizar sabor
              pleno, fibra intacta y valor nutricional real.
              <span v-html="rawdqth"></span>
            </p>
            <div class="calidad-credentials">
              <span class="credential-item">Origen trazable</span>
              <span class="credential-item">Agricultura regenerativa</span>
              <span class="credential-item">Certificación orgánica</span>
            </div>
          </article>
          <div class="calidad-support">
            <article
              role="group"
              aria-label="Prácticas sostenibles"
              class="calidad-card"
            >
              <div class="card-icon-accent">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  class="accent-icon"
                >
                  <path
                    fill="none"
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M14 9.536V7a4 4 0 0 1 4-4h1.5a.5.5 0 0 1 .5.5V5a4 4 0 0 1-4 4a4 4 0 0 0-4 4c0 2 1 3 1 5a5 5 0 0 1-1 3M4 9a5 5 0 0 1 8 4a5 5 0 0 1-8-4m1 12h14"
                  ></path>
                </svg>
              </div>
              <h4 class="calidad-card-title">Prácticas sostenibles</h4>
              <p class="calidad-card-body">
                Empaques compostables, transporte optimizado y asociaciones con
                proyectos locales de reforestación. Reducimos desperdicio mediante
                aprovechamiento integral de materias primas.
                <span v-html="rawz0zj"></span>
              </p>
            </article>
            <article
              role="group"
              aria-label="Compromiso artesanal"
              class="calidad-card"
            >
              <div class="card-icon-accent">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  class="accent-icon"
                >
                  <path
                    fill="none"
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M2 9.5a5.5 5.5 0 0 1 9.591-3.676a.56.56 0 0 0 .818 0A5.49 5.49 0 0 1 22 9.5c0 2.29-1.5 4-3 5.5l-5.492 5.313a2 2 0 0 1-3 .019L5 15c-1.5-1.5-3-3.2-3-5.5"
                  ></path>
                </svg>
              </div>
              <h4 class="calidad-card-title">Compromiso artesanal</h4>
              <p class="calidad-card-body">
                Procesos a baja temperatura y molienda en frío para preservar
                aceites naturales y micronutrientes. Nuestros lotes son pequeños y
                supervisados para mantener consistencia y frescura.
                <span v-html="rawsoba"></span>
              </p>
            </article>
            <article role="group" aria-label="Impacto local" class="calidad-card">
              <div class="card-icon-accent">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  class="accent-icon"
                >
                  <path
                    fill="none"
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M11 20A7 7 0 0 1 9.8 6.1C15.5 5 17 4.48 19 2c1 2 2 4.18 2 8c0 5.5-4.78 10-10 10"
                  ></path>
                  <path
                    d="M2 21c0-3 1.85-5.36 5.08-6C9.5 14.52 12 13 13 12"
                  ></path>
                </svg>
              </div>
              <h4 class="calidad-card-title">Impacto local</h4>
              <p class="calidad-card-body">
                Apoyamos cadenas cortas de suministro y empleamos mano de obra
                local con compensación justa. Nuestro enfoque fortalece economías
                rurales y reduce la huella ambiental.
                <span v-html="rawlujs"></span>
              </p>
            </article>
          </div>
        </div>
      </div>
    </section>
    <section aria-labelledby="contacto-heading" class="contacto-section">
      <div class="contact-panel">
        <div class="contact-left">
          <h2 id="contacto-heading" class="contact-headline">Contacto</h2>
          <p class="contact-mission">
            Estamos aquí para acompañarte en cada paso: consultas, pedidos
            especiales y reservas para eventos con productos integrales de alta
            calidad.
            <span v-html="rawnsuj"></span>
          </p>
          <div class="quick-contact-actions">
            <a href="tel:+34600000000">
              <div aria-label="Llamar a Milintegral" class="quick-action">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                  class="action-icon"
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
                <span>+34 600 000 000</span>
              </div>
            </a>
            <a href="mailto:hola@Milintegral.com?subject=">
              <div aria-label="Enviar email a Milintegral" class="quick-action">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                  class="action-icon"
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
                <span>hola@Milintegral.com</span>
              </div>
            </a>
          </div>
        </div>
        <div class="contact-right">
          <form
            role="form"
            aria-label="Formulario de contacto"
            id="contact-form"
            class="contact-form"
          >
            <div class="form-row">
              <div class="form-field">
                <label for="contact-name">Nombre completo</label>
                <input
                  type="text"
                  id="contact-name"
                  name="true"
                  required="true"
                  aria-required="true"
                  placeholder="Tu nombre"
                />
              </div>
              <div class="form-field">
                <label for="contact-email">Correo electrónico</label>
                <input
                  type="email"
                  id="contact-email"
                  name="email"
                  required="true"
                  aria-required="true"
                  placeholder="tu@email.com"
                />
              </div>
            </div>
            <div class="form-field">
              <label for="contact-phone">Teléfono (opcional)</label>
              <input
                type="tel"
                id="contact-phone"
                name="phone"
                placeholder="+34 600 000 000"
              />
            </div>
            <div class="form-field">
              <label for="contact-type">Tipo de consulta</label>
              <select
                id="contact-type"
                name="type"
                required="true"
                aria-required="true"
              >
                <option value="true">Selecciona una opción</option>
                <option value="individual">Pedido individual</option>
                <option value="catering">Pedido para evento / catering</option>
                <option value="ingredients">
                  Consulta sobre ingredientes y trazabilidad
                  <span v-html="rawou07"></span>
                </option>
                <option value="other">Otros</option>
              </select>
            </div>
            <div class="form-field">
              <label for="contact-message">Mensaje</label>
              <textarea
                id="contact-message"
                name="message"
                rows="4"
                required="true"
                aria-required="true"
                placeholder="Cuéntanos cómo podemos ayudarte"
              ></textarea>
            </div>
            <div class="form-field">
              <label for="contact-preference">Preferencia de contacto</label>
              <select id="contact-preference" name="preference">
                <option value="email">Email</option>
                <option value="phone">Teléfono</option>
              </select>
            </div>
            <button
              type="submit"
              aria-label="Enviar consulta"
              class="btn btn-primary btn-lg"
            >
              Enviar consulta
              <span v-html="rawpzwo"></span>
            </button>
          </form>
        </div>
      </div>
      <div class="info-band">
        <div class="info-group">
          <div class="info-icon-wrapper">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="info-icon"
            >
              <path
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M14.106 5.553a2 2 0 0 0 1.788 0l3.659-1.83A1 1 0 0 1 21 4.619v12.764a1 1 0 0 1-.553.894l-4.553 2.277a2 2 0 0 1-1.788 0l-4.212-2.106a2 2 0 0 0-1.788 0l-3.659 1.83A1 1 0 0 1 3 19.381V6.618a1 1 0 0 1 .553-.894l4.553-2.277a2 2 0 0 1 1.788 0zm.894.211v15M9 3.236v15"
              ></path>
            </svg>
          </div>
          <div class="info-content">
            <h4 class="info-title">Ubicación</h4>
            <p class="info-text">Calle Verde 123, Barrio Sustento</p>
          </div>
        </div>
        <div class="info-group">
          <div class="info-icon-wrapper">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="info-icon"
            >
              <g
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
              >
                <path d="M12 6v6l4 2"></path>
                <circle cx="12" cy="12" r="10"></circle>
              </g>
            </svg>
          </div>
          <div class="info-content">
            <h4 class="info-title">Horarios</h4>
            <p class="info-text">Lun–Vie 9:00–18:00 | Sáb 9:00–14:00</p>
          </div>
        </div>
        <div class="info-group">
          <div class="info-icon-wrapper">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="info-icon"
            >
              <path
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M11 20A7 7 0 0 1 9.8 6.1C15.5 5 17 4.48 19 2c1 2 2 4.18 2 8c0 5.5-4.78 10-10 10"
              ></path>
              <path d="M2 21c0-3 1.85-5.36 5.08-6C9.5 14.52 12 13 13 12"></path>
            </svg>
          </div>
          <div class="info-content">
            <h4 class="info-title">Compromiso</h4>
            <p class="info-text">Embalaje reciclable y trazabilidad clara</p>
          </div>
        </div>
      </div>
    </section>
    <div class="home-container4">
      <div class="home-container5">
        <DangerousHTML
          html="<style>
          @keyframes float {0% {transform: translateY(0);}
  100% {transform: translateY(-10px);}}@keyframes fadeInUp {from {opacity: 0;
  transform: translateY(6px);}
  to {opacity: 1;
  transform: translateY(0);}}@keyframes fadeIn {from {opacity: 0;}
  to {opacity: 1;}}
          </style> "
        ></DangerousHTML>
      </div>
    </div>
    <div class="home-container6">
      <div class="home-container7">
        <DangerousHTML
          html="<script defer data-name='homepage-interactions'>
  (function(){
    // Form submission handler
    const contactForm = document.getElementById('contact-form')
  
    if (contactForm) {
      contactForm.addEventListener('submit', function (event) {
        event.preventDefault()
  
        const formData = new FormData(contactForm)
        const data = Object.fromEntries(formData.entries())
  
        // In a real application, you would send this data to a server
        console.log('Form submitted:', data)
  
        // Show success feedback
        alert(
          '¡Gracias por tu consulta! Te responderemos en menos de 24 horas laborables.'
        )
  
        // Reset form
        contactForm.reset()
      })
    }
  
    // Smooth scroll animation for hero CTA
    const heroCta = document.getElementById('hero-cta')
  
    if (heroCta) {
      heroCta.addEventListener('click', function () {
        // In a real application, this would navigate to a reservation system
        console.log('Reservation button clicked')
      })
    }
  
    // Intersection Observer for scroll-triggered animations
    const observerOptions = {
      threshold: 0.1,
      rootMargin: '0px 0px -50px 0px',
    }
  
    const observer = new IntersectionObserver(function (entries) {
      entries.forEach(function (entry) {
        if (entry.isIntersecting) {
          entry.target.style.opacity = '1'
          entry.target.style.transform = 'translateY(0)'
        }
      })
    }, observerOptions)
  
    // Observe elements for scroll animations
    const animatedElements = document.querySelectorAll(
      '.value-card, .bento-panel, .calidad-card'
    )
    animatedElements.forEach(function (element) {
      observer.observe(element)
    })
  
    // Add keyboard navigation support for custom interactive elements
    const interactiveElements = document.querySelectorAll(
      '.quick-action, .bento-panel'
    )
  
    interactiveElements.forEach(function (element) {
      element.addEventListener('keydown', function (event) {
        if (event.key === 'Enter' || event.key === ' ') {
          event.preventDefault()
          element.click()
        }
      })
    })
  })()
  </script>"
        ></DangerousHTML>
      </div>
    </div>
    <app-footer></app-footer>

  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/vue'

import AppNavigation from '../components/navigation'
import AppFooter from '../components/footer'

export default {
  name: 'Home',
  props: {},
  components: {
    AppNavigation,
    DangerousHTML,
    AppFooter,
  },
  data() {
    return {
      rawgzmq: ' ',
      rawd00q: ' ',
      rawtbyg: ' ',
      rawly0f: ' ',
      rawrs6d: ' ',
      rawhy5t: ' ',
      rawvusk: ' ',
      rawinqb: ' ',
      rawqqfv: ' ',
      raw49c6: ' ',
      rawqoaz: ' ',
      raw8zfm: ' ',
      rawmywe: ' ',
      rawwb23: ' ',
      raw5zkj: ' ',
      rawdqth: ' ',
      rawz0zj: ' ',
      rawsoba: ' ',
      rawlujs: ' ',
      rawnsuj: ' ',
      rawou07: ' ',
      rawpzwo: ' ',
    }
  },
  metaInfo: {
    title: 'Composed Dental Newt',
    meta: [
      {
        property: 'og:title',
        content: 'Composed Dental Newt',
      },
    ],
  },
}
</script>

<style scoped>
html {
  scroll-behavior: smooth;
}

.home-container1 {
  width: 100%;
  display: block;
  min-height: 100vh;
}
 
.home-container2 {
  display: none;
}
 
.home-container3 {
  display: contents;
}
 
.home-container4 {
  display: none;
}
 
.home-container5 {
  display: contents;
}
 
.home-container6 {
  display: none;
}
 
.home-container7 {
  display: contents;
}
 
.home-container8 {
  right: 50px;
  border: 1px solid #ffffff5c;
  bottom: 30px;
  display: flex;
  z-index: 22;
  position: fixed;
  box-shadow: 5px 5px 10px 0px rgba(31, 31, 31, 0.4);
  min-height: auto;
  align-items: center;
  padding-top: 8px;
  padding-left: 12px;
  border-radius: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  backdrop-filter: blur(6px);
  background-color: rgba(41, 41, 41, 0.41);
}
 
.home-icon28 {
  width: 24px;
  margin-right: 4px;
}
 
.home-text24 {
  color: white;
  font-size: 13px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
</style>
