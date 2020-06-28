破解成功
破解名称：MujurID
版本: 4.5.6
文件大小: 4.01 MB
10分钟内下载有效，过期将删除文件！

Fork me on GitHub
Charles 在线破解工具
MujurID

Charles 4.5.6
请正确选择要破解的版本 建议安装使用最新版，官方下载地址 https://www.charlesproxy.com/download/
描述
此工具用于生成破解后的charles.jar文件，blog介绍: https://blog.zzzmode.com/2017/05/16/charles-4.0.2-cracked
用法
输入RegisterName(此名称随意，用于显示 Registered to xxx)，选择本地已安装的版本，点击生成，并下载charles.jar文件
替换本地charles.jar文件
macOS: /Applications/Charles.app/Contents/Java/charles.jar
Windows: C:\Program Files\Charles\lib\charles.jar
注意
仅供个人学习研究和交流使用，请勿用于任何商业用途。
广告
如果您有使用国外VPS的需求，不妨试试Vultr，我的推广链接 https://www.vultr.com/?ref=7772542-4F
https://www.zzzmode.com/mytools/charles/
https://github.com/MujurID/Charles-Crack/blob/master/src/main/resources/static/index.html


<!DOCTYPE html>
<html>

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta charset="utf-8">
    <title>Charles破解工具</title>

    <link rel="shortcut icon" href="/mytools/charles/favicon.ico" type="image/x-icon" />

    <link rel="stylesheet" href="https://cdn.staticfile.org/twitter-bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">


<script type="9040fe98897767dda8bd4df8-text/javascript">
    var _hmt = _hmt || [];
    (function() {
      var hm = document.createElement("script");
      hm.src = "https://hm.baidu.com/hm.js?7b75078b9031f25c29a1201d3e83ac3a";
      var s = document.getElementsByTagName("script")[0]; 
      s.parentNode.insertBefore(hm, s);
    })();
</script>

</head>

<body>

    <a href="https://github.com/8enet/Charles-Crack" target="_black"><img style="position: absolute; top: 0; right: 0; border: 0;" src="forkme_right_green_007200.png" alt="Fork me on GitHub"></a>



<h3 class="text-center">Charles 在线破解工具</h3>
<div id="myTabContent" class="tab-content" style="margin-top: 10%">
    <!-- 添加页面 -->
    <div class="tab-pane fade in active container" id="add">
        <form id="f_t" @submit="charlesCrack" class="bs-example bs-example-form" role="form">
            <input type="hidden" name="generateKey">

            <div class="form-group">
                <input type="text" maxlength="32" v-model="ckData.name" placeholder="RegisterName" class="form-control"/>
            </div>

            <div class="form-group">
                <select v-model="ckData.version" class="form-control">
                    <option disabled value="">请选择版本</option>
                    <option v-for="option in options" v-bind:value="option.version">
                        {{ option.name }}
                    </option>
                </select>
            </div>

            <div class="form-group">
                <button id="btn_ck" type="submit" onclick="if (!window.__cfRLUnblockHandlers) return false; ga('send','event','button', 'click','ck_crack');" data-loading-text="处理中..." class="btn btn-default" data-cf-modified-9040fe98897767dda8bd4df8-="">生成</button>
            </div>

        </form>
    </div>


    <!-- 详情弹窗 -->
    <div class="modal fade" id="update" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-hidden="true">×</button>
                    <h4 class="modal-title" id="myModalLabel">破解成功</h4>
                </div>
                <div class="modal-body">
                    破解名称：{{ dataCKResp.name }} <br/>
                    版本: {{ dataCKResp.version }} <br/>
                    文件大小: {{ dataCKResp.size | fmtFileSize }} <br/>
                    10分钟内下载有效，过期将删除文件！
                </div>

                <div class="modal-footer">
                    <a v-bind:href="dataCKResp.file" download target="_blank" onclick="if (!window.__cfRLUnblockHandlers) return false; ga('send','event','button', 'click','ck_download');" class="btn btn-default" data-cf-modified-9040fe98897767dda8bd4df8-="">下载</a>
                    <button type="button" class="btn btn-default" data-dismiss="modal">关闭</button>
                </div>

            </div>
        </div>

    </div>
    <!-- 详情弹窗 end -->

</div>


<div class="tab-content tab-pane fade in active container" style="margin-top: 2%">
    <dl>

        <dd>
            <label style="color: red">请正确选择要破解的版本</label>   建议安装使用最新版，官方下载地址 <a href="https://www.charlesproxy.com/download" target="_blank" title="Charles官网">https://www.charlesproxy.com/download/</a>
        </dd>
        
        <dt>
            描述
        </dt>
        <dd>
            此工具用于生成破解后的charles.jar文件，blog介绍: <a href="https://blog.zzzmode.com/2017/05/16/charles-4.0.2-cracked/" target="_blank" title="charles 破解介绍">https://blog.zzzmode.com/2017/05/16/charles-4.0.2-cracked</a>
        </dd>
        <dt>
            用法
        </dt>
        <dd>
            输入RegisterName(此名称随意，用于显示 Registered to xxx)，选择本地已安装的版本，点击生成，并下载charles.jar文件
        </dd>
        <dd>
            替换本地charles.jar文件
        </dd>
        <dd>
            macOS: <code>/Applications/Charles.app/Contents/Java/charles.jar</code>
        </dd>
        <dd>
            Windows: <code>C:\Program Files\Charles\lib\charles.jar</code>
        </dd>
        <dt>
            注意
        </dt>
        <dd>
            仅供个人学习研究和交流使用，请勿用于任何商业用途。
        </dd>

        <dt>
            广告
        </dt>
        <dd>
            如果您有使用国外VPS的需求，不妨试试Vultr，我的推广链接 <a href="https://www.vultr.com/?ref=7772542-4F" target="_black">https://www.vultr.com/?ref=7772542-4F</a> 
            <div style="margin-top: 5px" >
                <a href="https://www.vultr.com/?ref=7772542-4F" target="_black"><img src="vultr_banner_2.png" width="468" height="60" ></a>
        </div>
        </dd>
    </dl>
</div>

<script src="https://ajax.cloudflare.com/cdn-cgi/scripts/7089c43e/cloudflare-static/rocket-loader.min.js" data-cf-settings="9040fe98897767dda8bd4df8-|49" defer=""></script></body>


<script src="https://cdn.staticfile.org/jquery/3.3.1/jquery.min.js" type="9040fe98897767dda8bd4df8-text/javascript"></script>
<script src="https://cdn.staticfile.org/twitter-bootstrap/3.3.7/js/bootstrap.min.js" type="9040fe98897767dda8bd4df8-text/javascript"></script>
<script src="https://cdn.staticfile.org/bootstrap-growl/1.0.6/bootstrap-growl.min.js" type="9040fe98897767dda8bd4df8-text/javascript"></script>
<script src="https://cdn.staticfile.org/vue/2.5.17/vue.min.js" type="9040fe98897767dda8bd4df8-text/javascript"></script>



<script type="9040fe98897767dda8bd4df8-text/javascript" src="index.js"></script>

<script type="9040fe98897767dda8bd4df8-text/javascript">

    (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
        (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
        m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
    })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

    ga('create', 'UA-76336437-3', 'auto');
    ga('send', 'pageview');
</script>


</html>
