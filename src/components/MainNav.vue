<script setup>
    import Link from './Link.vue'
    import Logo from './Logo.vue'
</script>

<template>
    <header class="px-10 py-5 bg-gray-700 flex justify-between absolute top-0 w-full z-10">
        <div class="text-3xl font-black text-white">
            <Logo />    
        </div>
        
        <nav>
            <Link to="admin">Zona Admin</Link>
        </nav>
    </header>
</template>


