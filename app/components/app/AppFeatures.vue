<script setup lang="ts"></script>

<template>
   <section class="bg-white py-24">
      <div class="container mx-auto px-6">
         <div class="mx-auto max-w-7xl">
            <div class="mb-16 grid grid-cols-1 gap-12 lg:grid-cols-2">
               <div>
                  <p class="mb-6 text-sm font-semibold text-emerald-500">
                     Features
                  </p>
                  <h3
                     class="text-4xl leading-tight font-bold md:text-5xl lg:text-6xl"
                  >
                     Smart Tools to Support 
                     <span class="text-gray-400"
                        >Every Step of Your Practice.</span
                     >
                  </h3>
               </div>

               <div class="flex items-start justify-end col-end-1">
                  <button
                     class="transform rounded-full bg-linear-to-r from-emerald-400 to-emerald-500 px-8 py-4 text-lg font-medium text-white shadow-xl transition hover:scale-105 hover:from-emerald-500 hover:to-emerald-600 hover:shadow-2xl"
                  >
                     Get Started                                                                                                                                                                                                                                                                                                                                                                                                                   
                  </button>
               </div>
            </div>

            <div class="grid grid-cols-1 items-center gap-16 lg:grid-cols-2">
               <div class="space-y-8">
                  <div class="flex gap-4">
                     <div class="shrink-0">
                        <div
                           class="flex h-8 w-8 items-center justify-center rounded-lg bg-emerald-100 text-emerald-600"
                        >
                           <Icon name="lucide:person-standing" />
                        </div>
                     </div>
                     <div>
                        <h4 class="mb-2 text-xl font-bold text-gray-900">
                           Smart Patient History
                        </h4>
                        <p class="leading-relaxed text-gray-600">
                           Access organized patient data instantly, from previous 
                           diagnoses to medication history, all in one secure place.
                        </p>
                     </div>
                  </div>

                  <div class="flex gap-4">
                     <div class="shrink-0">
                        <div
                           class="flex h-8 w-8 items-center justify-center rounded-lg bg-emerald-100 text-emerald-600"
                        >
                           <Icon name="lucide:brain-circuit" />
                        </div>
                     </div>
                     <div>
                        <h4 class="mb-2 text-xl font-bold text-gray-900">
                           AI Diagnostic Support
                        </h4>
                        <p class="leading-relaxed text-gray-600">
                           A reliable second opinion at your fingertips. 
                           Our AI helps flag anomalies in screenings to assist with early detection.
                        </p>
                     </div>
                  </div>

                  <div class="flex gap-4">
                     <div class="shrink-0">
                        <div
                           class="flex h-8 w-8 items-center justify-center rounded-lg bg-emerald-100 text-emerald-600"
                        >
                           <Icon name="lucide:workflow" />
                        </div>
                     </div>
                     <div>
                        <h4 class="mb-2 text-xl font-bold text-gray-900">
                           Automated Workflow
                        </h4>
                        <p class="leading-relaxed text-gray-600">
                           Reduce administrative fatigue. Let the app handle 
                           scheduling and follow-ups so you can focus on clinical care.
                        </p>
                     </div>
                  </div>

                  <div class="flex gap-4">
                     <div class="shrink-0">
                        <div
                           class="flex h-8 w-8 items-center justify-center rounded-lg bg-emerald-100 text-emerald-600"
                        >
                           <Icon name="lucide:shield-plus" />
                        </div>
                     </div>
                     <div>
                        <h4 class="mb-2 text-xl font-bold text-gray-900">
                           Secure Data Insights
                        </h4>
                        <p class="leading-relaxed text-gray-600">
                           View practice trends and patient outcomes through encrypted, 
                           high-level analytics designed for healthcare privacy.
                        </p>
                     </div>
                  </div>
               </div>

               <div class="relative">
                  <div
                     class="h-96 overflow-hidden rounded-3xl bg-linear-to-br from-emerald-300 via-teal-300 to-green-200 p-8"
                  >
                     <div class="absolute inset-0 opacity-20">
                        <svg
                           class="h-full w-full"
                           viewBox="0 0 400 300"
                           fill="none"
                        >
                           <path
                              d="M0 150 Q 100 50 200 150 T 400 150"
                              stroke="white"
                              strokeWidth="2"
                              opacity="0.1"
                           />
                        </svg>
                     </div>

                     <div
                        class="relative z-10 flex h-full items-center justify-center"
                     >
                        <div class="grid w-full md:grid-cols-2 gap-6">
                           <div
                              class="transform rounded-2xl bg-white p-6 shadow-xl transition hover:scale-105"
                           >
                              <div class="mb-4 flex items-center gap-2">
                                 <span class="text-emerald-500">⚡</span>
                                 <h5 class="font-semibold text-gray-900">
                                    Daily Steps
                                 </h5>
                              </div>
                              <div class="mb-4">
                                 <svg
                                    class="h-12 w-full"
                                    viewBox="0 0 100 40"
                                    preserveAspectRatio="none"
                                 >
                                    <path
                                       d="M0 30 L 10 15 L 20 25 L 30 10 L 40 20 L 50 5 L 60 18 L 70 12 L 80 22 L 90 8 L 100 15"
                                       stroke="#10b981"
                                       strokeWidth="2"
                                       fill="none"
                                    />
                                 </svg>
                              </div>
                              <div class="text-center">
                                 <p class="text-2xl font-bold text-gray-900">
                                    5,120
                                 </p>
                                 <p class="text-sm text-gray-500">
                                    Steps today
                                 </p>
                              </div>
                              <div class="mt-4 flex justify-center">
                                 <div
                                    class="flex h-6 w-6 items-center justify-center rounded-full bg-gray-900 text-xs text-white"
                                 >
                                    ↗
                                 </div>
                              </div>
                           </div>

                           <div
                              class="transform rounded-2xl bg-white p-6 shadow-xl transition hover:scale-105"
                           >
                              <div class="mb-4 flex items-center gap-2">
                                 <span class="text-emerald-500">❤️</span>
                                 <h5 class="font-semibold text-gray-900">
                                    Heart Rate
                                 </h5>
                              </div>
                              <div class="mb-4">
                                 <svg
                                    class="h-12 w-full"
                                    viewBox="0 0 100 40"
                                    preserveAspectRatio="none"
                                 >
                                    <path
                                       d="M0 20 L 20 20 L 25 5 L 30 25 L 35 15 L 40 20 L 60 20 L 65 10 L 70 25 L 75 18 L 80 20 L 100 20"
                                       stroke="#10b981"
                                       strokeWidth="2"
                                       fill="none"
                                    />
                                 </svg>
                              </div>
                              <div class="text-center">
                                 <p class="text-2xl font-bold text-gray-900">
                                    73 <span class="text-sm">bpm</span>
                                 </p>
                                 <p class="text-sm text-gray-500">Normal</p>
                              </div>
                              <div class="mt-4 flex justify-center">
                                 <div
                                    class="flex h-6 w-6 items-center justify-center rounded-full bg-gray-900 text-xs text-white"
                                 >
                                    ↗
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </div>
   </section>
</template>
