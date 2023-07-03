<template>
  <div>
    <ul>
      <li>
        <nuxt-link to="/">anytime</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about_us">про нас</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/blog">блог</nuxt-link>
      </li>
      <li>
        <nuxt-link to="news">новости</nuxt-link>
      </li>
      <li>
        <nuxt-link to="registration">регистрация</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<style>
ul {
  list-style: none;
  padding: 20px;
  margin: 0 0 0 30rem;
  display: flex
}

ul li {
  margin: 20px;
}

ul li a {
  font-size: 40px;
  text-decoration: none;
  color: white;
}

ul li a:hover {
  text-decoration: underline;
}
</style>