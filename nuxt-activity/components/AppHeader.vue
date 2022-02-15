<template>
    <nav class="nav">
        <ul>
            <li>
                <nuxt-link to='/'>Home</nuxt-link>
            </li>
            <li>
                <nuxt-link to='/about'>About</nuxt-link>
            </li>
            <li>
                <nuxt-link to='/contact'>Contact</nuxt-link>
            </li>
        </ul> 
    </nav>
</template>

<script>
export default {
    name: 'AppHeader'
}
</script>

<style>
    .nav {
    height: 50px;
    padding: 10px;
    background: #000;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }
  
  .nav ul {
    display: flex;
    justify-content: center;
    align-items: center;
    list-style: none;
    color: #fff;
  }
  
  .nav ul li a {
    margin: 5px 15px;
    color: #fff;
  }
</style>