<template>
    <div id="app">
        this is id : {{$route.params.testId}}
        <!-- <router-link to="/test/title1">标题1</router-link>
        <router-link to="/test/title2">标题2</router-link> -->
        <router-view></router-view>
        <!-- <div @click="gotoGoods">跳转到商品详情页面</div>
        <router-link v-bind:to="{name:'goods'}">用命名路由方式跳转

        </router-link> -->

    </div>
</template>
<script>
    export default{
        name:'App'
        // data(){
        //     return {
        //         msg:'hello vue'
        //     }
        // },
        // methods: {
        //     // gotoGoods(){
        //     //     this.$router.push('/goods')
        //     // }
        //     gotoGoods(){
        //         // this.$router.push({
        //         //     path:'/goods?goodsId=666'
        //         // });
        //         this.$router.push({
        //             path:'/goods',
        //             query:{
        //                 goodsId:777
        //             }
        //         })
        //     }
        // }
    }
</script>
<style scoped></style>