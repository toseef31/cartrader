<template>
  <div>
    <header class="sticky top-0 z-50 flex justify-between items-center space-x-1 border-b bg-white p-4 shadow-md">
      <a class="text-3xl font-mono" href="">CarTrader</a>
    </header>
    <div class="relative h-screen w-100 bg-no-repeat bg-cover bg-bottom bg-[url('public/assets/images/home-bg.jpg')]">
      <div class="z-10 absolute w-full h-full flex justify-center items-center">
        <div class="text-center w-1/2">
          <h1 class="text-8xl font-serif mb-10 text-white">Find Your Drive</h1>
          <div
            class="font-serif w-100 rounded-full flex justify-between overflow-hidden bg-white drop-shadow-2xl mx-auto">
            <input class="py-3 px-5 w-full text-2xl rounded-full focus:outline-none" type="text">
            <button class="bg-sky-500 px-10 text-white">search</button>
          </div>
        </div>
      </div>
      <div class="z-1 absolute w-full h-full bg-black opacity-50"></div>

    </div>

    <div class="mx-auto mb-96 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-4/5 ">
      <div class="mt-32 flex h-48">
        <!-- sidebar -->
        <div class="shadow border w-64 mr-10 z-30 ">
          <div class="p-5 flex justify-between relative cursor-pointer border-b">
            <h3>Location</h3>
            <h3 class="text-blue-500 capitalize">Rawalpindi</h3>
          </div>
          <div class="p-5 flex justify-between relative cursor-pointer border-b">
            <h3>Make</h3>
            <h3 class="text-blue-500 capitalize">United</h3>
          </div>
          <div class="p-5 flex justify-between relative cursor-pointer border-b">
            <h3>Price</h3>
            <h3 class="text-blue-500 capitalize">Any</h3>
          </div>
        </div>
        <!-- <div class="shadow border w-100 mr-10 z-30 "></div> -->
        <!-- sidebar -->

        <!-- cards -->
        <div class="w-full">
          <div class="shadow border w-full overflow-hidden mb-5 cursor-pointer">
            <div class="flex h-full">
              <img
                src="https://www.proton.com/-/media/project/proton-group/proton/media/car-models/x70/2022-x70/x70-mc1-booknow-thumb.ashx?la=en&hash=D6DCDD26F54A46285CEB78B0636E723D8185C194"
                class=" h-full w-[150px] p-4 self-center" alt="">
              <div class="p-4 flex flex-col">
                <div>
                  <h1 class="text-2xl text-blue-700">Honda Accord</h1>
                  <p class="text-gray-700">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corporis vitae
                    tempora sunt laboriosam dignissimos incidunt debitis et minima aliquid reprehenderit.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="shadow border w-full overflow-hidden mb-5 cursor-pointer">
            <div class="flex h-full">
              <img
                src="https://www.proton.com/-/media/project/proton-group/proton/media/car-models/x70/2022-x70/x70-mc1-booknow-thumb.ashx?la=en&hash=D6DCDD26F54A46285CEB78B0636E723D8185C194"
                class=" h-full w-[150px] p-4 self-center" alt="">

              <div class="p-4 flex flex-col">
                <div>
                  <h1 class="text-2xl text-blue-700">Honda Civic</h1>
                  <p class="text-gray-700">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corporis vitae
                    tempora sunt laboriosam dignissimos incidunt debitis et minima aliquid reprehenderit.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="shadow border w-full overflow-hidden mb-5 cursor-pointer">
            <div class="flex h-full">
              <img
                src="https://www.proton.com/-/media/project/proton-group/proton/media/car-models/x70/2022-x70/x70-mc1-booknow-thumb.ashx?la=en&hash=D6DCDD26F54A46285CEB78B0636E723D8185C194"
                class=" h-full w-[150px] p-4 self-center" alt="">

              <div class="p-4 flex flex-col">
                <div>
                  <h1 class="text-2xl text-blue-700">Honda City</h1>
                  <p class="text-gray-700">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corporis vitae
                    tempora sunt laboriosam dignissimos incidunt debitis et minima aliquid reprehenderit.</p>
                  <p class="mt-3 text-blue-500">Model: 2020</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- cards -->
      </div>
    </div>
  </div>
</template>
