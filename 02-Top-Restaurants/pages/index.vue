<template>
  <div>
    <Html>
      <Head>
        <Title> Restaurantly </Title>
        <Meta name="description" content="My page is cool" />
        <Link rel="preload" href="@/favicon.ico" as="script" />
      </Head>
    </Html>
    <div class="container">
      <h1>Welcome to Restaurantly</h1>
      <a href="/restaurants">Go to restaurants</a>
    </div>
  </div>
</template>

<style scoped>
.container {
   text-align: center; 
   margin-top: 5rem;   
}
</style>
