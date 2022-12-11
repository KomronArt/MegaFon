<template>
    <div class="bg-white rounded-xl h-36 -mt-10 w-1/4">
            <div class="h-32 leading-9">
                <p class="text-neutral-400 pl-10 pt-4">{{LeftItem.title}}</p>
                <p class="text-3xl font-extrabold text-zinc-800 pl-10">{{LeftItem.value}}</p>
                <a href="#" class="text-cyan-400 text-sm font-semibold pl-10 ">{{LeftItem.option}}</a>
            </div>
        </div>
</template>

<script>
    export default{
        props:{
            LeftItem:{
                type: Object,
            }
        }
    }
</script>