<template>
  <section class="py-16 bg-gray-50">
    <div class="container mx-auto px-4">
      <div class="grid md:grid-cols-2 gap-8 max-w-6xl mx-auto">
        <!-- Left Side - Contact Info -->
        <div class="bg-white p-8 rounded-lg shadow-lg">
          <h2 class="text-3xl font-bold text-gray-900 mb-6">Hubungi Kami</h2>
          <p class="text-gray-600 mb-8">
            Kami siap melayani Anda dengan layanan terbaik untuk perawatan dan perbaikan kendaraan Anda.
          </p>
          <p class="text-gray-600 mb-8">
            CAS Garage adalah bengkel terpercaya yang menyediakan berbagai layanan otomotif mulai dari tune up, modifikasi mesin, perbaikan kaki-kaki, ganti oli, hingga over haul mesin. Kunjungi kami atau hubungi untuk konsultasi dan booking service.
          </p>
          
          <div class="space-y-6">
            <!-- Phone -->
            <div class="flex items-start">
              <div class="bg-orange-500 p-3 rounded-lg mr-4">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                </svg>
              </div>
              <div>
                <div class="font-semibold text-gray-900 mb-1">Telepon / WhatsApp</div>
                <a href="tel:+6281154421487" class="text-orange-500 hover:text-orange-600">+62 811-542-1487</a>
              </div>
            </div>
            
            <!-- Email -->
            <div class="flex items-start">
              <div class="bg-orange-500 p-3 rounded-lg mr-4">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                </svg>
              </div>
              <div>
                <div class="font-semibold text-gray-900 mb-1">Email</div>
                <a href="mailto:casgarage@gmail.com" class="text-orange-500 hover:text-orange-600 break-all">casgarage@gmail.com</a>
              </div>
            </div>
            
            <!-- Office Address -->
            <div class="flex items-start">
              <div class="bg-orange-500 p-3 rounded-lg mr-4">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                </svg>
              </div>
              <div>
                <div class="font-semibold text-gray-900 mb-1">Alamat Bengkel</div>
                <p class="text-gray-600">
                  Tamansari Bukit Mutiara, Gn. Samarinda Baru<br>
                  Kec. Balikpapan Utara, Kota Balikpapan<br>
                  Kalimantan Timur 76128
                </p>
              </div>
            </div>

            <!-- Jam Operasional -->
            <div class="flex items-start">
              <div class="bg-orange-500 p-3 rounded-lg mr-4">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                </svg>
              </div>
              <div>
                <div class="font-semibold text-gray-900 mb-1">Jam Operasional</div>
                <p class="text-gray-600">Senin - Sabtu: 08.00 - 17.00 WITA</p>
                <p class="text-gray-600">Minggu: Tutup</p>
              </div>
            </div>
          </div>
        </div>
        
        <!-- Right Side - Google Maps -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden">
          <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3988.8957089097926!2d116.86263701066028!3d-1.2321933355644414!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2df1470c2c14e327%3A0x9a853fdfed0699c7!2sCAS%20Garage!5e0!3m2!1sen!2sid!4v1763588331275!5m2!1sen!2sid" 
            width="100%" 
            height="100%" 
            style="border:0; min-height: 500px;" 
            allowfullscreen="" 
            loading="lazy" 
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactInfo'
}
</script>