<template>
    <div class="flex justify-center bg-stone-200 gap-10 pb-10">
        <LeftSection 
            v-for="LeftItem of LeftItems" :key="LeftItem"
            v-bind:LeftItem = LeftItem
        />
        
        <div class="bg-white rounded-xl -mt-10 w-1/2">
            <RightSection 
                v-for="RightItem of RightItems" :key="RightItem"
                v-bind:RightItem = RightItem
            />
        </div>
    </div>
</template>

<script>
    import LeftSection from './LeftSection.vue';
    import RightSection from './RightSection.vue';

    export default{
        components:{
    LeftSection,
    RightSection
},
        props: ["LeftItems", "RightItems"],
    }
</script>
