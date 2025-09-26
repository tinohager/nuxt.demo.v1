<template>
  <footer class="bg-white order-last">
    <div class="container flex flex-wrap justify-between gap-12 my-24 md:gap-24">
      <div class="mr-auto">
        <Logo />
        <p class="mt-4 text-sm text-gray-700 xl:max-w-md">
        WooNuxt is unmatched when it comes to performance and scalability. Reap the benefits of having a online store that out performs all of your competitors. You can edit components to display your own information just like the one you're reading now.
        </p>
        <LangSwitcher class="mt-8" />
      </div>
      <div class="w-3/7 lg:w-auto">
        <div class="mb-1 font-semibold">Information</div>
        <div class="text-sm">
          <a class="py-1.5 block" href="https://github.com/scottyzen/woonuxt?tab=readme-ov-file#next-generation-front-end-for-woocommerce" target="_blank">About</a>
          <a href="/" class="py-1.5 block">Careers</a>
          <a href="/" class="py-1.5 block">Press</a>
          <a href="https://woonuxt.com/faq" class="py-1.5 block" rel="noreferrer" target="_blank">FAQ's</a>
        </div>
      </div>
      <div class="w-3/7 lg:w-auto">
        <div class="mb-1 font-semibold">Products</div>
        <div class="text-sm">
          <NuxtLink to="/" class="py-1.5 block">test1</NuxtLink>
          <NuxtLink to="/" class="py-1.5 block">On sale</NuxtLink>
          <NuxtLink to="/" class="py-1.5 block">Top rated</NuxtLink>
          <a href="/" class="py-1.5 block">test2</a>
        </div>
      </div>
      <div class="w-3/7 lg:w-auto">
        <div class="mb-1 font-semibold">Customer Service</div>
        <div class="text-sm">
          <NuxtLink to="/contact" class="py-1.5 block">Contact Us</NuxtLink>
          <a href="/" class="py-1.5 block">Shipping & Returns</a>
          <a href="/" class="py-1.5 block">Privacy Policy</a>
          <a href="/" class="py-1.5 block">Terms & Conditions</a>
        </div>
      </div>
      <div class="w-3/7 lg:w-auto">
        <div class="mb-1 font-semibold">My Account</div>
        <div class="text-sm">
          <NuxtLink to="/" class="py-1.5 block">test5</NuxtLink>
          <NuxtLink to="/" class="py-1.5 block">test6</NuxtLink>
          <a href="/" class="py-1.5 block">test7</a>
        </div>
      </div>
    </div>
    <div class="container border-t flex items-center justify-center mb-4">
      <div class="copywrite">
        <p class="py-4 text-xs text-center">
          <a href="https://woonuxt.com" :title="`WooNuxt v1`">WooNuxt v1</a> - by
          <a href="https://scottyzen.com" title="Scott Kennedy - Web Developer" target="_blank">Scott Kennedy</a>
        </p>
      </div>
      <SocialIcons class="ml-auto" />
    </div>
  </footer>
</template>
