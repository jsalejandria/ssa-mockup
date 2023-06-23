<template>
  <div class="action">
    <div class="action__description">
      <h1>Last Call to Action</h1>
      <div class="action__description--statement">
        <p>Another section content goes here</p>
      </div>
    </div>
    <div class="action__container">
      <div class="action__card">
        <div class="action__card--left">
          <img src="../assets/badge.laravel-mix.svg" alt="" />
          <button>AUTOMATION</button>
        </div>
        <div class="action__card--right">
          <p class="action__card--right-intro">ROLL OUT</p>
          <h2>Automatic Prototyping</h2>
          <p>
            Webpack is the most powerful and flexible asset compilation tool
            available today. With that power, however, comes a certain level of
            complexity.
          </p>
        </div>
      </div>
      <div class="action__card-2">
        <div class="action__card-2--left">
          <img src="../assets/badge.how-to-read-code.svg" alt="" />
          <button>SIMPLICITY</button>
        </div>
        <div class="action__card--right">
          <p class="action__card--right-intro">SIP COFFEE</p>
          <h2>Complexity <br />Simplified</h2>
          <p>
            I know too many backend developers who are stifled by one glaring
            phobia: CSS. How do you construct a layout when nothing lines up?
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Action",
};
</script>
