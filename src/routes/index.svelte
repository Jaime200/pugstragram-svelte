<script>
import { onMount } from 'svelte'
import Header from '../components/Header.svelte'
import Main from '../components/Main.svelte'
import TimeLine from '../components/TimeLine.svelte'
import Sidebar from '../components/Sidebar.svelte'

let data = {}
const API = 'https://us-central1-pugstagram-co.cloudfunctions.net/data';

onMount(async ()=>{
  try {
    const response = await fetch(API);  
    data = await response.json();
  } catch (error) {
    
  }
  
})

</script>


<Header />
<Main>
  <TimeLine posts= {data.posts} />
  {#if data.user}
  <Sidebar {...data.user}/>
  {/if}
</Main>