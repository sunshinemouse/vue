<template>
    <div class="tmpl">
        {{msg}}
        <router-link to="/lgoin">登录</router-link>
        <router-link to="/lgoin">注册</router-link>
        <!--组件占位-->
        <router-view></router-view>
    </div>
</template>
<script>
    //利用es6语法定义并且导出一vm对象
    export  default{
////        es5语法的方法定义的写法
//        data:function () {
//            return{
//                msg:'这是vue组件'
//            }
//
//        }
//        es6的方法定义的写法
        data(){
            return{
                msg:'这是vue组件'
            }
        }
    }

</script>
<style scoped>
    .tmpl{
        color:red;
    }
</style>