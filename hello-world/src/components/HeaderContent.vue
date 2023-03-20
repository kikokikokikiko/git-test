<template>
    <div class="head-container">
        <a class="logo">
            <img src="../assets/logo.jpg">
            <!-- <div class="logo-name">合合信息</div> -->
        </a>
        <ul class="nav">
            <li>
                <a>首页</a>
            </li>
            <li>
                <a>智能文字识别</a>
            </li>
            <li>
                <a>商业大数据</a>
            </li>
            <li>
                <a>解决方案</a>
            </li>
            <li>
                <a>明星产品</a>
            </li>
            <li>
                <a>关于合合信息</a>
            </li>
        </ul>
        <div class="language">English</div>
    </div>
</template>

<script>

</script>

<style>
    .head-container {
        display: flex !important;
        flex-direction: row;
        width: 100%;
        height: 64px !important;
        background-color: rgba(232, 235, 245, 0.3) !important;
        position: fixed;       
        /* position啥意思 固定？*/
        top: 0;
        left: 0;
        min-width: 1080px;
        box-shadow: 0px 3px 6px 0px rgba(0, 0, 0, 0.1);
        padding-left: 100px;
        /* margin-right: 100px; */
        opacity: 3;

    }
    .header-containner {
        height: 100%;
        display: flex;
    }
    .logo {
        display: flex;
        flex-grow: 1;
        background-image: url(../assets/logo.jpg) center;
    }
    .logo > img {
        margin: 15px 20px;
    }
    .nav {
        display: flex;
        flex-grow: 6;
        height: 100%;
        margin: 0;
        align-items: center;
        padding-left: 0%;
    }
    .language {
        display: flex;
        flex-grow: 1;
        text-align: center;
        align-items: center;
    }
    li {
        display:flex;
        flex-grow: 1;
        /* padding:0 10px; */
        height:100%;
        align-items: center;
    }
</style>