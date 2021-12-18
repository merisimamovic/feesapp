<template>
    <nav class="nav">
        <div class="max-width  flex nav__wrapper">
            <div class="nav__inner">
                <img src="./img/logo.svg" alt="" class="logo">
                <ul class="nav__menu">
                    <li><a href="#">Uporedi transfer</a></li>
                    <li><a href="#">Opskrba voljenih</a></li>
                    <li><a href="#">Savjeti</a></li>
                    <li><a href="#">Pitanja</a></li>
                    <li><a href="#">O nama</a></li>
                </ul>
            </div>
            <a href="#" class="btn-ghost">Registruj se</a>
        </div>
        <div class="line"></div>
    </nav>

</template>

<script>
export default {
  name: 'Nav',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
