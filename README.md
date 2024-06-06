# Responsive Card Slider
## [Watch it on youtube](https://youtu.be/b71OeOAEQrQ)
### Responsive Card Slider

- Responsive Card Slider Using HTML CSS & JavaScript
- It contains beautiful cards in dark mode and 3D images.
- Slider images with Swiper Js.
- Developed first with the Mobile First methodology, then for desktop.
- Compatible with all mobile devices and with a beautiful and pleasant user interface.

💙 Join the channel to see more videos like this. [Bedimcode](https://www.youtube.com/@Bedimcode)

![preview img](/preview.png)


parte importante para fazer o card slider 
## html 
````html 
                  <div class="card__container swiper">
            <div class="card__content ">
               <div class="swiper-wrapper">
                  <article class="card__article swiper-slide">
                     <div class="card__image">
                        <img src="assets/img/avatar-1.png" alt="" class="card__img">
                        <div class="card__shadow"></div>
                     </div>
                     <div class="card__data">
                        <h3 class="card__name">Lorem, ipsum dolor.</h3>
                        <p class="card__description">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ratione, assumenda! Nobis molestiae deserunt at reprehenderit.</p>
                        <a href="#" class="card__button">view more</a>
                     </div>
                  </article>
                  <article class="card__article swiper-slide">
                     <div class="card__image">
                        <img src="assets/img/avatar-2.png" alt="" class="card__img">
                        <div class="card__shadow"></div>
                     </div>
                     <div class="card__data">
                        <h3 class="card__name">Lorem, ipsum dolor.</h3>
                        <p class="card__description">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ratione, assumenda! Nobis molestiae deserunt at reprehenderit.</p>
                        <a href="#" class="card__button">view more</a>
                     </div>
                  </article>
                  <article class="card__article swiper-slide">
                     <div class="card__image">
                        <img src="assets/img/avatar-3.png" alt="" class="card__img">
                        <div class="card__shadow"></div>
                     </div>
                     <div class="card__data">
                        <h3 class="card__name">Lorem, ipsum dolor.</h3>
                        <p class="card__description">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ratione, assumenda! Nobis molestiae deserunt at reprehenderit.</p>
                        <a href="#" class="card__button">view more</a>
                     </div>
                  </article>
                  <article class="card__article swiper-slide">
                     <div class="card__image">
                        <img src="assets/img/avatar-4.png" alt="" class="card__img">
                        <div class="card__shadow"></div>
                     </div>
                     <div class="card__data">
                        <h3 class="card__name">Lorem, ipsum dolor.</h3>
                        <p class="card__description">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ratione, assumenda! Nobis molestiae deserunt at reprehenderit.</p>
                        <a href="#" class="card__button ">view more</a>
                     </div>
                  </article>
               </div>
            </div>
         </div>
````

## css
 ````css
 .card__container{
  padding-block: 5rem;
}

.card__content{
  margin-inline: 1.75rem;
  border-radius: 1.25rem;
  overflow: hidden;
}

.card__article{
  width: 300px;
  border-radius: 1.25rem;
  overflow: hidden;
}
 ````

 ## js 
 ````js
 let swiperCards = new Swiper(".card__content", {
  loop: true,
  spaceBetween: 32,
  grabCursor: true,

  pagination: {
    el: ".swiper-pagination",
    clickable: true,
    dynamicBullets: true,
  },

  navigation: {
    nextEl: ".swiper-button-next",
    prevEl: ".swiper-button-prev",
  },

  breakpoints:{
    600: {
      slidesPerView: 2,
    },
    968: {
      slidesPerView: 3,
    },
  },
});
 ````

 15:11