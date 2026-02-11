<template>
    <table class=" w-full border-collapse font-puvi-regular">
        <thead class=" table-header-group!">
            <tr>
                <td>
                    <div class=" mt-5 border border-gray-800 w-full h-25 flex justify-around items-center">
                        <div class=" w-1/5 flex justify-center">
                            <img src="https://spectruminternational.ae/assets/Images/Logo.png" 
                            class=" h-20 "
                            alt="Spectrum Inter">
                        </div>
                        <div class=" w-1/2 font-semibold text-xl text-center">
                            SITE SURVEY FORM (AMC)
                        </div>
                        <div class=" w-3/10 text-xs font-semibold text-right pr-3">
                            SPECTRUM INTERNATIONAL LLC <br>
                            <a href="mailto:admin@spectruminternational.ae" class=" text-red-600">admin@spectruminternational.ae</a>
                        </div>
                    </div>
                </td>
            </tr>
        </thead>
        <tbody>
            <!-- Print Content -->
            <tr>
                <td >
                    <table class=" w-full border-collapse">
                        <tbody>
                            <tr>
                                <td class=" w-1/2 p-1 text-xs border border-t-0 border-gray-800">SALES PERSON:</td>
                                <td class=" w-1/2 p-1 text-xs border border-t-0 border-gray-800">DATE:</td>
                            </tr>
                            <tr>
                                <td class=" w-1/2 p-1 text-xs border border-gray-800">SITE NAME:</td>
                                <td class=" w-1/2 p-1 text-xs border border-gray-800">SITE LOCATION:</td>
                            </tr>
                            <tr>
                                <td class=" w-1/2 p-1 text-xs border border-gray-800">CONTACT DETAILS:</td>
                                <td class=" w-1/2 p-1 text-xs border border-gray-800">EXISTING SERVICE PROVIDER NAME:</td>
                            </tr>
                            <tr>
                                <td class=" w-1/2 p-1 text-xs border border-gray-800">TYPE OF BUILDING(OFF/RES/BOTH) </td>
                                <td class=" w-1/2 p-1 text-xs border border-gray-800">
                                    <div class="w-full flex justify-start items-center">
                                        <div class=" w-7/10">TOTAL NUMBER OF BUILDINGS:</div>
                                        <div class=" w-3/10">BLOCKS:</div>
                                    </div>
                                </td>
                            </tr>
                            <tr>
                                <td class=" w-1/2 p-1 text-xs border border-gray-800">TOTAL NUMBER OF APARTMENTS:</td>
                                <td class=" w-1/2 p-1 text-xs border border-gray-800">BUILDING STRUCTURE AND FLOORS:</td>
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>

            <tr>
                <td>
                    <table class=" w-full border-collapse">
                        <thead>
                            <tr>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/20">SN</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-7/20 text-left">FIRE ALARM SYSTEM DETAILS</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/5 ">BRAND & TYPE</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/10">QUANTITY</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-3/10">STATUS/REMARKS</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">1</td>
                                <td class="p-1 text-xs border border-gray-800">FIRE ALARM CONTROL PANEL</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800" rowspan="2">LOOP/ZONE:</td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">2</td>
                                <td class="p-1 text-xs border border-gray-800">SUB PANELS/GRAPHIC PC</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">3</td>
                                <td class="p-1 text-xs border border-gray-800">SMOKE DETECTOR</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">4</td>
                                <td class="p-1 text-xs border border-gray-800">HEAT DETECTOR</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">5</td>
                                <td class="p-1 text-xs border border-gray-800">BREAK GLASS UNIT</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">6</td>
                                <td class="p-1 text-xs border border-gray-800">BELL/SOUNDER</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">7</td>
                                <td class="p-1 text-xs border border-gray-800">PAVA SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">8</td>
                                <td class="p-1 text-xs border border-gray-800">FIRE TELEPHONE</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">9</td>
                                <td class="p-1 text-xs border border-gray-800">SPEAKER</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">10</td>
                                <td class="p-1 text-xs border border-gray-800">AIR SAMPLING SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>

            <tr>
                <td>
                    <table class=" w-full border-collapse">
                        <thead>
                            <tr>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/20">SN</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-7/20 text-left">EMERGENCY LIGHT SYSTEM DETAILS</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/5">BRAND & TYPE</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/10">QUANTITY</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-3/10">STATUS/REMARKS</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">1</td>
                                <td class="p-1 text-xs border border-gray-800">CBS PANELS</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">2</td>
                                <td class="p-1 text-xs border border-gray-800">SUB PANELS/GRAPHIC PC</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">3</td>
                                <td class="p-1 text-xs border border-gray-800">EMERGENCY LIGHT</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">4</td>
                                <td class="p-1 text-xs border border-gray-800">EXIT LIGHT</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">5</td>
                                <td class="p-1 text-xs border border-gray-800">MODULES/CIRCUIT DETAILS</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">6</td>
                                <td class="p-1 text-xs border border-gray-800">MORE SYSTEM DETAILS</td>
                                <td class="p-1 text-xs border border-gray-800" colspan="3"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>

            <tr>
                <td>
                    <table class=" w-full border-collapse">
                        <thead>
                            <tr>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/20">SN</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-7/20 text-left">FIRE FIGHTING SYSTEM DETAILS</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/5 ">BRAND & TYPE</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/10">QUANTITY</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-3/10">STATUS/REMARKS</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">1</td>
                                <td class="p-1 text-xs border border-gray-800">DRY POWDER FIRE EXTINGUISHER</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800" rowspan="3"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">2</td>
                                <td class="p-1 text-xs border border-gray-800">CO2 FIRE EXTINGUISHER</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">3</td>
                                <td class="p-1 text-xs border border-gray-800">WATER EXTINGUISHER 9L</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">4</td>
                                <td class="p-1 text-xs border border-gray-800">FIRE HOSE REEL</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">5</td>
                                <td class="p-1 text-xs border border-gray-800">Coiled FH / Landing Valves</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">6</td>
                                <td class="p-1 text-xs border border-gray-800">Apt. FIRE EXTINGUISHERS</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">7</td>
                                <td class="p-1 text-xs border border-gray-800">SPRINKLERS</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">8</td>
                                <td class="p-1 text-xs border border-gray-800">ZONE CONTROL VALVE</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">9</td>
                                <td class="p-1 text-xs border border-gray-800">FIRE HYDRANTS</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">10</td>
                                <td class="p-1 text-xs border border-gray-800">BREECHING INLET</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800" rowspan="6"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">11</td>
                                <td class="p-1 text-xs border border-gray-800">FM200/ AEROSOL SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">12</td>
                                <td class="p-1 text-xs border border-gray-800">KITCHEN HOOD SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">13</td>
                                <td class="p-1 text-xs border border-gray-800">PREACTION SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">14</td>
                                <td class="p-1 text-xs border border-gray-800">DELUGE SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">15</td>
                                <td class="p-1 text-xs border border-gray-800">FOAM SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>

            <tr>
                <td>
                    <table class=" w-full border-collapse">
                        <thead>
                            <tr>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/20">SN</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-7/20 text-left">FIRE PUMP SYSTEM DETAILS</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/5 ">BRAND & TYPE</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/10">QUANTITY</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-3/10">STATUS/REMARKS</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">1</td>
                                <td class="p-1 text-xs border border-gray-800">JOCKEY PUMP</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800" rowspan="3"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">2</td>
                                <td class="p-1 text-xs border border-gray-800">ELECTRIC PUMP</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">3</td>
                                <td class="p-1 text-xs border border-gray-800">DIESEL PUMP</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>

            <tr>
                <td>
                    <table class=" w-full border-collapse">
                        <thead>
                            <tr>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 text-left">MANPOWER DETAILS</th>
                            </tr>
                        </thead>
                        <tbody>

                        </tbody>
                    </table>
                </td>
            </tr>

            <tr>
                <td>
                    <table class=" w-full border-collapse">
                        <thead>
                            <tr>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-1/20">SN</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-7/20 text-left">SYSTEM TYPE</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-3/10">REQUIRED MANPOWER</th>
                                <th class=" p-1 text-xs border border-t-0 border-gray-800 w-3/10">REMARKS</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">1</td>
                                <td class="p-1 text-xs border border-gray-800">FIRE ALARM SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <td class="p-1 text-xs border border-gray-800" rowspan="3"></td>
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">2</td>
                                <td class="p-1 text-xs border border-gray-800">FIRE FIGHTING SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                            <tr>
                                <td class="p-1 text-xs border border-gray-800 text-center">3</td>
                                <td class="p-1 text-xs border border-gray-800">CBS SYSTEM</td>
                                <td class="p-1 text-xs border border-gray-800"></td>
                                <!-- <td class="p-1 text-xs border border-gray-800"></td> -->
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>

            <tr>
                <td>
                    <table class=" w-full border-collapse">
                        <tbody>
                            <tr>
                                <td class="p-1 text-[10px] border border-t-0 border-gray-800 w-2/5 h-12"><b>REMARKS/COMMENTS(IF ANY):</b></td>
                                <td class="p-1 text-[10px] border border-t-0 border-gray-800 w-3/10 h-12"><b>ENGINEER NAME & SIGN:</b></td>
                                <td class="p-1 text-[10px] border border-t-0 border-gray-800 w-3/10 h-12"><b>APPROVED BY:</b></td>
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>
        </tbody>
        <tfoot class=" table-footer-group!">
            <tr>
                <td>
                    <div class="w-full mb-5 text-xs text-right">
                        FORM 72 - 01- 01- REV C
                    </div>
                </td>
            </tr>
        </tfoot>
    </table>
</template>

<script setup>

</script>

<style>
td
{
    align-content: start;
}
</style>