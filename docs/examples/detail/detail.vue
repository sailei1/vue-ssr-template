<template>
    <div>
        详情页面
    </div>
</template>
<script>
    export  default{
        data(){
            return{
                query:0
            }
        },
        props:['data'],
        mounted(){
            let query=this.$route.query;
            console.log('detail '+ query.id);
            this.query=query;
        }
    }
</script>