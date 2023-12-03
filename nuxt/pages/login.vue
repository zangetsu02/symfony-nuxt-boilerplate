<script setup lang="ts">

const form = ref({
    email: "",
    password: ""
})

function handleLogin() {

}

</script>

<template>
    <form @submit.prevent="handleLogin">
        <label for="email">
            Email
            <input name="email" type="email" v-model="form.email">
        </label>
        <label for="password">
            Password
            <input name="password" type="password" v-model="form.password">
        </label>

        <button>Login</button>

    </form>
</template>