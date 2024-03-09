<script>
      import { goto } from '$app/navigation';
      import Pogi from "../image/pogi.jpg";
      import Icon from '../image/usericon.png';
      import Iconpic from '../image/ICON.png';
      
      
      function gotoDetails (){
                goto('/Details')
      }
      
</script>
<div class="overflow-x-auto  w-[200%]">
    <table class="table ">
      <!-- head -->
      <thead class="top-0 sticky bg-slate-900 z-30">
        <tr>
       
          <th class="text-white text-[15px]">FULL NAME</th>
          <th class="text-white text-[15px]">POSITION</th>
          <th class="text-white text-[15px]">ID</th>
          <th class="text-white text-[15px]">MANAGE</th>
        </tr>
      </thead>
      <tbody> 
        <!-- row 1 -->
        <tr>
        
          <td>
            <div class="flex items-center gap-3">
              <div class="avatar">
                <div class=" w-12 h-12">
                  <img src={Iconpic} alt=""/>
                </div>
              </div>
              <div>
                <div class="text font-bold">Hart Hagerty</div>
                <div class="text text-sm opacity-50">United States</div>
              </div>
            </div>
          </td>
          <td>
            
            <span class="badge badge-ghost badge-sm h-7">CCS registrar 1</span>
          </td>
          <td>REG-101</td>
          <th>
            <button on:click={gotoDetails} class="btn btn-ghost btn-xs hover:bg-[#000450] hover:text-teal-100">DETAILS</button>
          </th>
        </tr>
        <!-- row 2 -->
        <tr>
        
          <td>
            <div class="flex items-center gap-3">
              <div class="avatar">
                <div class="mask mask-squircle w-12 h-12 ">
                  <img src={Iconpic} alt=""/>
                </div>
              </div>
              <div>
                <div class="text font-bold">Hart Hagerty</div>
                <div class="text text-sm opacity-50">United States</div>
              </div>
            </div>
          </td>
          <td>
            
            <span class="badge badge-ghost badge-sm h-7">CCS registrar 1</span>
          </td>
          <td>REG-101</td>
          <th>
            <button class="btn btn-ghost btn-xs hover:bg-[#000450] hover:text-teal-100">DETAILS</button>
          </th>
        </tr>
        <!-- row 3 -->
        <tr>
         
          <td>
            <div class="flex items-center gap-3">
              <div class="avatar">
                <div class="mask mask-squircle w-12 h-12">
                  <img src={Iconpic} alt=""/>
                </div>
              </div>
              <div>
                <div class="font-bold">Marjy Ferencz</div>
                <div class="text-sm opacity-50">Russia</div>
              </div>
            </div>
          </td>
          <td>
            
            <span class="badge badge-ghost badge-sm h-7">EDUK registrar 1</span>
          </td>
          <td>REG-103</td>
          <th>
            <button class="btn btn-ghost btn-xs hover:bg-[#000450] hover:text-teal-100">DETAILS</button>
          </th>
        </tr>
        <!-- row 4 -->
        <tr>
          
          <td>
            <div class="flex items-center gap-3">
              <div class="avatar">
                <div class="mask mask-squircle w-12 h-12">
                  <img src={Iconpic} alt=""/>
                </div>
              </div>
              <div>
                <div class="font-bold">Yancy Tear</div>
                <div class="text-sm opacity-50">Brazil</div>
              </div>
            </div>
          </td>
          <td>
           
            <span class="badge badge-ghost badge-sm h-7">CBAA registrar 1</span>
          </td>
          <td>REG-104</td>
          <th>
            <button class="btn btn-ghost btn-xs hover:bg-[#000450] hover:text-teal-100">DETAILS</button>
          </th>
        </tr>
        <tr>
          
          <td>
            <div class="flex items-center gap-3">
              <div class="avatar">
                <div class="mask mask-squircle w-12 h-12">
                  <img src={Iconpic} alt=""/>
                </div>
              </div>
              <div>
                <div class="font-bold">Baby Calma</div>
                <div class="text-sm opacity-50">Philippines</div>
              </div>
            </div>
          </td>
          <td>
            
            <span class="badge badge-ghost badge-sm h-7">COE registrar 1</span>
          </td>
          <td>REG-105</td>
          <th>
            <button class="btn btn-ghost btn-xs hover:bg-[#000450] hover:text-teal-100">DETAILS</button>
          </th>
        </tr>
        <tr>
          
          <td>
            <div class="flex items-center gap-3">
              <div class="avatar">
                <div class="mask mask-squircle w-12 h-12">
                  <img src={Iconpic} alt=""/>
                </div>
              </div>
              <div>
                <div class="font-bold">Brice Swyre</div>
                <div class="text-sm opacity-50">China</div>
              </div>
            </div>
          </td>
          <td>
            
            <span class="badge badge-ghost badge-sm h-7">COE registrar 1</span>
          </td>
          <td>REG-106</td>
          <th>
            <button class="btn btn-ghost btn-xs hover:bg-[#000450] hover:text-teal-100">DETAILS</button>
          </th>
        </tr>
        <tr>
          
          <td>
            <div class="flex items-center gap-3">
              <div class="avatar">
                <div class="mask mask-squircle w-12 h-12">
                  <img src={Iconpic} alt=""/>
                </div>
              </div>
              <div>
                <div class="font-bold">Brice Swyre</div>
                <div class="text-sm opacity-50">China</div>
              </div>
            </div>
          </td>
          <td>
            
            <span class="badge badge-ghost badge-sm h-7">COE registrar 1</span>
          </td>
          <td>REG-107</td>
          <th>
            <button class="btn btn-ghost btn-xs hover:bg-[#000450] hover:text-teal-100">DETAILS</button>
          </th>
        </tr>
      </tbody>
      <!-- foot -->
     
      
    </table>
  </div>