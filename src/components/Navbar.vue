<template>
    <div class="parent">
        <div class="navbar-routes">Home</div>
        <div class="navbar-routes">Completed</div>
        <div class="navbar-routes">Pending</div>
        <div class="navbar-routes">In Progress</div>
    </div>
</template>

<script setup></script>
<style scoped>
.parent{
    height:5rem;
    width: 100vw;
    display: flex;
    gap: 2rem;
    justify-content: center;
    align-items: center;
    background: rgb(2,0,36);
    background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(241,92,92,1) 0%, rgba(0,212,255,1) 100%);
}

.navbar-routes{
    color: #ffffff;
    font-weight: 700;
    cursor: pointer;
    font-size: 1.3rem;
}
</style>