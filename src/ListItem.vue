<script>
export default{
    props:{
        text:{
            type:String,
            requared:true
        }
    }
}
</script>

<template>
<li>{{ text }}</li>
</template>