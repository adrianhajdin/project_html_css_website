@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700;800;900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@200;300;400;500;600;700;800&display=swap");

/* other css file imports */
@import url("sections/header.css");
@import url("sections/hero.css");
@import url("sections/about.css");
@import url("sections/popular.css");
@import url("sections/trending.css");
@import url("sections/subscribe.css");
@import url("sections/footer.css");

/* CSS variables for reusablity across all files (including above imported) */
:root {
  --playfair-display: "Playfair Display", serif;
  --plus-jakarta-sans: "Plus Jakarta Sans", sans-serif;

  --primary-color: #b1454a;
  --secondary-color: #121212;

  --black-200: #020202;
  --black-300: #333333;
  --black-400: #1f1e31;
  --black-500: #555555;
  --gray-100: #888888;

  --color-white: #fff;
  --color-creamson: #fff0de;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  max-width: 1280px;
  margin: 0 auto;
  background-color: var(--color-creamson);
}

a {
  text-decoration: none;
  color: inherit;
}


.flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}

.flex-between {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.sushi__subtitle {
  font-size: 18px;
  font-weight: 400;
  font-family: var(--plus-jakarta-sans);

  color: var(--primary-color);
  opacity: 0.8;

  letter-spacing: -0.01em;
}

.sushi__title {
  font-size: 64px;
  font-weight: 600;
  font-family: var(--playfair-display);

  color: var(--secondary-color);

  margin-top: 16px;
}

.sushi__description {
  font-size: 18px;
  font-weight: 400;
  font-family: var(--plus-jakarta-sans);

  line-height: 36px;
  letter-spacing: -0.01em;

  color: var(--secondary-color);
  opacity: 0.8;

  margin: 32px 0px;
}

/* Hide scrollbar for Chrome, Safari and Opera */
.sushi__hide-scrollbar::-webkit-scrollbar {
  display: none;
}

/* Hide scrollbar for IE, Edge and Firefox */
.sushi__hide-scrollbar {
  -ms-overflow-style: none; /* IE and Edge */
  scrollbar-width: none; /* Firefox */
}

/* START: about us media queries */
@media screen and (max-width: 1024px) {
  .about-us {
    flex-direction: column;
  }

  .about-us__image {
    flex-direction: row;
  }

  .about-us__image-sushi3 {
    border-bottom: none;
    border-right: 8px solid var(--color-creamson);
  }

  .about-us__button {
    display: none;
  }
}

@media screen and (max-width: 750px) {
  .about-us__image {
    flex-direction: column;
  }

  .about-us__image-sushi3 {
    border-bottom: 8px solid var(--color-creamson);
    border-right: none;
  }

  .about-us__button {
    display: block;
    top: 47%;
  }
}

@media screen and (max-width: 550px) {
  .about-us__image-sushi2 img,
  .about-us__image-sushi3 img {
    width: 50%;
    height: 160px;

    object-fit: contain;
  }

  .about-us__image div {
    padding: 32px;
  }

  .about-us__button {
    top: 44%;
  }

  .about-us__content {
    padding: 32px;
  }
}
/* END: about us media queries */


/* START: header media querie */
@media screen and (max-width: 900px) {
  .header__nav {
    background: var(--primary-color);
  }

  .header__menu {
    display: none;
  }

  .header__menu-mobile {
    display: flex;
  }
}

@media screen and (max-width: 550px) {
  .header__logo {
    padding-left: 0;
  }
}
/* END: header media queries */

/* START: hero media queries */
@media screen and (max-width: 1060px) {
  .hero {
    flex-direction: column;
  }

  .hero-image img {
    width: 100%;

    transform: matrix(1, 0.05, 0, 1.25, 0, 0) !important;
  }
}

@media screen and (max-width: 750px) {
  .hero-image h2 {
    font-size: 70px;
    line-height: 90px;
  }
}

@media screen and (max-width: 550px) {
  .hero-image h2 {
    font-size: 40px;
    line-height: 60px;
  }

  .hero-content-info {
    padding: 32px;
  }

  .hero-content-info h1 {
    font-size: 60px;
  }

  .hero-content-info p {
    margin: 32px 0;
  }

  .hero-content__buttons {
    margin: 41px 0;
  }

  .hero-content__testimonial {
    padding: 32px;
  }
}
/* END: hero media queries */

/* START: popular media queries */
@media screen and (max-width: 550px) {
  .popular-foods {
    padding: 64px 32px;
  }

  .popular-foods__card,
  .popular-foods__card.active-card {
    min-width: 100%;
  }
}
/* END: popular media queries */

/* START: subscribe media queries */
@media screen and (max-width: 550px) {
  .subscription {
    padding: 64px 32px;
  }

  .subscription h2 {
    font-size: 68px;
    line-height: 100px;
  }

  .subscription__form {
    flex-direction: column;
    gap: 20px;

    min-width: 100%;
    border-radius: 20px;
    padding: 0;

    border: none;
  }

  .subscription__form input {
    min-height: 50px;

    border: 1px solid rgba(255, 255, 255, 0.5);
    padding: 10px 20px;
    border-radius: 30px;
  }

  .subscription__form button {
    min-width: 100%;
  }
}
/* END: subscribe media queries */

/* START: trending media queries */
@media screen and (max-width: 1024px) {
  .trending-sushi {
    flex-direction: column;
  }

  .trending-drink {
    flex-direction: column-reverse;
  }

  .trending__image {
    width: 100%;
    background-size: cover;
  }

  .trending__discover {
    display: none;
  }

  .trending__arrow {
    display: none;
  }
}

@media screen and (max-width: 550px) {
  .trending__image img {
    width: 70%;
    height: 70%;
  }

  .trending__content {
    padding: 32px;
  }
}
/* END: trending media queries */