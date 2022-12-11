<template>


    <h1 class="text-3xl">Users</h1>
        
    <div style="margin-top: 800px">
        <p>The current time is {{time}}.</p>
    </div>
        
    <Link href="/users" class="text-blue-500" preserve-scroll>
        Refresh
    </Link>




</template>

<script>


export default {

    props: {
        time : String,

    },
};
</script>

<style>

</style>