<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
      <div class="container">
        <a class="navbar-brand" href="#">Грибная Компания</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" href="#about">О нас</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#products">Продукция</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Контакты</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div class="infinite-scroll">
      <section id="hero" class="section hero-section">
        <div class="hero-background">
          <div class="parallax-overlay"></div>
          <img src="@/assets/mushroom-hero.jpg" alt="Шампиньоны" class="parallax-img">
        </div>
        <div class="container position-relative hero-content">
          <div class="row align-items-center min-vh-100">
            <div class="col-lg-8 col-md-10 mx-auto text-center">
              <h1 class="hero-title" data-aos="fade-up">
                Свежие шампиньоны с собственной фермы — качество, которое вы почувствуете!
              </h1>
              <p class="hero-subtitle" data-aos="fade-up" data-aos-delay="200">
                Оптовые поставки для ресторанов, магазинов и предприятий. Гарантия свежести и доступные цены.
              </p>
              <div class="hero-buttons" data-aos="fade-up" data-aos-delay="400">
                <a href="#contact" class="btn btn-primary btn-lg me-3">Заказать сейчас</a>
                <a href="#about" class="btn btn-outline-light btn-lg">Узнать больше</a>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="about" class="section about-section">
        <div class="container">
          <div class="row align-items-center">
            <div class="col-lg-6" data-aos="fade-right">
              <div class="about-content">
                <h2 class="section-title">О нашей компании</h2>
                <p class="about-text">
                  Мы — современная ферма по выращиванию шампиньонов, работающая с 2022 года. 
                  Наши грибы выращиваются в экологически чистых условиях с использованием передовых технологий. 
                  Мы гарантируем свежесть, качество и стабильные поставки для наших клиентов.
                </p>
                <div class="about-features">
                  <div class="feature-item">
                    <i class="fas fa-leaf"></i>
                    <span>Экологически чистое производство</span>
                  </div>
                  <div class="feature-item">
                    <i class="fas fa-truck"></i>
                    <span>Быстрая доставка</span>
                  </div>
                  <div class="feature-item">
                    <i class="fas fa-certificate"></i>
                    <span>Гарантия качества</span>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-6" data-aos="fade-left">
              <div class="about-image-wrapper">
                <img src="@/assets/farm.jpg" alt="Наша ферма" class="about-image">
                <div class="image-overlay"></div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="advantages" class="section advantages-section">
        <div class="container">
          <h2 class="section-title text-center" data-aos="fade-up">Почему выбирают нас?</h2>
          <div class="row g-4">
            <div class="col-lg-3 col-md-6" data-aos="fade-up" data-aos-delay="100">
              <div class="advantage-card">
                <div class="advantage-icon">
                  <i class="fas fa-leaf"></i>
                </div>
                <h3>Экологически чистая продукция</h3>
                <p>Мы используем только натуральные субстраты и удобрения.</p>
              </div>
            </div>
            <div class="col-lg-3 col-md-6" data-aos="fade-up" data-aos-delay="200">
              <div class="advantage-card">
                <div class="advantage-icon">
                  <i class="fas fa-clock"></i>
                </div>
                <h3>Свежесть и качество</h3>
                <p>Грибы доставляются сразу после сбора.</p>
              </div>
            </div>
            <div class="col-lg-3 col-md-6" data-aos="fade-up" data-aos-delay="300">
              <div class="advantage-card">
                <div class="advantage-icon">
                  <i class="fas fa-handshake"></i>
                </div>
                <h3>Гибкие условия сотрудничества</h3>
                <p>Индивидуальные условия для каждого клиента.</p>
              </div>
            </div>
            <div class="col-lg-3 col-md-6" data-aos="fade-up" data-aos-delay="400">
              <div class="advantage-card">
                <div class="advantage-icon">
                  <i class="fas fa-truck"></i>
                </div>
                <h3>Стабильные поставки</h3>
                <p>Мы работаем без перебоев, даже в пиковые сезоны.</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="products" class="section products-section">
        <div class="container">
          <div class="text-center mb-5" data-aos="fade-up">
            <h2 class="section-title">Наш ассортимент</h2>
            <p class="section-description">
              Мы предлагаем шампиньоны различных категорий: от мелких до крупных, в удобной упаковке. 
              Всегда в наличии свежие грибы, готовые к поставке.
            </p>
          </div>
          
          <div class="row g-4">
            <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="100">
              <div class="product-card">
                <div class="product-image-wrapper">
                  <img src="@/assets/mushroom-basket.jpg" alt="Шампиньоны в корзинах" class="product-image">
                  <div class="product-overlay">
                    <div class="product-details">
                      <h3>Шампиньоны в корзинах</h3>
                      <p>Свежесобранные грибы в традиционной упаковке</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            
            <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="200">
              <div class="product-card">
                <div class="product-image-wrapper">
                  <img src="@/assets/mushroom-package.jpg" alt="Упаковки для ресторанов" class="product-image">
                  <div class="product-overlay">
                    <div class="product-details">
                      <h3>Упаковки для ресторанов</h3>
                      <p>Специальная упаковка для профессиональной кухни</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            
            <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="300">
              <div class="product-card">
                <div class="product-image-wrapper">
                  <img src="@/assets/mushroom-closeup.jpg" alt="Грибы крупным планом" class="product-image">
                  <div class="product-overlay">
                    <div class="product-details">
                      <h3>Грибы крупным планом</h3>
                      <p>Отборные шампиньоны высшего качества</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="technology" class="section technology-section">
        <div class="container">
          <div class="text-center mb-5" data-aos="fade-up">
            <h2 class="section-title">Как мы выращиваем наши шампиньоны</h2>
            <p class="section-description">
              Мы используем современные технологии и строго контролируем каждый этап выращивания: 
              от подготовки субстрата до сбора урожая. Это позволяет нам гарантировать высочайшее качество продукции.
            </p>
          </div>

          <div class="technology-slider" data-aos="fade-up">
            <swiper
              :modules="[SwiperAutoplay, SwiperPagination, SwiperNavigation]"
              :slides-per-view="1"
              :space-between="30"
              :loop="true"
              :autoplay="{
                delay: 5000,
                disableOnInteraction: false,
              }"
              :pagination="{ clickable: true }"
              :navigation="true"
              class="technology-swiper"
            >
              <swiper-slide>
                <div class="technology-slide">
                  <div class="slide-image">
                    <img src="@/assets/substrate.jpg" alt="Подготовка субстрата">
                    <div class="slide-overlay"></div>
                  </div>
                  <div class="slide-content">
                    <h3>Подготовка субстрата</h3>
                    <p>Создание идеальной питательной среды для выращивания шампиньонов с использованием современных технологий и экологически чистых компонентов.</p>
                  </div>
                </div>
              </swiper-slide>

              <swiper-slide>
                <div class="technology-slide">
                  <div class="slide-image">
                    <img src="@/assets/mycelium.jpg" alt="Посев мицелия">
                    <div class="slide-overlay"></div>
                  </div>
                  <div class="slide-content">
                    <h3>Посев мицелия</h3>
                    <p>Тщательный контроль процесса засева мицелия в подготовленный субстрат с соблюдением всех технологических параметров.</p>
                  </div>
                </div>
              </swiper-slide>

              <swiper-slide>
                <div class="technology-slide">
                  <div class="slide-image">
                    <img src="@/assets/harvest.jpg" alt="Сбор урожая">
                    <div class="slide-overlay"></div>
                  </div>
                  <div class="slide-content">
                    <h3>Сбор урожая</h3>
                    <p>Сбор грибов в оптимальной стадии зрелости с последующей сортировкой и упаковкой для сохранения свежести.</p>
                  </div>
                </div>
              </swiper-slide>
            </swiper>
          </div>
        </div>
      </section>

      <section id="testimonials" class="section testimonials-section">
        <div class="container">
          <div class="text-center mb-5" data-aos="fade-up">
            <h2 class="section-title">Что говорят наши клиенты</h2>
          </div>

          <div class="testimonials-slider" data-aos="fade-up">
            <swiper
              :modules="[SwiperAutoplay, SwiperPagination]"
              :slides-per-view="1"
              :space-between="30"
              :loop="true"
              :autoplay="{
                delay: 5000,
                disableOnInteraction: false,
              }"
              :pagination="{ clickable: true }"
              class="testimonials-swiper"
            >
              <swiper-slide>
                <div class="testimonial-card">
                  <div class="testimonial-content">
                    <i class="fas fa-quote-left"></i>
                    <p class="testimonial-text">
                      Отличное качество грибов! Всегда свежие и вкусные. Рекомендую!
                    </p>
                    <div class="testimonial-author">
                      <span class="author-name">Ресторан "Гриль Хаус"</span>
                    </div>
                  </div>
                </div>
              </swiper-slide>

              <swiper-slide>
                <div class="testimonial-card">
                  <div class="testimonial-content">
                    <i class="fas fa-quote-left"></i>
                    <p class="testimonial-text">
                      Сотрудничаем уже несколько лет. Ни разу не подводили с поставками.
                    </p>
                    <div class="testimonial-author">
                      <span class="author-name">Магазин "Овощи и Фрукты"</span>
                    </div>
                  </div>
                </div>
              </swiper-slide>

              <swiper-slide>
                <div class="testimonial-card">
                  <div class="testimonial-content">
                    <i class="fas fa-quote-left"></i>
                    <p class="testimonial-text">
                      Лучшие шампиньоны в регионе! Всегда рады сотрудничеству.
                    </p>
                    <div class="testimonial-author">
                      <span class="author-name">Кафе "Уютное место"</span>
                    </div>
                  </div>
                </div>
              </swiper-slide>
            </swiper>
          </div>
        </div>
      </section>

      <section id="contact" class="section contact-section">
        <div class="container">
          <div class="text-center mb-5" data-aos="fade-up">
            <h2 class="section-title">Свяжитесь с нами!</h2>
            <p class="section-description">
              Оставьте заявку, и мы свяжемся с вами для уточнения деталей.
            </p>
          </div>

          <div class="row justify-content-center">
            <div class="col-lg-8">
              <div class="contact-wrapper" data-aos="fade-up">
                <div class="row">
                  <div class="col-lg-6">
                    <div class="contact-info">
                      <h3>Наши контакты</h3>
                      <div class="contact-items">
                        <div class="contact-item">
                          <i class="fas fa-phone"></i>
                          <div class="contact-details">
                            <h4>Телефон</h4>
                            <p>+7 (XXX) XXX-XX-XX</p>
                          </div>
                        </div>
                        <div class="contact-item">
                          <i class="fas fa-envelope"></i>
                          <div class="contact-details">
                            <h4>Email</h4>
                            <p>info@mushroomfarm.ru</p>
                          </div>
                        </div>
                        <div class="contact-item">
                          <i class="fas fa-map-marker-alt"></i>
                          <div class="contact-details">
                            <h4>Адрес</h4>
                            <p>г. Москва, ул. Грибная, д. 10</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="col-lg-6">
                    <form class="contact-form">
                      <div class="form-group">
                        <input type="text" class="form-control" placeholder="Ваше имя" required>
                      </div>
                      <div class="form-group">
                        <input type="tel" class="form-control" placeholder="Ваш телефон" required>
                      </div>
                      <div class="form-group">
                        <input type="email" class="form-control" placeholder="Ваш email" required>
                      </div>
                      <button type="submit" class="btn btn-primary w-100">Отправить заявку</button>
                    </form>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <footer class="footer" data-aos="fade-up">
        <div class="container">
          <div class="row">
            <div class="col-lg-4 col-md-6 mb-4 mb-lg-0">
              <div class="footer-brand">
                <h3>Грибная Ферма</h3>
                <p>Качественные шампиньоны для вашего бизнеса</p>
              </div>
            </div>
            <div class="col-lg-2 col-md-6 mb-4 mb-lg-0">
              <h4>Навигация</h4>
              <ul class="footer-links">
                <li><a href="#about">О компании</a></li>
                <li><a href="#products">Продукция</a></li>
                <li><a href="#contact">Контакты</a></li>
              </ul>
            </div>
            <div class="col-lg-3 col-md-6 mb-4 mb-lg-0">
              <h4>Контакты</h4>
              <ul class="footer-contact">
                <li><i class="fas fa-phone"></i> +7 (XXX) XXX-XX-XX</li>
                <li><i class="fas fa-envelope"></i> info@mushroomfarm.ru</li>
                <li><i class="fas fa-map-marker-alt"></i> г. Москва, ул. Грибная, д. 10</li>
              </ul>
            </div>
            <div class="col-lg-3 col-md-6">
              <h4>Социальные сети</h4>
              <div class="social-links">
                <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
                <a href="#" class="social-link"><i class="fab fa-facebook"></i></a>
                <a href="#" class="social-link"><i class="fab fa-whatsapp"></i></a>
              </div>
            </div>
          </div>
          <div class="footer-bottom">
            <p>&copy; 2023 Грибная Ферма. Все права защищены.</p>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap/dist/js/bootstrap.bundle.min.js'
