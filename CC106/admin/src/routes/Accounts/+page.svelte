<script>
    import { goto } from '$app/navigation';
    import Header2 from "../../components/header2.svelte";
    import Sidebar from "../../components/sidebar.svelte";
    import Pogi from "../../image/pogi.jpg";
    import BoxesAccounts from '../../components/BoxesAccounts.svelte';
    import Registrar from '../../components/registrars.svelte';

</script>

<div class="h-[105vh] w-full bg-slate-300">
  <Header2/>
  <Sidebar/>

  <div class="ml-[300px] p-5 ">
    <h1 class="pl-0 text-[30px] text-black font-bold">MANAGE ACCOUNTS<span class="float-end text-[20px] text-slate-600">REGISTRARS' ACCOUNT</span></h1>
    <!-- CONTAINER --> 
    <div class="h-[200px] w-[200] flex gap-x-5">
      <BoxesAccounts/>
     
      
      <!-- registrar --> 
     
      <div class="h-[260%] w-[80%] bg-slate-100 mx-auto mt-3 rounded-md shadow-md p-5  flex ">     
       <Registrar/>    
      </div>  

    </div>

   
    
  </div>

</div>