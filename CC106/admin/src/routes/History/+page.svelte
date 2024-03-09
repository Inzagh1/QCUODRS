<script>
    import Header2 from "../../components/header2.svelte";
    import Sidebar from "../../components/sidebar.svelte";
    import Useraccs from "../../components/useraccs.svelte";
    // @ts-ignore
    import History from "../../components/history.svelte";
</script>

<div class="h-[105vh] w-full bg-slate-300">
    <Header2/>
    <Sidebar/>
  
    <div class="ml-[300px] p-5 ">
      <h1 class="pl-0 text-[30px] text-black font-bold">HISTORY LOG</h1>
        <div class="mx-auto ">
            <History/>
        </div>
        
  
     
      
    </div>
</div>
  