<!-- Use preprocessors via the lang attribute! e.g. <template lang="pug"> -->
  <template>
    <div id="app">
      <div class='loader df aic jcc'>
        <div>
          <h1>Loading</h1>
          <h2 class='loader--text'>0%</h2>
        </div>
      </div>
      <div class='demo-wrapper'>
        <header class='df aic jcc'>
          <div>
            <h1>African </h1>
            <h2>Inspiration</h2>
          </div>
        </header>
        <section class='demo-text'>
          <div class='wrapper text'>
            INSPIRATION
          </div>
        </section>
        <section class='demo-gallery'>
          <ul class='wrapper'>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=157' width='1240'>
            </li>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=56' width='1240'>
            </li>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=158' width='1240'>
            </li>
          </ul>
        </section>
        <section class='demo-gallery'>
          <ul class='wrapper'>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=71' width='1240'>
            </li>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=3' width='1240'>
            </li>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=119' width='1240'>
            </li>
          </ul>
        </section>
        <section class='demo-text'>
          <div class='wrapper text'>
            AFRICAN
          </div>
        </section>
      
        <section class='demo-gallery'>
          <ul class='wrapper'>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=30' width='1240'>
            </li>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=112' width='1240'>
            </li>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=6' width='1240'>
            </li>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=142' width='1240'>
            </li>
          </ul>
        </section>
        <section class='demo-text'>
          <div class='wrapper text'>
            INSPIRATION
          </div>
        </section>
      
        <section class='demo-gallery'>
          <ul class='wrapper'>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=199' width='1240'>
            </li>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=159' width='1240'>
            </li>
            <li>
              <img height='874' src='https://source.unsplash.com/random/1240x874?sig=5' width='1240'>
            </li>
          </ul>
        </section>
        <section class='demo-text'>
          <div class='wrapper text'>
            AFRICAN
          </div>
        </section>
        <footer class='df aic jcc'>
          <p>Images from <a href="https://unsplash.com/">Unsplash</a></p>
        </footer>
      </div>
        
    </div>
  </template>
  
  <script>
  import { gsap } from 'gsap'
  export default {
    mounted: function() {
      this.scrollAnimation();
    },
    methods: {
      scrollAnimation() {
        gsap.to(".box", {
  scrollTrigger: ".box", // start the animation when ".box" enters the viewport (once)
  x: 500
})
      },
    }
  };

  </script>
  <style>
  h2 {
    margin-top: 200px;
    margin-bottom: 200px;
  }
  </style>