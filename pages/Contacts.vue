<template>
<form name="contact" method="POST" netlify>
  <p>
    <label>Name <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Email <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
</template>
<script>
export default {
  name: 'Contacts'
}
</script>
<style>
form {
    padding: 4rem;
}
input {
    border: 1px solid blue;
}
button {
    background-color: blue;
    color: #fff;
}
</style>