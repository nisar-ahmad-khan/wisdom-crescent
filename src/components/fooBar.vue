<template>
    <footer class="bg-[#f5f1e6] py-10 text-center text-gray-600 mt-auto px-4">
      <p class="text-sm sm:text-base max-w-2xl mx-auto">
        This project shares authentic prophecies of Prophet Muhammad ﷺ and Qur'anic ayats from
        verified Islamic sources.
        <br>
        Feel free to contact me if you find any mistake <br>
        &copy;Nisar Ahmad | {{ date.getFullYear() }}
      </p>
        <p>Our Other Products</p>
        <div class="flex justify-center">

            <a href="https://eventlay.com" target="_blank" rel="noopener">
    Eventlay
</a>
        </div>
    </footer>
</template>

<script setup>
const date = new Date()
</script>