import AOS from 'aos'
import 'aos/dist/aos.css'
import '@fortawesome/fontawesome-free/css/all.min.css'
import { Swiper, SwiperSlide } from 'swiper/vue'
import { Autoplay, Pagination, Navigation } from 'swiper/modules'
import 'swiper/css'
import 'swiper/css/pagination'
import 'swiper/css/navigation'

// Добавляем импорт шрифтов
const link = document.createElement('link')
link.rel = 'stylesheet'
link.href = 'https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&family=Playfair+Display:wght@700&family=Roboto:wght@300;400;500&display=swap'
document.head.appendChild(link)

export default {
  name: 'App',
  components: {
    Swiper,
    SwiperSlide
  },
  data() {
    return {
      SwiperAutoplay: Autoplay,
      SwiperPagination: Pagination,
      SwiperNavigation: Navigation
    }
  },
  mounted() {
    AOS.init({
      duration: 1000,
      once: true
    })

    // Параллакс эффект для фонового изображения
    window.addEventListener('scroll', () => {
      const parallaxImg = document.querySelector('.parallax-img')
      const scrolled = window.pageYOffset
      parallaxImg.style.transform = `scale(1.1) translateY(${scrolled * 0.5}px)`
    })
  }
}
</script>

<style>
#app {
  font-family: 'Roboto', sans-serif;
}

