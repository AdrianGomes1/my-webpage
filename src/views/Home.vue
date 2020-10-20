<template>
  <div class="home">
    <body>
      <div class='topbar'>
        <div class="buttons">
          <button id='Home' @click="$router.push({'path' : '/'})">Home</button>
          <button id='About' @click="$router.push('about')">About</button>
          <button id='Contacts'>Contacts</button>
          <button id='Works'>Works</button>
        </div>
        <p id='LocalTime'></p>
      </div>
      <div class='typedText'>
        <h1 id='heading'>Welcome to my Page!</h1>
      </div>
      <p id='Desc'>
      This is a page that includes all of my works as a developer such as websites, games, or apps
      the github link of each work will be attached to it
      </p>
    </body>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Home',
}
</script>
