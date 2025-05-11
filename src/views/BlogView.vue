<template>
  <div class="container mx-auto p-3 md:p-8">
    <div class="flex flex-col-reverse md:flex-row relative">
      <!-- Bagian Kontak -->
      <div class="w-full md:w-2/3">
        <div class="flex flex-col gap-4 md:px-20 fade-zoom-up">
          <div class="bg-[#1e1e1f] text-white p-5 md:py-7 md:px-8 rounded-xl text-left">
            <h1 class="text-xl md:text-2xl text-amber-200 font-bold mb-4">Informasi Kontak</h1>
            
            <!-- LinkedIn -->
            <div class="mb-3">
              <a href="https://www.linkedin.com/in/arya-fadillah-ba3a19364" target="_blank" class="flex items-center text-lg text-amber-200 hover:text-amber-400">
                <i class="fab fa-linkedin mr-3"></i> LinkedIn
              </a>
            </div>

            <!-- Gmail -->
            <div class="mb-3">
              <a href="mailto:aryafadila509@gmail.com" class="flex items-center text-lg text-amber-200 hover:text-amber-400">
                <i class="fas fa-envelope mr-3"></i> Gmail
              </a>
            </div>

            <!-- Instagram -->
            <div>
              <a href="https://www.instagram.com/aryafadd?igsh=MW05Y2IwazNkN2JoaA==" target="_blank" class="flex items-center text-lg text-amber-200 hover:text-amber-400">
                <i class="fab fa-instagram mr-3"></i> Instagram
              </a>
            </div>
          </div>
        </div>
      </div>

      <!-- Bagian Sidebar (Opsional) -->
      <div class="w-full md:w-1/3 h-fit p-8 md:sticky md:top-24">
        <div class="flex flex-col text-left">
          <div class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">
            Mari terhubung melalui platform berikut!
          </div>
          <div class="h-[1px] mt-7 mb-7 w-20 bg-amber-200 aos-init aos-animate mr-2"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
}
</script>

<style scoped>
.fade-zoom-up {
  animation: fadeZoomUp 1s ease-in-out;
}
@keyframes fadeZoomUp {
  0% {
    opacity: 0;
    transform: scale(0.5);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}
</style>