.navbar {
  background-color: rgba(0, 0, 0, 0.8);
  backdrop-filter: blur(10px);
}

.section {
  min-height: 100vh;
  padding: 100px 0;
  display: flex;
  align-items: center;
  margin: 20px;
  border-radius: 20px;
  background-color: #ffffff;
  box-shadow: 0 10px 30px rgba(0,0,0,0.05);
}

.container {
  padding: 0 30px;
}

@media (max-width: 768px) {
  .section {
    margin: 10px;
    padding: 60px 0;
  }
  
  .container {
    padding: 0 15px;
  }
}

#hero {
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
}

.card {
  border: none;
  border-radius: 15px;
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-10px);
}

.product-card {
  padding: 20px;
  border-radius: 15px;
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  margin-bottom: 30px;
}

.product-card img {
  border-radius: 10px;
  margin-bottom: 20px;
}

.btn-primary {
  background-color: #2c3e50;
  border-color: #2c3e50;
}

.btn-primary:hover {
  background-color: #34495e;
  border-color: #34495e;
}

.infinite-scroll {
  position: relative;
  overflow: hidden;
}

.infinite-scroll::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  background: linear-gradient(to bottom, transparent, rgba(255,255,255,0.1));
}

.hero-section {
  position: relative;
  padding: 0;
  overflow: hidden;
  min-height: 100vh;
  margin: 20px;
  border-radius: 20px;
  background: none;
  box-shadow: 0 10px 30px rgba(0,0,0,0.05);
}

