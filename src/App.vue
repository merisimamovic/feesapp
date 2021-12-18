<template>
  <Nav />
  <Main />
</template>

<script>
import Main from './components/Main.vue'
import Nav from './components/Nav.vue'

export default {
  name: 'App',
  components: {
    Main,
    Nav
  }
}
</script>

<style>
@font-face {
  font-family: "Objectivity-Regular";
  src: local("Objectivity-Regular"), url(./fonts/Objectivity-Regular.woff2) format("woff2");
}
@font-face {
  font-family: "Objectivity-Bold";
  src: local("Objectivity-Bold"), url(./fonts/Objectivity-Bold.woff2) format("woff2");
}
@font-face {
  font-family: "Objectivity-Medium";
  src: local("Objectivity-Medium"), url(./fonts/Objectivity-Medium.woff2) format("woff2");
}

#app {
  font-family: Objectivity-Regular ,Avenir, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

:root {
  --blue: #0669F8;
  --bluehover: #0F56BD;
  --dark: #182B47;
  --light: #8A99AE;
}

* {
    margin: 0;
    padding:0;
    box-sizing: border-box;
}

body {
    font-family: sans-serif;
    color: var(--dark);
    line-height: 1.3;
}

h1, h2, h3, h4, h5, h6 {
    font-family: Objectivity-Bold, Avanir, sans-serif;
}

h1 {
  font-size: 40px;
}

h5 {
  font-size: 20px;
}

a, a:active {
    color: inherit;
    text-decoration: none;
}

.nav__menu{
    display: flex;
    gap: 40px;
    align-items: center;
}

ul li {
    list-style-type: none;
    text-indent: 0;
    text-decoration: none;
}

.nav {
    height: 10vh;
    width: 100%;
    display: flex;
    align-items: center;
    position: relative;
}

.max-width {
    width: 1440px;
    margin: 0 auto;
}

.nav__wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.btn-ghost {
    padding: 16px 24px;
    border-radius: 12px;
    border: 2px solid #0669F8;
    background: white;
    transition: all 300ms ease-in-out;
    font-family: Objectivity-Bold, Avanir, sans-serif;
}

.btn-ghost:hover {
    background-color: var(--blue);
    color: white;
}

.btn-primary {
padding: 16px 24px;
font-size: 20px;
border-radius: 12px;
border: 2px solid #0669F8;
background: var(--blue);
color: #fff;
transition: all 300ms ease-in-out;
font-family: Objectivity-Bold, Avanir, sans-serif;
}

.btn-primary:hover {
    background-color: var(--bluehover);
}

.btn-secondary {
padding: 16px 24px;
font-size: 20px;
border-radius: 12px;
border: 2px solid var(--light);
background: #fff;
transition: all 300ms ease-in-out;
font-family: Objectivity-Bold, Avanir, sans-serif;

}

.btn-secondary:hover {
    background-color: var(--dark);
    border-color: var(--dark);
    color: #fff;
}

.logo {
    width: 140px;
    height: auto;
}

.mr-8 {
  margin-right: 8px;
}

.line {
    height: 1px;
    width: 100%;
    background: #8A99AE;
    opacity: 0.2;
    position: absolute;
    bottom: 5%;
    left: 0;
    right: 0;
}
.option {
  text-align: left;
}

input[type='radio'][name='buttonGroup'] { display:none; }
label {
  display:inline-block;
  padding: 16px 24px;
  border:2px solid var(--light);
  border-radius: 16px;
  background-color:#fff;
  text-align:center;
  color: var(--dark);
  font-size: 20px;
  cursor: pointer;
}

.mb-8{
    margin-bottom: 8px;
}

input[type='radio'][name='buttonGroup']:checked + label { background-color: var(--dark); color: #fff; border-color: var(--dark);}

.form {
    border: 2px solid var(--light);
    padding: 40px;
    border-radius: 24px;
    display: flex;
    width: 100%;
    justify-content: space-between;
    background: white;
    margin-top: 0.5rem;
    margin-bottom: 5rem;
}

.input {
    outline: 0;
    border-width: 0 0 2px;
    border-bottom: 1px solid #bdbcbc;
    font-size: 32px;
    width: 150px;
}

.input::placeholder {
    color: #e4e2e2;
}

.text-sm {
    font-size: 14px;
}

.btn-group {
    display: flex;
    gap: 16px;
    align-items: center;
    display: inline-block;
    margin-top: 32px;
}

.hero{
    height: 90vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: relative;
}

.flex-c {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.form-group {
    display: flex;
    align-items: flex-start;
    flex-direction: column;
    width: 846px;
    margin: 0 auto;
}

.nav__inner {
    display: flex;
    gap: 40px;
    align-items: center;
}

.w-50 {
    width: 50%;
    display: inline-block;
    margin-bottom: 2rem;
}

.bg-img {
    position: absolute;
    bottom: 0;
    left: 0;
    z-index: -1;
}
</style>
