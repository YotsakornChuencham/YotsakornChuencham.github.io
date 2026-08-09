<template>
    <h1>Index pages </h1>
    <p>
        <span>Name: </span>
        <span>{{ name }}</span>
    </p>
    <bottom @click="handleClick('worked')"> rename </bottom>
</template>
    <bottom @click="handleShowLogName">console.log </bottom>

<script setup>
const name = ref("init")

const handleClick = () => {
    console.log('worked form handleClick function')

    name.nalue = "yotsakorn"
}
</script>