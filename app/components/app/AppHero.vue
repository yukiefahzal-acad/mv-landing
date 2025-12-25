<script setup lang="ts"></script>


<template>
   <div id="home" class="relative mx-auto max-w-7xl">
      <!-- SECTION: Blob -->
      <div class="absolute top-1/2 left-1/2 z-0 -translate-1/2">
         <div class="relative size-[300px] md:size-[500px]">
            <!-- ANCHOR: Blob Shadow -->
            <div
               class="absolute inset-0 rounded-full bg-linear-to-br from-cyan-300 via-cyan-400 to-sky-500 opacity-20 blur-3xl"
            ></div>
            <!-- ANCHOR: Blob Background -->
            <div
               class="absolute inset-8 animate-[spin_20s_linear_infinite] rounded-[40%_60%_70%_30%/60%_30%_70%_40%] bg-linear-to-br from-sky-300 via-cyan-400 to-blue-500 blur-lg opacity-50"
            ></div>
            <!-- ANCHOR: Blob Foreground -->
            <div
               class="absolute inset-16 animate-[spin_15s_linear_infinite_reverse] rounded-[60%_40%_30%_70%/40%_70%_30%_60%] bg-linear-to-br from-cyan-200 via-cyan-300 to-cyan-500 blur opacity-75"
            ></div>
         </div>
      </div>
      <!-- !SECTION: Blob -->

      <!-- <div
         class="relative z-10 mb-16 hidden grid-cols-1 gap-8 md:grid md:grid-cols-3"
      >
         <div class="col-end-2 flex items-center justify-end">
            <div class="max-w-sm text-center md:text-right">
               <p class="leading-relaxed text-gray-600">
                  Validated by thousands of clinical datasets, 
                  our AI empowers physicians to identify malignancies 
                  with unprecedented speed and accuracy.
               </p>
            </div>
         </div>
         <div class="col-start-3 flex items-center justify-start">
            <div class="max-w-sm text-center md:text-left">
               <p class="leading-relaxed text-gray-600">
                  o beyond standard screenings. Our deep-learning algorithms 
                  analyze complex patterns to support early-stage cancer detection 
                  and clinical decision-making.
               </p>
            </div>
         </div>
      </div> -->

      <div class="relative z-10 text-center">
         <h1
            class="mb-6 text-5xl leading-tight font-extrabold tracking-wide text-gray-900 md:text-3xl lg:text-5xl"
         >
             The Command Center for Your Entire Medical Universe.
         </h1>
         <div class="flex items-center justify-center pb-10">
            <div class="max-w-xl text-center">
               <p class="leading-relaxed text-gray-600">
                  Ubah Kesibukan Menjadi Keteraturan. 
                  <strong>Medic<span class="text-emerald-500">Verse</span></strong> 
                  menyelaraskan pasien, dokter, dan operasional klinik Anda dalam satu orbit yang sempurna. 
                  Generasi baru Sistem Manajemen Klinik telah hadir.
               </p>
            </div>
         </div>

         <button
            class="transform rounded-full bg-linear-to-r from-emerald-400 to-emerald-500 px-8 py-4 text-lg font-medium text-white shadow-xl transition hover:scale-105 hover:from-emerald-500 hover:to-emerald-600 hover:shadow-2xl"
         >
            <div
               class="flex font-bold h-8 items-center"
            >
               <Icon name="lucide:rocket" />
               <p class="ml-2">
                  Uji Coba Penerbangan 
               </p> 
            </div>
         </button>
      </div>
   </div>
</template>
