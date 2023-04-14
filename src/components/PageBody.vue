<template>
  <div >

    <section  class="boddy">
          <article>
      <h1>Kenyan food</h1>
    </article>

      <article>
        <img
          src="http://farm3.static.flickr.com/2038/5735687549_8f85d0acc0_o.jpg"
          alt=""
        />
        <h3>Sukuma Wiki (Collard Greens / Kale)</h3>
        <p>
          One of the most popular vegetable Kenyan dishes is sukuma wiki (known
          as collard greens or a form of kale in English).
        </p>
      </article>

      <article>
        <img
          src="http://farm6.static.flickr.com/5302/5735688337_5308583847_o.jpg"
          alt=""
        />
        <h3> Chapati (Flatbread)</h3>
        
        <p>
          Chapatis in Kenya can trace their origin from the influence of the
          Indian population. Kenyan style chapatis are made with a flour dough
          that is wound into a coil before being rolled into a flat round
          circle. The dough is then fried on a skillet accompanied by plenty of
          oil so it becomes crispy on the edges but remains moist and doughy on
          the interior.
        </p>
      </article>

<article>
   <img src="https://migrationology.com/wp-content/uploads/2011/05/mandazi.jpg" alt="">
    <h3> Mandazi (Kenyan Doughnut)</h3>
    <p>They can be smelled from a kilometer down the street, that lovely familiar scent of a blob of deep frying dough.</p>
</article>

    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
img {
    margin: 10px;
    max-width: 400px;
}
div{
  display: grid;
  grid-template-rows: 1fr 1fr 1fr;
  background-color: aqua;
  margin-bottom: 0px;
}
.boddy{
  display: grid;
  place-items: center;

}
p{
  text-align: center;
  max-width: 400px;
}


</style>