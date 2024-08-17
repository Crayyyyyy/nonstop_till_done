<template>
    <div id="skills" class="tray">
        <h1 class="top">My skills ?</h1>
        <div class="skill-icons">
            <div class="icon"><img src="../../assets/icons/html.svg" alt=""></div>
            <div class="icon"><img src="../../assets/icons/css.svg" alt=""></div>
            <div class="icon"><img src="../../assets/icons/javascript.svg" alt=""></div>
            <div class="icon"><img src="../../assets/icons/bash.svg" alt=""></div>
            <div class="icon"><img src="../../assets/icons/python.svg" alt=""></div>
            <div class="icon"><img src="../../assets/icons/java.svg" alt=""></div>
            <div class="icon"><img src="../../assets/icons/github.svg" alt=""></div>
        </div>
    </div>
</template>

<style>

#skills
{
    @apply flex flex-col row-span-2 col-span-2;
}

.skill-icons
{
    @apply h-full;
    /* FLEX */
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}

.icon
{
    /* FLEX */
    display: flex;
    justify-content: center;
    align-items: center;
    
    min-width: 30%;
}

.icon img
{
    @apply w-2/3;
}


</style>