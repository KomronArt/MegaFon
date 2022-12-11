<template>
    <div class="h-32 leading-9">
        <p class="text-neutral-400 pl-10 pt-4">{{RightItem.title}}</p>
        <p class="text-3xl font-extrabold text-zinc-800 pl-10">{{RightItem.value}}</p>
        <a href="" class="text-cyan-400 text-sm font-semibold pl-10">{{RightItem.option}}</a>
    </div>
</template>

<script>
    export default{
        props:{
            RightItem:{
                type: Object,
            }
        }
    }
</script>