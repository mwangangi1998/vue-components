<template>
    <div class="footer">
        <p>&copy; {{  CurrentYear()  }} {{ footer }}</p>
    </div>
</template>
<script>
export default{
    data() {
        return {
            footer: 'copyright ',
            // currentYear:'',
        }
    },
    methods:{
CurrentYear:function(){
return new Date().getFullYear();
}
    },
    computed:{

    },
}
</script>
<style>
.footer{
    color: #fff;
width: 100%;
    background-color: blue;
}
</style>