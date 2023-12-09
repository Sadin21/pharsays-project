<script setup>

</script>

<template>
  <div class="w-100 h-screen bg-[#F2F2F2]">
        <div class="m-auto w-4/5 pt-14 pb-10">
          <div class="grid grid-cols-3 gap-6">
            <div class="bg-white p-6 font-bold text-xl text-[#11111] rounded-xl">
              <h1>Mulai generate soal essay</h1>
              <div class=" relative mt-10">
                <label for="name-with-label" class="text-gray-700">
                    Subject (*Pharmacotherapy)
                </label>
                <input type="text" id="name-with-label" class=" rounded-lg flex-1 appearance-none border border-[##4C37EE] w-full py-2 px-4 bg-white text-gray-700 placeholder-gray-400 shadow-sm text-base mt-2" name="email" placeholder=""/>
              </div>
              <div class=" relative mt-10">
                <label for="name-with-label" class="text-gray-700">
                    Topik Terkait (*Hipertensi/Stroke)
                </label>
                <input type="text" id="name-with-label" class=" rounded-lg flex-1 appearance-none border border-[##4C37EE] w-full py-2 px-4 bg-white text-gray-700 placeholder-gray-400 shadow-sm text-base mt-2" name="email" placeholder=""/>
              </div>
              <button class="mt-10 button bg-[#4C37EE] text-white px-4 py-3 rounded-lg w-full">Generate Soal</button>
            </div>
            <div class="col-span-2 bg-white p-6 font-bold text-xl text-[#11111] rounded-xl">
              <h1>Hasil generate soal</h1>
            </div>
          </div>
        </div>
    </div>
</template>