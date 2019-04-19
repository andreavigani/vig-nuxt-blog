<template>
<form name="contact" method="POST" netlify-honeypot="bot-field" data-netlify-recaptcha="true" data-netlify="true">
    <p class="hidden">
        <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
    </p>
    <p>
        <label>Name <input type="text" name="name" /></label>
    </p>
    <p>
        <label>Email <input type="email" name="email" /></label>
    </p>
    <p>
        <label>Message: <textarea name="message"></textarea></label>
    </p>
    <div data-netlify-recaptcha="true"></div>
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