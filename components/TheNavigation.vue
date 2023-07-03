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
  padding: 2px 0 2px 0;
  margin: 30px 23% 0 23%;
  display: flex;
  background-color: #696969;
  border-radius: 50px;
  justify-content: center;
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