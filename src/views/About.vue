<template>
  <div class="about">
    <body>
      <div class="buttons">
          <button id='Home' @click="$router.push({'path' : '/'})">Home</button>
          <button id='About' @click="$router.push('about')">About</button>
          <button id='Contacts'>Contacts</button>
          <button id='Works'>Works</button>
      </div>
    </body>
  </div>
</template>
