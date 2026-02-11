<template>
  <div class=" bg-[#eef1f9] h-screen print:h-auto w-screen flex flex-col justify-center items-center">
    <div class=" h-17 w-full bg-white flex justify-between items-center px-2.5 py-3 box-border border-b border-b-[#dcdbee] print:hidden!">
      <div class=" w-3/5 pl-7 font-puvi-medium box-border text-lg overflow-hidden text-nowrap text-ellipsis" title="Al Mahina LLC Building Dubai, 87654">
        Al Mahina LLC Building Dubaiy, 87654 
      </div>
      <div class=" w-2/5 flex justify-end items-center">
        <a href="" target="_blank" title="Download" class=" h-8 text-sm px-4 py-1 mr-2 shadow-[inset_0_-1px_0_#2b42a9] font-puvi-regular bg-primary-linearGradient text-black border border-[#d0d4df]  rounded-md box-border flex justify-between items-center gap-x-1.5 ">
          <svg class=" pb-px" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 32 32">
            <path fill="none" stroke="#ffff" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 22V5M9 16l7 7l7-7M9 27h14"/>
          </svg>
          <div class=" text-white">
            Download
          </div>
        </a>
        <a href="" target="_blank" title="Print" class=" h-8 text-sm px-5 py-1 mr-2  shadow-[inset_0_-1px_0_#cdd1e6] font-puvi-regular bg-default-linearGradient text-black border border-[#d0d4df]  rounded-md box-border">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24">
            <path fill="#000000" d="M7 9.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3zm0 2a.5.5 0 1 1 0-1a.5.5 0 0 1 0 1zM19.5 6H18V2.5a.5.5 0 0 0-.5-.5h-11a.5.5 0 0 0-.5.5V6H4.5A2.502 2.502 0 0 0 2 8.5V15a3.003 3.003 0 0 0 3 3h1v3.5a.5.5 0 0 0 .5.5h11a.5.5 0 0 0 .5-.5V18h1a3.003 3.003 0 0 0 3-3V8.5A2.502 2.502 0 0 0 19.5 6zM7 3h10v3H7V3zm10 18H7v-6h10v6zm4-6a2.003 2.003 0 0 1-2 2h-1v-2.5a.5.5 0 0 0-.5-.5h-11a.5.5 0 0 0-.5.5V17H5a2.003 2.003 0 0 1-2-2V8.5A1.5 1.5 0 0 1 4.5 7h15A1.5 1.5 0 0 1 21 8.5V15z"/>
          </svg>
        </a>
        <a href="" target="_blank" title="Edit Template" class=" h-8 text-sm px-5 py-1 mr-2  shadow-[inset_0_-1px_0_#cdd1e6] font-puvi-regular bg-default-linearGradient text-black border border-[#d0d4df]  rounded-md box-border">
          Edit
        </a>
      </div>
    </div>

    <div class="h-[calc(100%-60px)] print:h-auto w-full overflow-y-scroll print:overflow-hidden flex flex-col items-center py-5 print:py-0">
      <div class=" h-auto print:w-screen! shadow-xl shadow-slate-350">
        <div class=" min-h-[29.7cm] w-225 print:w-screen bg-white px-5 box-border">
          <!-- Table Content Comes Here -->
           <SPISiteSurvey/>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import SPISiteSurvey from './components/SPI Site Survey.vue';
</script>

<style >
.bg-primary-linearGradient
{
  background: transparent linear-gradient(0deg, #3954CC 0%, #5F7CFC 100%);
}
.bg-default-linearGradient
{
  background: transparent linear-gradient(180deg,#FCFCFF 1.4%,#EBEAF5 100%);
}
</style>