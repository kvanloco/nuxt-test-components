<template>
  <table class="w-full ">
    <tbody>
      <tr>
        <td class="bg-gray-100 border ">
          <div class="flex items-center justify-center">

            <img src="img/calendar.png" alt="Calender image">
          </div>
          </td>
        <td class="p-2 border">
            <div class="text-xl pt-2">Voorjaars hapje/tapje</div>
            <div class="text-blue-500 text-sm pb-2"><a href="#">Bekijken op Agenda</a></div>
            <table>
                <tbody>
                    <tr>
                        <td class="text-gray-500 pr-2">Wanneer</td>
                        <td>Do 15 juni 2023 17:00 - 20:00 (CEST)</td>
                    
                    </tr>
                    <tr>
                        <td class="text-gray-500 pr-2">Waar</td>
                        <td>Geel</td>
                    </tr>
                    <tr>
                        <td class="text-gray-500 pr-2">Wie</td>
                        <td>Jan, Mieke, John doe, Jane Doe, </td>
                    </tr>
                </tbody>
            </table>
            <div class="p-2 flex gap-2 items-center">
                <button class="px-5  py-2 bg-green-500 text-white rounded font-semibold">Ja</button>
                <button class="px-5  py-2 border rounded font-semibold">Misschien</button>
                <button class="px-5  py-2 border rounded font-semibold">Nee</button>
                <div class="font-semibold">Meer opties</div>
            </div>
        </td>
        <td class="border">
          <div class="p-2 flex flex-col justify-items-start">
            <div class="text-xl pt-2">Agenda</div>
            <div class="text-sm text-gray-500 pb-2">do 15 jun 2023</div>
            <div class="text-gray-500 italic">Geen eerdere gebeurtenissen</div>
            <div> 
              <table>
                <tbody>
                  <tr>
                    <td>17:00</td>
                    <td>Voorjaars hapje/tapje</td>

                  </tr>
                </tbody>
              </table>
              
            </div>
            <div>Geen latere gebeurtenissen</div>
          </div>
        </td>
      </tr>
    </tbody>
  </table>
</template>
