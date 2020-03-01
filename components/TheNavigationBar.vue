<template>
  <nav>
    <div class="container">
      <ul class="nav-links">
        <nuxt-link to="/browse">
          <li>Browse</li>
        </nuxt-link>
        <nuxt-link to="/helper">
          <li>Help me choose</li>
        </nuxt-link>
        <nuxt-link to="/about">
          <li>About</li>
        </nuxt-link>
      </ul>
      <div class="signing">
        <nuxt-link to="/login">Log in</nuxt-link>
        <button class="sign-up">Sign up</button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavigationBar'
}
</script>

<style lang="scss" scoped>
nav {
  background-color: navy;
  .container {
    margin: 0 auto;
    max-width: 1080px;
    display: flex;
    justify-content: space-between;
    padding: 1rem 1rem;
    align-items: center;
    font-size: 16px;

    .nav-links,
    .signing {
      display: flex;
      align-items: center;
      text-decoration: none;
      list-style: none;

      > a {
        color: white;
        text-decoration: none;
        margin-right: 1rem;
        height: 100%;
      }
    }

    .sign-up {
      font-size: 16px;
      padding: 5px 15px;
      background-color: white;
      border-radius: 15px;
      border: none;
      cursor: pointer;
    }
  }
}
</style>
