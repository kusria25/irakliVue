<script>
import ListItem from './ListItem.vue'
export default{
    props:{
        list_item:{type:Array,required:true}
    },
    components:{ListItem}

}
</script>

<template>
    <ul>
        <ListItem v-for="note in list_item" :key="note.id" :text="note.title"/>
    </ul>
</template>

<style>
.mystli{
    color:red
}
</style>