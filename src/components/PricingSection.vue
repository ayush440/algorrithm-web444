<template>
  <section id="features" class="w-full bg-[#304838] py-20 -mt-10 md:-mt-20 lg:-mt-30 xl:-mt-20">
    <div class="max-w-[1702px] mx-auto px-4 sm:px-6 md:px-[69px]">
      <!-- Free Trial Box -->
      <div class="mb-8 w-full rounded-3xl relative overflow-visible h-[650px] md:h-[400px]">
        <div class="absolute inset-0 bg-white/10 backdrop-blur-md hover:bg-white/20 transition-all duration-300 rounded-3xl"></div>
        <div class="flex h-full relative flex-col md:flex-row">
          
          <!-- Text content - Centered on mobile -->
          <div class="w-full md:w-[45%] p-8 md:p-12 flex flex-col justify-start md:justify-center items-center md:items-start text-center md:text-left z-10 md:ml-32 pt-12 md:pt-0">
            <h2 class="text-3xl md:text-5xl font-semibold text-white mb-2 md:w-96">
              Free Trial for
              <br><span class="text-[#FFB800] inline-block mt-1">7 Days</span>
            </h2>
            <button class="bg-[#FFB800] text-[#304838] px-6 py-2 md:px-8 md:py-3 rounded-full mt-6 hover:bg-opacity-90 transition-all duration-300 w-auto">
              Try Now
            </button>
          </div>

          <!-- Image container - Bottom center on mobile -->
          <div class="absolute md:relative bottom-0 left-1/2 md:left-auto transform -translate-x-1/2 md:translate-x-0 md:right-[-10%] w-full sm:w-[70%] h-[60%] md:h-[150%] md:top-[-50%]">
            <div class="absolute inset-0 bg-gradient-radial from-white/20 to-transparent pointer-events-none"></div>
            <img 
              src="../assets/images/image6.png"
              alt="Person using phone" 
              class="absolute bottom-0 left-1/2 transform -translate-x-1/2 lg:-translate-x-3/4 xl:-translate-x-3/4  md:-translate-x-3/4 w-auto h-full object-cover object-bottom md:h-auto md:w-auto"
            />
          </div>

        </div>
      </div>
      <!-- Two Column Layout -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4 sm:gap-6 md:gap-8 mb-8">
        <!-- Daily Profit Box -->
        <div class="rounded-3xl overflow-hidden group relative h-[450px] sm:h-[500px] md:h-[617px]">
          <div class="absolute inset-0 bg-white/10 backdrop-blur-md group-hover:bg-white/20 transition-all duration-300"></div>
          <div id="why-us" class="relative z-10 p-6 sm:p-8 h-full flex flex-col">
            <h3  class="text-xl sm:text-2xl md:text-4xl font- text-white text-center mt-6 sm:mt-10">
              Daily profit with perfect
              <br />
              <span class="text-[#FFB800]">Risk Management</span>
            </h3>
            <div class="relative flex-1 w-full mt-8">
              <img 
                src="../assets/images/frame.png"
                alt="" 
                class="absolute bottom-0 right-0 w-auto h-[80%] max-w-[90%] object-contain object-bottom-right z-30"
              />
              <img 
                src="../assets/images/image.png"
                alt="Trading Interface" 
                class="absolute -bottom-8 -right-10 w-auto h-[80%] max-w-[90%] object-contain object-bottom-right z-20"
              />
            </div>
          </div>
        </div>

        <!-- X2 Box -->
        <div class="rounded-3xl overflow-hidden group relative h-[450px] sm:h-[500px] md:h-[617px]">
          <div class="absolute inset-0 bg-white/10 backdrop-blur-md group-hover:bg-white/20 transition-all duration-300"></div>
          <div 
            class="absolute inset-0 transition-all duration-300"
            :style="{
              background: 'radial-gradient(circle at center, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0))'
            }"
          ></div>
          <div class="relative z-10 p-6 sm:p-8 h-full flex flex-col items-center ">
            <h3 class="text-xl sm:text-2xl md:text-4xl font- text-white text-center mt-6 sm:mt-10 ">
              Suitable for any type of
              <br />
              lot you decide
            </h3>
            <div class="relative flex-1 w-full mt-8 flex items-center justify-center">
              <img 
                src="../assets/images/image8.png"
                alt="X2 3D Logo" 
                class="w-[70%] sm:w-[75%] md:w-[50%] h-auto object-contain"
              />
            </div>
          </div>
        </div>
      </div>
      <!-- Clients Box -->
      <div class="mb-8 w-full rounded-3xl overflow-hidden group relative min-h-[240px]">
        <div class="absolute inset-0 bg-white/10 backdrop-blur-md group-hover:bg-white/20 transition-all duration-300"></div>
        <div class="relative z-10 p-6 md:p-12">
          <div class="flex flex-col md:flex-row justify-between items-center ">
            <div class="flex flex-col justify-center md:ml-32 mb-6 md:mb-0 ">
              <h2 class="text-3xl md:text-5xl  mb-1  ">
                <span class="text-[#FFB800] font-semibold">500+</span>
                <span class="text-white ml-2 font-semibold ">Client</span>
              </h2>
              <p class="text-xl md:text-5xl font-semibold text-white mb-6">Across India</p>
              <button class="bg-[#FFB800] text-[#304838] px-8 py-3 rounded-full hover:bg-opacity-90 transition-all duration-300 w-36">
                Try Now
              </button>
            </div>
            <div class="w-full md:w-1/2 md:pr-12">
              <img 
                src="../assets/images/Untitled-1.png"
                alt="Client Grid" 
                class="w-full h-auto object-contain md:hidden lg:block "
              />
            </div>
          </div>
        </div>
      </div>

      <!-- Bottom Two Column Layout -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4 sm:gap-6 md:gap-8">
        <!-- Chart Box -->
        <div class="rounded-3xl overflow-hidden group relative h-[450px] sm:h-[500px] md:h-[617px]">
          <div class="absolute inset-0 bg-white/10 backdrop-blur-md group-hover:bg-white/20 transition-all duration-300"></div>
          <div class="relative z-10 h-full flex flex-col items-center justify-center">
            <h3 class="text-xl sm:text-2xl md:text-4xl font- text-white text-center z-20 md:mt-20 mt-20 ">
              Suitable for any type of
              <br />lot you decide
            </h3>
            <div class="relative flex-1 w-full">
              <img 
                src="../assets/images/Vector.png"
                alt="Chart" 
                class="absolute bottom-0 left-0 w-full h-auto object-contain z-10"
              />
            </div>
          </div>
        </div>

        <!-- Experience Box (Updated) -->
        <div class="rounded-3xl overflow-hidden group relative h-[450px] sm:h-[500px] md:h-[617px]">
          <div class="absolute inset-0 bg-white/10 backdrop-blur-md group-hover:bg-white/20 transition-all duration-300"></div>
          <div 
            class="relative z-10 p-6 sm:p-8 h-full flex flex-col items-center"
            :style="{
              background: `
                radial-gradient(circle at top left, rgba(255, 255, 255, 0.1) 0%, transparent 15%),
                radial-gradient(circle at bottom right, rgba(255, 255, 255, 0.1) 0%, transparent 15%)
              `
            }"
          >
            <h3 class="text-3xl sm:text-4xl md:text-5xl font-bold text-center mt-6 sm:mt-10">
              <span class="text-[#FFB800]">5+ years</span>
              <span class="text-white"> of professional</span>
              <br />
              <span class="text-white">experience</span>
            </h3>
            <div class="relative flex-1 w-full mt-8 flex items-center justify-center">
              <img 
                src="../assets/images/image14.png"
                alt="Number 5" 
                class="w-[70%] sm:w-[75%] md:w-[80%] lg:w-[85%] xl:w-[60%] h-auto object-contain"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');

:root {
  font-family: 'Inter', sans-serif;
}

@supports (backdrop-filter: blur(12px)) {
  .backdrop-blur-md {
    backdrop-filter: blur(12px);
    -webkit-backdrop-filter: blur(12px);
  }
}
</style>