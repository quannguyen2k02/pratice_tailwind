<script setup></script>

<template>
  <!-- Begin aside -->
  <aside class="w-50 flex flex-col border-r border-gray-800">
    <div class="flex h-20 items-center mx-6 ">
      <h1 class="font-black">WVN</h1>
    </div>
    <div class="flex-1">
      <nav class="flex flex-col ml-2 ">
        <div class="text-xs font-semibold text-slate-400 px-3 mb-2">MAIN MENU</div>
        <a
          class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span
            class="material-symbols-outlined">dashboard</span>Dashboard</a>
        <a
          class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span
            class="material-symbols-outlined">build</span>Maintenance</a>
        <a
          class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span
            class="material-symbols-outlined">inventory</span>Inventory</a>
        <a
          class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span
            class="material-symbols-outlined">analytics</span>Analysis</a>
      </nav>
      <nav class="flex flex-col ml-2 mt-5 ">
        <div class="text-xs font-semibold text-slate-400 px-3 mb-2">SYSTEM</div>
        <a
          class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span
            class="material-symbols-outlined">settings_b_roll</span>Setting</a>
        <a
          class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span
            class="material-symbols-outlined">build</span>Maintenance</a>

      </nav>
    </div>

    <div class="p-6 border-t broder-r border-gray-800">
      <div class="flex py-2 bg-gray-800  flex-col items-center   rounded-lg">
        <span class="text-sm font-semibold">Marc Nguyen</span>
        <span class="text-xs text-slate-500">PM</span>
      </div>
    </div>
  </aside>
  <!-- End aside -->
  <!-- begin main -->
  <main class="flex-col flex-1 ">
    <!-- begin header -->
    <header class="h-16 w-full border-b border-gray-800 flex justify-between">
      <div class="flex justify-center items-center">
        <h2 class="text-xl font-bold mr-4 p-4">Line Overview</h2>
        <div class="flex justify-between items-center gap-1 rounded-3xl bg-gray-700 px-2 py-1">
          <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
          <span class="text-sm text-gray-400">Line monitoring</span>
        </div>
      </div>
      <div class="flex justify-center items-center w-1/3 gap-4">
        <input type="text" class="w-1/2 h-1/2 bg-gray-700 rounded-lg p-2 focus:outline-none ">
        <button
          class="w-fit flex justify-center items-center rounded-lg border p-2 border-gray-400 hover:bg-gray-700 cursor-pointer">
          <span class="material-symbols-outlined">
            add
          </span>
          New assets
        </button>
      </div>
    </header>
    <!-- end header -->
    <div class="h-1/8  content  w-full px-3 grid grid-cols-4 gap-4 my-4 ">
      <div class="  rounded-lg bg-gray-800 p-5 h-full flex flex-col justify-center">
        <p class="text-sm text-slate-500">Total Power Consumption</p>

        <h1 class="text-2xl font-bold">1,240kW</h1>

      </div>
      <div class=" rounded-lg bg-gray-800 p-5 h-full flex flex-col justify-center">
        <p class="text-sm text-slate-500">Overall Line Efficiency</p>
        <h1 class="text-2xl font-bold">97,8%</h1>

      </div>
      <div class="  rounded-lg bg-gray-800 p-5 h-full flex flex-col justify-center">
        <p class="text-sm text-slate-500">Total Power Consumption</p>
        <h1 class="text-2xl font-bold">1,240kW</h1>

      </div>
      <div class="  rounded-lg bg-gray-800 p-5 h-full flex flex-col justify-center">
        <p class="text-sm text-slate-500">Total Power Consumption</p>
        <h1 class="text-2xl font-bold">1,240kW</h1>

      </div>
    </div>

    <div class="flex flex-1 overflow-y-auto p-8">
      <div class="grid w-full grid-cols-1 md:grid-cols-2 lg:grid-cols-4 xl:grid-cols-5 gap-4 pb-24">
        <div
          class="bg-white dark:bg-slate-900 rounded-xl border-l-4 border-l-emerald-500 border-y border-r border-slate-200 dark:border-slate-800 p-4 shadow-sm hover:shadow-md transition-all group cursor-pointer">
          <div class="flex justify-between items-start mb-4">
            <div class="p-2 bg-emerald-500/10 text-emerald-500 rounded-lg group-hover:scale-110 transition-transform">
              <span class="material-symbols-outlined">settings_input_component</span>
            </div>
            <span
              class="text-[10px] font-bold text-emerald-500 bg-emerald-500/10 px-2 py-0.5 rounded uppercase">Running</span>
          </div>
          <h3 class="font-bold text-sm mb-1">LED01</h3>
          <p class="text-xs text-slate-500 mb-4">Asset ID: CNC-8821</p>
          <div class="space-y-3">
            <div class="flex justify-between text-xs">
              <span class="text-slate-400">Temperature</span>
              <span class="font-medium">45°C</span>
            </div>
            <div class="w-full bg-slate-100 dark:bg-slate-800 h-1.5 rounded-full overflow-hidden">
              <div class="bg-emerald-500 h-full w-[45%]"></div>
            </div>
            <div class="flex justify-between text-xs pt-1">
              <span class="text-slate-400">Load</span>
              <span class="font-medium">82%</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
  <!-- End main -->
</template>

<style scoped></style>
