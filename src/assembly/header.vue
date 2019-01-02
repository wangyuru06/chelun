<template>
    <div class="header">
        <img src="@/assets/logo1.png" alt="">
        <span>产品</span>
        <ul class="pcnav">
            <li>关于我们</li>
            <li>大数据</li>
            <li>新闻</li>
            <li>招聘</li>
            <li>商城</li>
        </ul>
        <a href="#">登录/注册</a>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.header {
    width: 100%;
    height: .6rem;
    position: fixed;
    left: 0;
    top:0;
    display: flex;
    align-items: center;
    border:1px solid #ccc;
    font-size: 20px;
    text-align: center;
    padding: 0 .6rem 0 .6rem;
    z-index: 999;
}
.header img{
    width: 120px;
    height: 60px;
}
.header ul{
    display: flex;
}
.header ul li{
    width: .6rem;
}
.header span{
    width: .8rem;
    margin-left: .4rem;
}
@media screen and (max-width: 800px) {
    
}
</style>
