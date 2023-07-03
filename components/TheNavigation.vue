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
  padding: 2px 0 2px 12px;
  margin: 30px 29rem 0 29rem;
  display: flex;
  background-color: #696969;
  border-radius: 50px;
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