<template>
    <header class="w-full border-b border-slate-200 py-6">
      <div class="container mx-auto">
        <div class="flex flex-col md:flex-row justify-between items-center px-4">
          <div class="mb-4 md:mb-4">
            <NuxtLink to="/" class="text-xl font-bold"
              >Sekolah Beta Intensif</NuxtLink
            >
          </div>
          <nav class="flex items-center gap-6">
            <NuxtLink to="/" class="text-base">Home</NuxtLink>
            <NuxtLink to="/product" class="text-base">Products</NuxtLink>
            <NuxtLink to="/cart" class="text-base">Cart</NuxtLink>
          </nav>
        </div>
      </div>
    </header>
  </template>