.hero-background {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
  border-radius: 20px;
  overflow: hidden;
}

.parallax-img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  transform: scale(1.1);
  transition: transform 0.5s ease-out;
  border-radius: 20px;
}

.parallax-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(
    to bottom,
    rgba(0, 0, 0, 0.7),
    rgba(0, 0, 0, 0.5)
  );
  z-index: 2;
  border-radius: 20px;
}

.hero-title {
  font-family: 'Playfair Display', serif;
  font-size: 3.5rem;
  font-weight: 700;
  color: #ffffff;
  margin-bottom: 1.5rem;
  line-height: 1.2;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
}

.hero-subtitle {
  font-family: 'Montserrat', sans-serif;
  font-size: 1.5rem;
  color: #ffffff;
  margin-bottom: 2rem;
  line-height: 1.6;
  text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);
  font-weight: 300;
}

.hero-buttons {
  margin-top: 2rem;
}

.btn-primary {
  background-color: #4CAF50;
  border-color: #4CAF50;
  padding: 1rem 2rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 1px;
  transition: all 0.3s ease;
}

.btn-primary:hover {
  background-color: #45a049;
  border-color: #45a049;
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}

.btn-outline-light {
  padding: 1rem 2rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 1px;
  transition: all 0.3s ease;
}

.btn-outline-light:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}

