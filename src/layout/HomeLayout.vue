<template>
    <div class="home rflex">
        <left_menu></left_menu>
        <div class="menu_right wflex el-scrollbar" ref="menu_right" width="200px">
            <div class="menu_content" ref="menu_content">
                <router-view></router-view><!--页面渲染入口-->
            </div>
        </div>
    </div>
</template>

<script>
    import left_menu from "./LeftMenu.vue";

    export default {
        name: 'homelayout',
        data(){
            return {
            }
        },
        computed:{
        },
        components:{
            left_menu,
        },
        created() {
        },
        mounted (){
        },
        watch:{

        }
    }
</script>