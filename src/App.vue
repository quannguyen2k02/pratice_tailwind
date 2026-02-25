<script setup></script>

<template>
  <aside class="w-50 flex flex-col border-r border-gray-800">
    <div class="flex h-20 items-center mx-6 ">
      <h1 class="font-black">WVN</h1>
    </div>
    <div class="flex-1">
      <nav class="flex flex-col ml-2 ">
        <div class="text-xs font-semibold text-slate-400 px-3 mb-2">MAIN MENU</div>
        <a class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span class="material-symbols-outlined">dashboard</span>Dashboard</a>
        <a class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span class="material-symbols-outlined">build</span>Maintenance</a>
        <a class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span class="material-symbols-outlined">inventory</span>Inventory</a>
        <a class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span class="material-symbols-outlined">analytics</span>Analysis</a>
      </nav>
      <nav class="flex flex-col ml-2 mt-5 ">
        <div class="text-xs font-semibold text-slate-400 px-3 mb-2">SYSTEM</div>
        <a class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span class="material-symbols-outlined">settings_b_roll</span>Setting</a>
        <a class="p-3 text-xl flex items-center font-semibold text-slate-400 gap-4  rounded-lg hover:bg-gray-700 cursor-pointer"><span class="material-symbols-outlined">build</span>Maintenance</a>
        
      </nav>
    </div>

    <div class="p-6 border-t broder-r border-gray-800">
      <div class="flex py-2 bg-gray-800  flex-col items-center   rounded-lg">
        <span class="text-sm font-semibold">Marc Nguyen</span>
        <span class="text-xs text-slate-500">PM</span>
      </div>
    </div>
  </aside>


</template>

<style scoped></style>
