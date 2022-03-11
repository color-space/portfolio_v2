<template>
    <Header />
    <main class="container mx-auto py-10">
        <slot />
    </main>
    <Footer />
</template>

<script lang="js">

</script>

<style>
#__nuxt {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

main {
    flex: 1;
}
</style>