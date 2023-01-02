<template>
  <div>
    <carousel>
      <slide>
        <div class="testimonial-info">
          <h2>HAPPY PEOPLE'S</h2>
          <h1>TESTIMONIALS</h1>
        </div>

        <div class="tes-comments">
          <div class="frame-com-slider">
            <p>
              Nullam orci dui, dictum magna <br />
              sollicitudin, blandit erat. <br />
              Maecenas suscipit tellus sit amet augue <br />
              placerat fringilla a id lacus. Fusce tincidunt <br />
              in leo lacinia condimentum.
            </p>
            <font class="fa-quote-left" :icon="['fas', 'quote-left']" />
            <h4>ANASTASIA STONE</h4>
            <img id="img" src="~@/assets/team-2.jpg" alt="Member-1" />
          </div>

          <div class="frame-com-slider">
            <p>
              Suspendisse sed lacinia <br />
              pretium. Phasellus eros ligula, mattis id <br />
              rutrum non, dictim ture eleifend vitae lacus.
            </p>
            <div class="error-place">
              <font class="fa-quote-left" :icon="['fas', 'quote-left']" />
              <h4>STEVEN RASHFORD</h4>
              <img id="img" src="~@/assets/team-3.jpg" alt="Member-2" />
            </div>
          </div>

          <div class="frame-com-slider">
            <p>
              Quisque sollicitudin feugiat risus, eu <br />
              posuere ex euismod eu. Phasellus <br />
              hendrerit, massa efficitur dapibus <br />
              pulvinar, sapien eros sodales ante, <br />
              euismod aliquet ture nulla metus a mauris.
            </p>
            <font class="fa-quote-left" :icon="['fas', 'quote-left']" />
            <h4>Elena Korovskiy</h4>
            <img id="img" src="~@/assets/team-4.jpg" alt="Member-3" />
          </div>
        </div>
      </slide>
    </carousel>
  </div>
</template>
<style>
.header-testimonial {
  background: #f5f5f5;
}

.testimonial-info h2 {
  text-align: center;
  padding-top: 82px;
  color: #ffc61a;
  font-size: 24px;
  font-family: "Fira Sans Condensed", sans-serif;
}

.testimonial-info h1 {
  text-align: center;
  font-family: "Fira Sans Condensed", sans-serif;
  /*    line-height: 1.4;*/
  font-size: 39px;
  font-weight: 700;
  padding-bottom: 15px;
}

.tes-comments {
  display: flex;
  justify-content: center;
  text-align: center;
}

.frame-com-slider {
  background: #ffffff;
  margin: 20px;
  padding: 25px;
  border-radius: 5px;
  animation: boxShadow 1.5s ease-in infinite;
}

@keyframes boxShadow {
    0% {
      box-shadow: 0 7px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0);
    }
    50% {
      box-shadow: 0 12px 19px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0);
    }
    75% {
      box-shadow: 0 10px 21px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0);
    }
    100% {
    box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0);
    }
}

.frame-com-slider p {
  font-size: 16px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  margin-top: 20px;
  color: #6b5e5e;
  line-height: 1.6em;
  font-style: italic;
}

.frame-com-slider #img {
  width: 22%;
  border-radius: 100%;
  margin-bottom: -65px;
  z-index: 2;
}

.frame-com-slider .error-place {
  margin-top: 50px;
}

.frame-com-slider .fa-quote-left {
  margin-top: 25px;
  margin-bottom: 20px;
  color: #e6e6e6;
  font-size: 36px;
}

.frame-com-slider h4 {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 15px;
  line-height: 1.6em;
  color: #0E0E0E;
}

#tes-icons {
  display: flex;
  justify-content: center;
  margin-top: 40px;
}

#tes-icons a,
#tes-icons a {
  background: #ffc61a;
  font-size: 19px;
  color: white;
  margin: 0 4px;
  padding: 7px 12px;
  border-radius: 4px;
  transition: all 0.2s ease;
}

#tes-icons a:hover,
#tes-icons a:hover {
  background: #1f1f1f;
}

.offer-images {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 115px;
}

.our-partners-paragraph h3 {
  padding-left: 50px;
  padding-top: 9px;
}

.our-partners-paragraph .black {
  color: #1f1f1f;
  font-size: 22px;
  font-family: "Fjalla One", sans-serif;
}

.our-partners-paragraph .white {
  color: white;
  font-size: 32px;
  font-family: "Fjalla One", sans-serif;
}

.our-partners-block {
  background: #ffc61a;
  margin-top: -4px;
  padding: 42px;
  display: flex;
}

.frame-com-slider {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0);
}

.partners-head-img #img {
  padding-left: 60px;
  padding-right: 55px;
}
</style>
