<script>
    import { goto } from '$app/navigation';
    import Header2 from "../../components/header2.svelte";
    import Sidebar from "../../components/sidebar.svelte";
    
    import Pogi from "../../image/pogi.jpg";
    // @ts-ignore
    import BoxesAccounts from '../../components/BoxesAccounts.svelte';




</script>
<div class="h-[105vh] w-full bg-slate-300">
  <Header2/>
  <Sidebar/>

  <div class="ml-[300px] p-5 ">
    <h1 class="pl-0 text-[30px] text-black font-bold">MANAGE ACCOUNTS</h1>
    <!-- CONTAINER --> 
    <div class="h-[200px] w-[200] flex gap-x-5">
      <BoxesAccounts/>
     
      <!--ADD REGISTRAR ACCOUNT-->
      <div class="h-[260%] w-[80%] bg-slate-100  mt-3 rounded-md shadow-md p-5">
        <div class="w-full pl-10 ">
          <h1 class=" text-slate-900 text-[25px]  font-bold ">ADD REGISTRAR ACCOUNT</h1>
        </div>
        <!--form for registrar entry-->
        <div class=" flex w-full pl-10 pr-10 pt-5 gap-14 ">
            <div class="w-full p-1 ">
              <label class="form-control w-full max-w-xs  ">
                <div class="label">
                  <span class="label-text text-black text-[15px] font-medium ">Full name:</span>
                </div>
                <input type="text" placeholder="Type here"  class="text-black bg-slate-300 input w-full max-w-xs shadow-sm border-[0.5px] border-[#0a0a0a2b]" required />
              </label>

              <label class="form-control w-full max-w-xs pt-4 ">
                <div class="label">
                  <span class="label-text text-black text-[15px] font-medium">Username:</span>
                </div>
                <input type="text" placeholder="Type here"  class="text-black bg-slate-300 input w-full max-w-xs shadow-sm border-[0.5px] border-[#0a0a0a2b] " />
              </label>

              <label class="form-control w-full max-w-xs pt-4 ">
                <div class="label">
                  <span class="label-text text-black text-[15px] font-medium">Position:</span>
                </div>
                <input type="text" placeholder="Type here"  class="text-black bg-slate-300 input w-full max-w-xs shadow-sm border-[0.5px] border-[#0a0a0a2b] " />
              </label>
            </div>
            <div class="w-full  p-1">
              <label class="form-control w-full max-w-xs ">
                <div class="label">
                  <span class="label-text text-black text-[15px] font-medium ">Pasword:</span>
                </div>
                <input type="password" placeholder="Type here"  class="text-black bg-slate-300 input w-full max-w-xs shadow-sm border-[0.5px] border-[#0a0a0a2b]" />
              </label>   
              <label class="form-control w-full max-w-xs pt-4">
                <div class="label">
                  <span class="label-text text-black text-[15px] font-medium ">Confirm Pasword:</span>
                </div>
                <input type="password" placeholder="Type here"  class="text-black bg-slate-300 input w-full max-w-xs shadow-sm border-[0.5px] border-[#0a0a0a2b]" />
              </label> 
          
              
            </div>
            
      </div>
      <div class="p-8 pr-14 float-right">
        <button onclick="my_modal_6.showModal()" class="btn btn-active shadow-md">SUBMIT</button>
        <dialog id="my_modal_6" class="modal modal-bottom sm:modal-middle">
          <div class="modal-box">
            <h3 class="font-bold text-lg text-blue-700">ADD</h3>
            <p class="py-4">Are you sure want to ADD this account? </p>
            <div class="modal-action">
              <form method="dialog">
                <!-- if there is a button in form, it will close the modal -->
                <button onclick="my_modal_10.showModal()" class="btn">Yes</button>
                <button  class="btn">Close</button>
                <dialog id="my_modal_10" class="modal">
                  <div class="modal-box">
                    <h3 class="font-bold text-lg text-blue-700 ">Added</h3>
                    <p class="py-4">Account CREATED</p>
                  </div>
                  <form method="dialog" class="modal-backdrop">
                    <button>close</button>
                  </form>
                </dialog>
              </form>
            </div>
          </div>
        </dialog>
        
      </div>
      

      </div>  

    </div>

   
    
  </div>

</div>