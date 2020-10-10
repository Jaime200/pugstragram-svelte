<script>
import Header from '../components/Header.svelte'
import Main from '../components/Main.svelte'
import TimeLine from '../components/TimeLine.svelte'
import Sidebar from '../components/Sidebar.svelte'
</script>

<style>
    :global(body){
        background-color: #676778;
        /* color: white; */
        background-color: #fafafa;
        color: rgba(38, 38, 38, 0.7);
        font-family: "Lato", sans-serif;
        margin: 0;
        padding: 0;
    }
</style>

<Header />
<Main>
  <TimeLine />
  <Sidebar />
</Main>