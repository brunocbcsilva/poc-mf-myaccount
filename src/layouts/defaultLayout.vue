<template>
  <div class="antialiased dark:bg-gray-900">
    <TopNavbar />

    <!-- Sidebar -->

    <SidebarNav />

    <!-- Main -->

    <main class="h-auto p-8 pt-20 md:ml-64">
      <slot />
    </main>

    <footer class="flex items-center justify-between border-t p-8 pl-72">
      <div>
        <ComercEnergiaLogo />
      </div>
      <div>Lorem ipsum dolor.</div>
    </footer>
  </div>
</template>

<script setup>
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'
import TopNavbar from '@/components/TopNavbar.vue'
import SidebarNav from '@/components/SidebarNav.vue'
import ComercEnergiaLogo from '@/components/ComercEnergiaLogo.vue'

onMounted(() => {
  initFlowbite()
})
</script>
