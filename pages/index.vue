<template>
  <div>
    <Html :lang="dynamic > 50 ? 'en-GB': 'en-US'">
      <Head>
        <Title>Restaurantly</Title>
        <Meta 
          name="description"
          content="My page on restaurants"
        />
        <Link
          rel="preload"
          href="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
          as="script"
        />
      </Head>
    </Html>
    <div class="container text-center">
      <h1 class="mt-5">Welcome to Restaurantly</h1>
      <NuxtLink class="btn btn-primary" to="/restaurants">Go to restaurants</NuxtLink>
    </div>
  </div>
</template>