@media (max-width: 768px) {
  .hero-section {
    margin: 10px;
    border-radius: 15px;
  }
  
  .hero-background,
  .parallax-img,
  .parallax-overlay {
    border-radius: 15px;
  }
  
  .hero-title {
    font-size: 2.5rem;
  }
  
  .hero-subtitle {
    font-size: 1.2rem;
  }
  
  .hero-buttons {
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  
  .btn {
    width: 100%;
    margin: 0 !important;
  }
}

.hero-content {
  z-index: 3;
  position: relative;
}

.about-section {
  background-color: #f0f7ff;
  padding: 120px 0;
}

.section-title {
  font-family: 'Playfair Display', serif;
  font-size: 2.5rem;
  font-weight: 700;
  color: #2c3e50;
  margin-bottom: 2rem;
  position: relative;
  padding-bottom: 1rem;
}

.section-title::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 80px;
  height: 4px;
  background-color: #4CAF50;
  border-radius: 2px;
}

.about-content {
  padding-right: 2rem;
}

.about-text {
  font-family: 'Roboto', sans-serif;
  font-size: 1.1rem;
  line-height: 1.8;
  color: #666;
  margin-bottom: 2rem;
  font-weight: 300;
}

.about-features {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.feature-item {
  font-family: 'Montserrat', sans-serif;
  display: flex;
  align-items: center;
  gap: 1rem;
  font-size: 1.1rem;
  color: #2c3e50;
  font-weight: 500;
}

.feature-item i {
  color: #4CAF50;
  font-size: 1.5rem;
}

.about-image-wrapper {
  position: relative;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 20px 40px rgba(0,0,0,0.1);
}

.about-image {
  width: 100%;
  height: 500px;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.image-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(
    to bottom,
    rgba(0,0,0,0.2),
    rgba(0,0,0,0.1)
  );
}

.about-image-wrapper:hover .about-image {
  transform: scale(1.05);
}

@media (max-width: 991px) {
  .about-content {
    padding-right: 0;
    margin-bottom: 3rem;
  }
  
  .about-image {
    height: 400px;
  }
}

@media (max-width: 768px) {
  .section-title {
    font-size: 2rem;
  }
  
  .about-text {
    font-size: 1rem;
  }
  
  .feature-item {
    font-size: 1rem;
  }
}

.advantages-section {
  background-color: #ffffff;
  padding: 100px 0;
}

.advantage-card {
  background: #ffffff;
  border-radius: 15px;
  padding: 2rem;
  height: 100%;
  text-align: center;
  transition: all 0.3s ease;
  box-shadow: 0 10px 30px rgba(0,0,0,0.05);
  border: 1px solid rgba(0,0,0,0.05);
}

.advantage-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 15px 40px rgba(0,0,0,0.1);
}

