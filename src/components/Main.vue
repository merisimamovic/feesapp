<template>
        <section class="hero">
            <img src="../assets/img1.png" class="bg-img" alt="">
            <div class="max-width flex-c">

                <h1 class="w-50">Pronađite najpogodniji način slanja novca u Bosnu i Hercegovinu</h1>
                
                <div class="form-group">

                    <div class="radio-group">
                        <input type="radio" name="buttonGroup" value="one" id="one"><label for="one" class="mr-8">Najbrže</label>
                        <input type="radio" name="buttonGroup" value="two" id="two"><label for="two" class="mr-8">Najjeftinije</label>
                    </div>

                    <div class="form">

                        <div class="option">
                            <p class="text-sm mb-8">Slanje iz</p>
                            <h5>Njemačka</h5>
                        </div>

                        <div class="option">
                            <p class="text-sm mb-8">Slanje u</p>
                            <h5>Bosna i Hercegovina</h5>
                        </div>

                        <div class="option">
                            <p class="text-sm mb-8">Unesite iznos</p>
                            <input placeholder="0,00" class="input" type="text">
                        </div>
                
                        <a href="https://www.figma.com/proto/1Pv26rZNYSL0mh6TNul1wV/Feesless?node-id=1%3A7&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=1%3A7" class="btn-primary">Uporedi</a>

                    </div>
                
                </div>

                <h1 class="mb-8">Opskrbite svoje voljene</h1>
                <div class="btn-group">
                    <a href="#" class="btn-secondary mr-8">Pokloni</a>
                    <a href="#" class="btn-secondary mr-8">Namirnice</a>
                    <a href="#" class="btn-secondary mr-8">Zdravstvene usluge</a>
                    <a href="#" class="btn-secondary">Lijekovi</a>
                </div>
            </div>
        </section>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
