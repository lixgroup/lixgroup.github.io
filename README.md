# lixgroup.github.io
<!DOCTYPE html>
<html lang="zh-cn">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no"
    />
    <meta name="apple-mobile-web-app-status-bar-style" content="black" />
    <meta name="format-detection" content="email=no" />
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="format-detection" content="telephone=no" />
    <meta name="renderer" content="webkit">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <meta name="apple-mobile-web-app-title" content="Amaze UI" />
    <meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate" />
    <meta http-equiv="Pragma" content="no-cache" />
    <meta http-equiv="Expires" content="0" />
    <title>[简历]张大侠-前端开发工程师/杭州</title>
    <link rel="shortcut icon" href="assets/images/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="assets/css/typo.css">
    <link rel="stylesheet" href="assets/css/font-awesome.min.css">
    <link rel="stylesheet" href="assets/css/index.css">
    <script>
        function loading() {
            document.getElementsByClassName('avatar')[0].style.display = 'block';
            document.getElementsByClassName('loading')[0].style.display = 'none';
        }
    </script>
</head>

<body>

    <header class="header"></header>

    <article class="container">
        <section class="side" id="side">

            <!-- 左栏固定开关，记得及时删除这段代码 Start-->
            <label class="switch" style="display: none;" onchange="switchFixed()">
                <script type="text/javaScript">
                    function switchFixed(){
                        var value = document.getElementById('side').style.position === 'fixed' ? 'absolute' : 'fixed';
                        document.getElementById('side').style.position = value;
                    }
                </script>
                <input id="cb" type="checkbox">
                <span class="slider round"></span>
            </label>
            <style>
                @media (min-width: 	750px){
                    .switch{position:relative;display:inline-block!important;width:60px;height:34px;}
                    .switch input{display:none;}
                    .slider{position:absolute;cursor:pointer;top:0;left:0;right:0;bottom:0;background-color:#ccc;-webkit-transition:.4s;transition:.4s;}
                    .slider:before{position:absolute;content:"";height:26px;width:26px;left:4px;bottom:4px;background-color:white;-webkit-transition:.4s;transition:.4s;}
                    input:checked + .slider{background-color:#1abc9c;}
                    input:focus + .slider{box-shadow:0 0 1px #1abc9c;}
                    input:checked + .slider:before{-webkit-transform:translateX(26px);-ms-transform:translateX(26px);transform:translateX(26px);}.slider.round{border-radius:34px;}
                    .slider.round:before{border-radius:50%;}
                }
            </style>
            <!-- 左侧固定开关，记得及时删除这段代码 End-->

            <!-- 个人肖像 -->
            <section class="me">
                <section class="portrait">
                    <div class="loading">
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>
                    <!-- 头像照片 -->
                    <img class="avatar" src="assets/images/avatar.jpg" onload="loading()">
                </section>

                <h1 class="name">张大侠</h1>
                <h4 class="info-job">前端开发工程师 / 杭州</h4>

            </section>

            <!-- 基本信息 -->
            <section class="profile info-unit">
                <h2>
                    <i class="fa fa-user" aria-hidden="true"></i>基本信息</h2>
                <hr/>
                <ul>
                    <li>
                        <label>个人信息</label>
                        <span>张大侠 / 男 / 24岁</span>
                    </li>
                    <li>
                        <label>英语水平</label>
                        <span>CET-6</span>
                    </li>
                    <li>
                        <label>计算机水平</label>
                        <span>软考中级</span>
                    </li>
                </ul>
            </section>

            <!-- 联系方式 -->
            <section class="contact info-unit">
                <h2>
                    <i class="fa fa-phone" aria-hidden="true"></i>联系方式</h2>
                <hr/>
                <ul>
                    <li>
                        <label>手机</label>
                        <a href="tel:15168285219" target="_blank">151-6828-5219</a>
                    </li>
                    <li>
                        <label>邮箱</label>
                        <a href="mailto:ze.zh@hotmail.com" target="_blank">ze.zh@hotmail.com</a>
                    </li>
                    <li>
                        <label>个人主页</label>
                        <a href="http://0b11111110.com/" target="_blank">0b11111110.com/</a>
                    </li>
                    <li>
                        <label>Github</label>
                        <a href="https://github.com/0b11111110" target="_blank">github.com/0b11111110</a>
                    </li>
                </ul>
            </section>

            <!-- 技能点 -->
            <section class="skill info-unit">
                <h2>
                    <i class="fa fa-code" aria-hidden="true"></i>技能点</h2>
                <hr/>
                <ul>
                    <li>
                        <label>HTML</label>
                        <progress value="90" max="100"></progress>
                    </li>
                    <li>
                        <label>CSS</label>
                        <progress value="85" max="100"></progress>
                    </li>
                    <li>
                        <label>JavaScript</label>
                        <progress value="85" max="100"></progress>
                    </li>
                    <li>
                        <label>React</label>
                        <progress value="85" max="100"></progress>
                    </li>
                    <li>
                        <label>Node.js</label>
                        <progress value="70" max="100"></progress>
                    </li>
                    <li>
                        <label>小程序</label>
                        <progress value="70" max="100"></progress>
                    </li>
                </ul>
            </section>

            <section class="qrcode info-unit">
                <h2><i class="fa fa-qrcode" aria-hidden="true"></i>二维码</h2>
                <hr/>
                <img src="https://github.com/if2er/FeZaoDuKe-Collection/blob/master/ifeees.jpg?raw=true" style="width: 100%;" alt="">
            </section>

            <!-- 技术栈 -->
            <!-- <div class="stack info-unit">
                    <h2><i class="fa fa-code" aria-hidden="true"></i>其他</h2>
                    <hr/>
                    <ul>
                        <li>
                            <label>前端</label>
                            <span>React、jQuery、微信小程序、Bootstrap、SASS、LESS</span>
                        </li>
                        <li>
                            <label>后端</label>
                            <span>Node.js、MySQL、MongoDB、WordPress、ThinkPHP</span>
                        </li>
                        <li>
                            <label>其他</label>
                            <span>Git、SVN、Markdown</span>
                        </li>
                    </ul>
                </div> -->
        </section>

        <section class="main">

            <!-- 教育经历 -->
            <section class="edu info-unit">
                <h2>
                    <i class="fa fa-graduation-cap" aria-hidden="true"></i>教育经历</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>XXXX大学 - XXX专业（硕士）</span>
                            <time>201X.9-201X.7</time>
                        </h3>
                        <p>专业排名
                            <mark>X/XX</mark>，期间发表国际会议英文摘要X篇，国内核心期刊文章X篇（其中第一作者X篇），获XXX，XXX2次，XXX2次。(此处根据自身情况填写，可以突出自己的亮点，或者跟求职目标相关的内容)</p>
                    </li>
                    <li>
                        <h3>
                            <span>XXXX大学 - XXX专业（本科）</span>
                            <time>201X.9-201X.7</time>
                        </h3>
                        <p>专业排名
                            <mark>X/XX</mark>，期间发表国内核心期刊文章X篇，三等奖学金X次。</p>
                    </li>
                </ul>
            </section>

            <!-- 工作经历 -->
            <section class="work info-unit">
                <h2>
                    <i class="fa fa-shopping-bag" aria-hidden="true"></i>工作经历</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>[经历1]XX公司－前端开发工程师（实习）</span>
                            <time>2016.X 至 2017.X</time>
                        </h3>
                        <ul class="info-content">
                            <li>深度参与XX项目迭代XX的前端开发工作，独立承担并完成XX、XX、XXXX等功能点的开发，主要维护并修复XX、XX、XX等功能点bug若干。项目采用技术栈
                                <mark>React+React Router+Node.js+SASS</mark>，实现
                                <mark>前后端完全分离</mark>。</li>
                            <li>配合UI和后端，根据产品需求提供H5页面嵌入到后台模板，要求
                                <mark>移动端显示正常</mark>。</li>
                            <li>主要参与XXXXXXX的静态页面开发工作，要求
                                <mark>在支付宝环境下完全兼容</mark>。</li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>[经历2]XX－前端开发工程师（实习）</span>
                            <time>20XX.10-20XX.7</time>
                        </h3>
                        <ul class="info-content">
                            <li>深度参与公司主线产品「XXXX」的前端开发工作，完成帖子快捷回复、
                                <mark>全站图片懒加载</mark>、活动banner、帖子管理（使用Yii框架）等功能。项目采用技术栈phpWind+NAMP。
                                <a href="http://itsay.tech/162/" target="_blank">
                                    <i class="fa fa-link" aria-hidden="true"></i>博客文章</a>。</li>
                            <li>主要参与公司产品「XXXX」的前端开发工作，实现接入微博、微信、QQ等
                                <mark>第三方账号登录</mark>等功能。项目采用技术栈WordPress+NAMP。</li>
                            <li>活动页面的开发（七夕活动、抽奖活动以及承接外包页面）。</li>
                            <li>论坛
                                <mark>图片增量备份</mark>（CentOS+vsftpd+crontab）
                                <a href="#" target="_blank">
                                    <i class="fa fa-link" aria-hidden="true"></i>博客文章</a>。</li>
                        </ul>
                    </li>
                </ul>
            </section>

            <!-- 项目经验 -->
            <section class="project info-unit">
                <h2>
                    <i class="fa fa-terminal" aria-hidden="true"></i>个人项目</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>[项目1]医学科学数据管理与共享平台</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>201X.X-201X.X</time>
                        </h3>
                        <ul class="info-content">
                            <li>技术栈：ThinkPHP+MongoDB+Axure</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]实现多类型多来源医学科学数据的提交、管理和共享
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [团队]同 2 位同专业同学一起
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]完成从
                                <mark>“调研-设计-实现-文档”</mark>等工作，主要负责系统原型、功能框架及数据提交流程、元数据及源数据的管理与共享方案的设计以及系统开发等工作
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [效果]作品最终取得第三届共享杯国家级竞赛“一等奖” （2/2000）</li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>[项目2]肿瘤流行病数据可视化</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>201X.X-201X.X</time>
                        </h3>
                        <ul class="info-content">
                            <li>技术栈：HTML 5+D3.js+ECharts+MySQL</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]实现常见肿瘤流行病数据多维度可视化展示、数据透视及分析
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [团队]与 1 位同学
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]分析项目需求，清洗并整理相关数据(扩展第三方知识组织系统和 Google trends 数据)，并用
                                <mark>D3.js</mark> 和
                                <mark>ECharts</mark> 进行图形化展示以及实现简易自动分析 功能
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [效果]作品取得第二届共享杯国家级竞赛“特等奖”(1/1500)
                            </li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>[项目3]肿瘤流行病数据可视化</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>201X.X-201X.X</time>
                        </h3>
                        <ul class="info-content">
                            <li>技术栈：HTML 5+D3.js+ECharts+MySQL</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]实现常见肿瘤流行病数据多维度可视化展示、数据透视及分析
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [团队]与 1 位同学
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]分析项目需求，清洗并整理相关数据(扩展第三方知识组织系统和 Google trends 数据)，并用
                                <mark>D3.js</mark> 和
                                <mark>ECharts</mark> 进行图形化展示以及实现简易自动分析功能
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [效果]作品取得第二届共享杯国家级竞赛“特等奖”(1/1500)
                            </li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>[项目4]肿瘤流行病数据可视化</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>201X.X-201X.X</time>
                        </h3>
                        <ul class="info-content">
                            <li>技术栈：HTML 5+D3.js+ECharts+MySQL</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]实现常见肿瘤流行病数据多维度可视化展示、数据透视及分析
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [团队]与 1 位
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]分析项目需求，清洗并整理相关数据(扩展第三方知识组织系统和 Google trends 数据)，并用
                                <mark>D3.js</mark> 和
                                <mark>ECharts</mark> 进行图形化展示以及实现简易自动分析 功能
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [效果]作品取得第二届共享杯国家级竞赛“特等奖”(1/1500)
                            </li>
                        </ul>
                    </li>

                </ul>
            </section>

            <!-- 自我评价 -->
            <section class="work info-unit">
                <h2>
                    <i class="fa fa-pencil" aria-hidden="true"></i>自我评价/期望</h2>
                <hr/>
                <p>[此处如果有一些能够量化的、且比较个性的指标会有加分，比如喜爱跑步坚持夜跑200小时或者200km等]
                    <span class="mark-txt">“多静多思考，反省不张扬”</span>是我给自己总结的“十字箴言”，鞭策自己做人既不能以己度人，也不以人观己，要脚踏实地做事，坚持自己的梦想和本心。</p>
            </section>
        </section>
    </article>



    <footer class="footer">
        <p>© 2017 张大侠.文档最后更新时间为
            <time>2018年06月20日</time>.</p>
    </footer>

    <!-- 侧栏 -->
    <aside>
        <ul>
            <li>
                <a href="https://gitee.com/itsay/resume" target="_blank">源代码</a>
            </li>
            <li>
                <a href="http://if2er.com/" target="_blank">Blog</a>
            </li>
        </ul>
    </aside>

    <script src="./assets/js/index.js"></script>
</body>

</html>