.advantage-icon {
  width: 80px;
  height: 80px;
  margin: 0 auto 1.5rem;
  background: rgba(76, 175, 80, 0.1);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: all 0.3s ease;
}

.advantage-icon i {
  font-size: 2rem;
  color: #4CAF50;
  transition: all 0.3s ease;
}

.advantage-card:hover .advantage-icon {
  background: #4CAF50;
}

.advantage-card:hover .advantage-icon i {
  color: #ffffff;
}

.advantage-card h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1.25rem;
  font-weight: 700;
  color: #2c3e50;
  margin-bottom: 1rem;
}

.advantage-card p {
  font-family: 'Roboto', sans-serif;
  font-size: 1rem;
  color: #666;
  line-height: 1.6;
  margin: 0;
  font-weight: 300;
}

@media (max-width: 991px) {
  .advantage-card {
    margin-bottom: 1rem;
  }
}

@media (max-width: 768px) {
  .advantage-card {
    padding: 1.5rem;
  }
  
  .advantage-icon {
    width: 60px;
    height: 60px;
  }
  
  .advantage-icon i {
    font-size: 1.5rem;
  }
  
  .advantage-card h3 {
    font-size: 1.1rem;
  }
  
  .advantage-card p {
    font-size: 0.9rem;
  }
}

.products-section {
  background-color: #f5f9f0;
  padding: 100px 0;
}

.section-description {
  font-family: 'Montserrat', sans-serif;
  font-size: 1.2rem;
  color: #666;
  max-width: 800px;
  margin: 0 auto 3rem;
  line-height: 1.8;
  font-weight: 300;
}

.product-card {
  margin-bottom: 0;
  padding: 0;
  border: none;
  box-shadow: none;
  background: transparent;
}

.product-image-wrapper {
  position: relative;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  aspect-ratio: 4/3;
}

.product-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.product-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(
    to bottom,
    rgba(0,0,0,0.7),
    rgba(0,0,0,0.3)
  );
  display: flex;
  align-items: flex-end;
  opacity: 1;
  transition: opacity 0.3s ease;
}

.product-details {
  padding: 2rem;
  color: #ffffff;
  transform: translateY(0);
  transition: transform 0.3s ease;
}

.product-details h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
  transform: translateY(0);
  transition: transform 0.3s ease;
}

.product-details p {
  font-family: 'Roboto', sans-serif;
  font-size: 1rem;
  margin: 0;
  transform: translateY(0);
  transition: transform 0.3s ease;
  font-weight: 300;
}

@media (hover: hover) {
  .product-overlay {
    opacity: 0;
  }

  .product-image-wrapper:hover .product-overlay {
    opacity: 1;
  }

  .product-details h3,
  .product-details p {
    transform: translateY(20px);
  }

  .product-image-wrapper:hover .product-details h3,
  .product-image-wrapper:hover .product-details p {
    transform: translateY(0);
  }
}

@media (max-width: 991px) {
  .product-image-wrapper {
    aspect-ratio: 16/9;
  }
}

@media (max-width: 768px) {
  .section-description {
    font-size: 1rem;
    margin-bottom: 2rem;
  }
  
  .product-details {
    padding: 1.5rem;
  }
  
  .product-details h3 {
    font-size: 1.25rem;
  }
  
  .product-details p {
    font-size: 0.9rem;
  }
}

