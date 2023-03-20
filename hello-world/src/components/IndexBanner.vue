<template>
    <div class="index-container">
        <!-- <h1>
            index content
        </h1> -->
        <video class="video">

        </video>
        <div class="page-container">
            <div  class="page-container-title">智能文字识别与理解的一站式服务平台</div>
            <p class="page-container-part1">
                <span>
                    银行 ｜
                </span>
                <span>
                    身份证 ｜
                </span>
                <span>
                    票据 ｜
                </span>
                <span>
                    自定义文档电子化
                </span>
            </p>
            <ul class="page-container-part2">
                <li>
                    · 高精度识别
                </li>
                <li>
                    · 无缝对接企业内容OA、Saas、CRM系统
                </li>
            </ul>
            <p class="page-container-more">
                <a style="margin = 40px">了解详情</a>
            </p>
        </div>
        
    </div>
</template>

<script>

</script>

<style>
    .index-container {
        top:120px;
    }
    .video {
        background-color: rgb(227, 148, 91);
        width: 100%;
        height: 500px;
        overflow-clip-margin: content-box;
        overflow: clip;
    }
    .page-container {
        margin-top:100px;
        margin-left: 150px;
        /* 可以将文字放在视频的上方 */
        position: absolute;
        transform: translateX(-50%);
        z-index: 1;
        width: 100%;
        /* height: 100%; */
        top: 50px;
        left: 50%;
        box-sizing: border-box !important;
        display: block;
    }
    .page-container-title {
        font-size: 44px;
        font-weight: 900;
        text-align: left;
        letter-spacing: 6px;
    }
    .page-container-part1 {
        text-align: left;
        font-size: 25px;
    }
    .page-container-part2 {
        padding: 0%;
    }
    .page-container-part2 > li{
        margin: 10px;
    }
    .page-container-more {
        /* text-align: left; */
        height: 40px;
        width: 120px;
        background-color: rgb(73, 73, 132);
        margin-top: 60px;
    }
    .page-container-more > a{
        text-align: center;
        line-height: 40px;
        color: white;
        font-size: 14px;
    }
</style>