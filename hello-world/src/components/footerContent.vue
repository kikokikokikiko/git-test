<template>
    <div class="footer">
        <div class="footer-container">
            <!-- <h1>footer</h1> -->
            <div class="footer-nav">
                <div class="footer-left">
                    <div class="footer-left-column">
                        <div class="footer-column-title">智能文字识别</div>
                        <div class="footer-column-content">
                            <a>场景智能文字识别引擎</a>
                            <a>合同机器人</a>
                            <a>通用智能文字识别引擎</a>
                            <a>财报机器人</a>
                            <a>智能图像处理引擎</a>
                            <a>企业AI管理平台</a>
                            <a>Textin Studio 结构化文字提取工具</a>
                            <a>Textin Studio Pro 智能文字识别训练平台</a>
                        </div>
                    </div>
                    <div class="footer-left-column">
                        <div class="footer-column-title">商业大数据</div>
                        <div class="footer-column-content">
                            <a>企业数据库</a>
                            <a>企业数据API</a>
                            <a>标准化服务应用</a>
                            <a>企业定制化服务</a>
                        </div>
                    </div>
                    <div class="footer-left-column">
                        <div class="footer-column-title">解决方案</div>
                        <div class="footer-column-content">
                            <a>银行</a>
                            <a>证券</a>
                            <a>保险</a>
                            <a>政府园区</a>
                            <a>供应链</a>
                        </div>
                    </div>
                    <div class="footer-left-column">
                        <div class="footer-column-title">明星产品</div>
                        <div class="footer-column-content">
                            <a>名片全能王</a>
                            <a>扫描全能王</a>
                            <a>启信宝</a>
                            <a>名片全能王-企业版</a>
                            <a>启信慧眼</a>

                        </div>
                    </div>
                    <div class="footer-left-column">
                        <div class="footer-column-title">关于合合</div>
                        <div class="footer-column-content">
                            <a>公司简介</a>
                            <a>加入合合</a>
                            <a>启信宝</a>
                            <a>安全中心</a>

                        </div>
                    </div>
                </div>
                <div class="footer-right">
                    <div class="footer-right-title">INTSIG合合信息</div>
                    <div>
                        <div class="footer-right-company-name">上海合合信息科技股份有限公司</div>
                        <div class="footer-right-company-add">地址：上海市静安区万荣路1268号云立方A座11层</div>
                        <div class="footer-right-company-tel">电话：4006611390</div>
                    </div>
                    <div class="footer-right-company-media">
                        <a class="footer-icon-weibo">微博</a>
                        <div class="footer-icon-wechat">微信</div>
                    </div>


                </div>
            </div>
            <div class="ohter">
                <div>Copyright@2023 上海合合信息科技股份有限公司 保留所有权利 </div>
                <div>不良心信息举报电话：4006611390</div>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style>
    .footer {
        background:url(../assets/img_footer.png),no-repeat;
        background-position: right;
        background-size: cover;
        color: white;
        padding: 50px 70px;

    }
    .footer-contanier {
        display: flex;
        flex-direction: column;
        margin: 0 auto;
        /* margin-left: 90px;
        margin-right: 90px; */
        /* margin: 30px; */
        padding-left: 90px;
        padding-right: 90px;
    }
    .footer-nav {
        display: flex;
        flex-direction: row;
        border-bottom: 1px solid rgba(255, 255, 255, 0.33);
        padding-bottom: 20px;
        margin-bottom: 20px;
        text-align: left;
    }
    .footer-left {
        display: flex;
        flex-direction: row;
        flex-grow: 5;
        /* text-align: left; */
        border-right: 1px solid rgba(255, 255, 255, 0.33);
        /* height: 150px; */
        /* margin-top: 40px;
        margin-bottom: 30px; */
    }
    .footer-left-column {
        display: flex;
        flex-direction: column;
        flex-grow: 2;
    }
    .footer-column-title {
        font-size: 17px;
        font-weight: 400;
        margin-bottom:20px;
    }
    .footer-column-content {
        display: flex;
        flex-direction: column;
        font-size: 14px;
    }
    .footer-column-content > a {
        margin-top: 10px;
        opacity: 0.6;
    }

    .footer-right {
        display: flex;
        width: 305px;
        flex-direction: column;
        /* text-align: left; */
        padding-left: 30px;
        /* margin-top: 40px; */
    }
    .footer-right-title {
        font-size: 22px;
        margin-bottom: 20px;

    }
    .footer-right-company-name, .footer-right-company-add, .footer-right-company-tel {
        font-size: 12px;
        opacity:0.7;
    }
    .footer-right-company-media {
        display: flex;
        flex-direction: row;
    }
    .ohter {
        text-align: left;
        /* margin-bottom: 30px; */
        font-size: 10px;
    } 

</style>