@media (hover: hover) {
  .product-image-wrapper:hover .product-image {
    transform: scale(1.1);
  }
}

.technology-section {
  background-color: #ffffff;
  padding: 100px 0;
}

.technology-slider {
  margin-top: 3rem;
}

.technology-swiper {
  padding: 2rem 0;
}

.technology-slide {
  background: #ffffff;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  height: 100%;
}

.slide-image {
  position: relative;
  height: 400px;
  overflow: hidden;
}

.slide-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.slide-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(
    to bottom,
    rgba(0,0,0,0.2),
    rgba(0,0,0,0.1)
  );
}

.slide-content {
  padding: 2rem;
}

.slide-content h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1.5rem;
  font-weight: 700;
  color: #2c3e50;
  margin-bottom: 1rem;
}

.slide-content p {
  font-family: 'Roboto', sans-serif;
  font-size: 1rem;
  color: #666;
  line-height: 1.6;
  margin: 0;
  font-weight: 300;
}

.swiper-pagination-bullet {
  width: 12px;
  height: 12px;
  background: #4CAF50;
  opacity: 0.5;
}

.swiper-pagination-bullet-active {
  opacity: 1;
}

.swiper-button-next,
.swiper-button-prev {
  color: #4CAF50;
}

@media (max-width: 991px) {
  .slide-image {
    height: 300px;
  }
}

@media (max-width: 768px) {
  .slide-image {
    height: 250px;
  }
  
  .slide-content {
    padding: 1.5rem;
  }
  
  .slide-content h3 {
    font-size: 1.25rem;
  }
  
  .slide-content p {
    font-size: 0.9rem;
  }
}

.testimonials-section {
  background-color: #fff5f5;
  padding: 100px 0;
}

.testimonials-slider {
  margin-top: 3rem;
}

.testimonials-swiper {
  padding: 2rem 0;
}

.testimonial-card {
  background: #ffffff;
  border-radius: 15px;
  padding: 3rem 2rem;
  margin: 1rem;
  box-shadow: 0 10px 30px rgba(0,0,0,0.05);
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  transition: all 0.3s ease;
}

.testimonial-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 40px rgba(0,0,0,0.1);
}

.testimonial-content {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
}

.testimonial-content i {
  font-size: 3rem;
  color: #4CAF50;
  opacity: 0.2;
  position: absolute;
  top: -20px;
  left: -20px;
}

.testimonial-text {
  font-family: 'Playfair Display', serif;
  font-size: 1.25rem;
  color: #2c3e50;
  line-height: 1.8;
  margin-bottom: 2rem;
  font-style: italic;
}

.testimonial-author {
  margin-top: 2rem;
}

.author-name {
  font-family: 'Montserrat', sans-serif;
  font-size: 1.1rem;
  font-weight: 600;
  color: #4CAF50;
}

@media (max-width: 768px) {
  .testimonial-card {
    padding: 2rem 1.5rem;
  }
  
 .testimonial-text {
    font-size: 1.1rem;
  }
  
  .author-name {
    font-size: 1rem;
  }
  
  .testimonial-content i {
    font-size: 2.5rem;
    top: -15px;
    left: -15px;
  }
}

.contact-section {
  background-color: #ffffff;
  padding: 100px 0;
}

.contact-wrapper {
  background: #ffffff;
  border-radius: 15px;
  padding: 3rem;
  box-shadow: 0 10px 30px rgba(0,0,0,0.05);
}

.contact-info {
  padding-right: 2rem;
}

.contact-info h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1.5rem;
  font-weight: 700;
  color: #2c3e50;
  margin-bottom: 2rem;
}

