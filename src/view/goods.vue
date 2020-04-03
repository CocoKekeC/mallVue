<template>
    <div class="goods">
        This is goods
        <span>{{$route.query.goodsId}}</span>
        <button @click="go">点击按钮</button>
    </div>
</template>
<script>
    export default {
        methods: {
            go(){
                this.$router.go(-1)
            }
        },
    }
</script>
<style scoped>

</style>