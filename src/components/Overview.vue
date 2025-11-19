<template>
  <section id="services" class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <div class="text-center mb-12">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Tentang Kami</h2>
        <div class="w-20 h-1 bg-orange-500 mx-auto"></div>
      </div>
      
      <div class="grid md:grid-cols-2 gap-12 items-center max-w-6xl mx-auto">
        <!-- Left Side - Company Info -->
        <div>
          <h3 class="text-2xl font-bold text-orange-500 mb-4">CIHAMPELAS AUTO SERVICE</h3>
          <p class="text-gray-700 mb-6 leading-relaxed">
            Cihampelas Auto Service (CAS) adalah bengkel spesialis perawatan dan perbaikan kendaraan yang telah berpengalaman melayani masyarakat Samarinda dan sekitarnya. Kami berkomitmen memberikan layanan terbaik dengan teknisi profesional dan peralatan modern.
          </p>
          <p class="text-gray-700 mb-6 leading-relaxed">
            Layanan kami mencakup tune up, modifikasi mesin, perbaikan kaki-kaki, ganti oli berkala, over haul mesin, dan berbagai service kendaraan lainnya. Kami melayani semua jenis kendaraan dengan garansi kualitas pekerjaan.
          </p>
          <p class="text-gray-700 leading-relaxed">
            Kepuasan pelanggan adalah prioritas utama kami. Dengan harga kompetitif dan hasil kerja yang memuaskan, CAS menjadi pilihan tepat untuk merawat kendaraan kesayangan Anda.
          </p>
          
          <div class="mt-8 space-y-4">
            <div class="flex items-center">
              <svg class="w-6 h-6 text-orange-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
              </svg>
              <span class="text-gray-700">Teknisi Berpengalaman & Profesional</span>
            </div>
            <div class="flex items-center">
              <svg class="w-6 h-6 text-orange-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
              </svg>
              <span class="text-gray-700">Spare Part Original & Berkualitas</span>
            </div>
            <div class="flex items-center">
              <svg class="w-6 h-6 text-orange-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
              </svg>
              <span class="text-gray-700">Pengerjaan Cepat & Harga Terjangkau</span>
            </div>
            <div class="flex items-center">
              <svg class="w-6 h-6 text-orange-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
              </svg>
              <span class="text-gray-700">Garansi Service & Kepuasan Pelanggan</span>
            </div>
          </div>
        </div>
        
        <!-- Right Side - Logo/Image -->
        <div class="flex justify-center">
          <div class="bg-gradient-to-br from-orange-500 to-orange-600 p-12 rounded-lg shadow-2xl">
            <div class="text-white text-center">
              <div class="text-8xl font-bold mb-4">CAS</div>
              <div class="text-xl font-semibold">CIHAMPELAS</div>
              <div class="text-lg">AUTO SERVICE</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Overview'
}
</script>