.contact-items {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.contact-item {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
}

.contact-item i {
  font-size: 1.5rem;
  color: #4CAF50;
  margin-top: 0.25rem;
}

.contact-details h4 {
  font-family: 'Montserrat', sans-serif;
  font-size: 1.1rem;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 0.5rem;
}

.contact-details p {
  font-family: 'Roboto', sans-serif;
  font-size: 1rem;
  color: #666;
  margin: 0;
  font-weight: 300;
}

.contact-form {
  padding-left: 2rem;
}

.form-group {
  margin-bottom: 1.5rem;
}

.form-control {
  padding: 0.8rem 1rem;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  font-size: 1rem;
  transition: all 0.3s ease;
}

.form-control:focus {
  border-color: #4CAF50;
  box-shadow: 0 0 0 0.2rem rgba(76, 175, 80, 0.25);
}

.contact-form .btn-primary {
  padding: 1rem;
  font-size: 1.1rem;
  text-transform: uppercase;
  letter-spacing: 1px;
}

@media (max-width: 991px) {
  .contact-info {
    padding-right: 0;
    margin-bottom: 2rem;
  }
  
  .contact-form {
    padding-left: 0;
  }
}

@media (max-width: 768px) {
  .contact-wrapper {
    padding: 2rem;
  }
  
  .contact-info h3 {
    font-size: 1.3rem;
  }
  
  .contact-details h4 {
    font-size: 1rem;
  }
  
  .contact-details p {
    font-size: 0.9rem;
  }
  
  .form-control {
    padding: 0.7rem 1rem;
    font-size: 0.9rem;
  }
  
  .contact-form .btn-primary {
    padding: 0.8rem;
    font-size: 1rem;
  }
}

.footer {
  background-color: #2c3e50;
  color: #ffffff;
  padding: 4rem 0 2rem;
  margin: 20px;
  border-radius: 20px;
}

.footer-brand h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: #ffffff;
}

.footer-brand p {
  color: rgba(255, 255, 255, 0.8);
  font-size: 1rem;
  margin: 0;
}

.footer h4 {
  font-family: 'Montserrat', sans-serif;
  font-size: 1.2rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  color: #ffffff;
}

.footer-links {
  list-style: none;
  padding: 0;
  margin: 0;
}

.footer-links li {
  margin-bottom: 0.8rem;
}

.footer-links a {
  font-family: 'Roboto', sans-serif;
  color: rgba(255, 255, 255, 0.8);
  text-decoration: none;
  transition: color 0.3s ease;
  font-weight: 300;
}

.footer-links a:hover {
  color: #4CAF50;
}

.footer-contact {
  list-style: none;
  padding: 0;
  margin: 0;
}

.footer-contact li {
  font-family: 'Roboto', sans-serif;
  color: rgba(255, 255, 255, 0.8);
  margin-bottom: 1rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-weight: 300;
}

.footer-contact i {
  color: #4CAF50;
}

.social-links {
  display: flex;
  gap: 1rem;
}

.social-link {
  width: 40px;
  height: 40px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #ffffff;
  text-decoration: none;
  transition: all 0.3s ease;
}

.social-link:hover {
  background: #4CAF50;
  transform: translateY(-3px);
}

.footer-bottom {
  margin-top: 3rem;
  padding-top: 2rem;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  text-align: center;
}

.footer-bottom p {
  font-family: 'Roboto', sans-serif;
  color: rgba(255, 255, 255, 0.6);
  margin: 0;
  font-size: 0.9rem;
  font-weight: 300;
}

@media (max-width: 991px) {
  .footer {
    padding: 3rem 0 1.5rem;
  }
  
  .footer-brand h3 {
    font-size: 1.3rem;
  }
}

@media (max-width: 768px) {
  .footer {
    margin: 10px;
    padding: 2rem 0 1rem;
  }
  
  .footer h4 {
    font-size: 1.1rem;
    margin-bottom: 1rem;
  }
  
  .footer-brand h3 {
    font-size: 1.2rem;
  }
  
  .footer-contact li {
    font-size: 0.9rem;
  }
  
  .social-link {
    width: 35px;
    height: 35px;
  }
}
</style> 