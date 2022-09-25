<template>
    <div>
        <Html>
            <Head>
                <Title> Top 50 Restaurants in the world </Title>
                <Meta name="description" content="My page is cool" />
                <Link rel="preload" href="@/favicon.ico" as="script" />
            </Head>
        </Html>
        <NuxtLayout name="custom">
            <div class="container">
                <RestaurantTable />
            </div>
        </NuxtLayout>   
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>