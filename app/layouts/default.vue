<template>
  <div>
     <header style="background-color: blueviolet; text-align: center; padding: 10px;">
        <nav>
            <ul style="margin: 20px;">
                <li style="float: left;"><NuxtLink to="/">Home</NuxtLink></li>
                <li style="float: left;"><NuxtLink to="/about">About</NuxtLink></li>
                <li style="float: left;"><NuxtLink to="/blogs">Blogs</NuxtLink></li>
            </ul>
        </nav>
    </header>
    <main style="padding: 20px;">
        <slot />
    </main>
    <div class="footer" style="background-color: blueviolet; text-align: center; padding: 10px;">
        <p>&copy; 2024 My Nuxt App. All rights reserved.</p>
    </div>
  </div>
</template>