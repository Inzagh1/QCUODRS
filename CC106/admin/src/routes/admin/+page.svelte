<script>
    import QCU from '../../image/QCULOGO.png';
    import Header from '../../components/header.svelte';
    import Sidebar from '../../components/sidebar.svelte';
    import Header2  from '../../components/header2.svelte';
    import { goto } from '$app/navigation';
    import Livetime from '../../components/Livetime.svelte';

    function gotoAdmin () {
                goto('/admin');
    }

</script>

<div class="h-[105vh] w-full bg-slate-300  " >
    <Header2/>
    <Sidebar/>
 
    <div class="ml-[300px] p-5 ">
        <h1 class="pl-0 text-[30px] text-black font-bold">DASHBOARD</h1>
        
            <Livetime/>
        
    </div>
    

</div>  
