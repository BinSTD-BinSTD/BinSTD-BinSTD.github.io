<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>api接口大全，免费数据接口大全列表-进制数据</title>
  <meta name="keywords" content="api接口大全,数据接口大全">
  <meta name="descrption" content="进制数据精心制作API接口大全，其中包括生活常用、工具万能、交通出行、金融理财、图像识别、位置服务、新闻媒体等大类数据接口，提供较为全面的免费数据接口大全，方便开发者查找所需的API数据接口，节省开发成本是时间。">
  <link rel="stylesheet" type="text/css" href="./css/reset.css">
  <link rel="stylesheet" type="text/css" href="./css/css.css">
</head>
<body>

<div class="leftmenu menu">
  <div class="hidden">
    <h1>API大全</h1>
    <ul>
      <li class="active">
        <h2>生活常用</h2>
        <p class="active"><a href="#1_1">快递查询</a></p>
        <p><a href="#1_2">短信</a></p>
        <p><a href="#1_3">IP查询</a></p>
        <p><a href="#1_4">全国天气预报</a></p>
        <p><a href="#1_5">万年历</a></p>
        <p><a href="#1_6">空气质量指数</a></p>
        <p><a href="#1_7">彩票开奖</a></p>
        <p><a href="#1_8">菜谱大全</a></p>
        <p><a href="#1_9">电视节目预告</a></p>
        <p><a href="#1_10">全国省市县行政区划</a></p>
        <p><a href="#1_11">ISBN书号查询</a></p>
        <p><a href="#1_12">历史天气</a></p>
      </li>
      <li>
        <h2>工具万能</h2>
        <p class="active"><a href="#2_1">手机号码归属地</a></p>
        <p><a href="#2_2">智能问答</a></p>
        <p><a href="#2_3">身份证号码查询</a></p>
        <p><a href="#2_4">区号查询</a></p>
        <p><a href="#2_5">邮编查询</a></p>
        <p><a href="#2_6">WHOIS查询</a></p>
        <p><a href="#2_7">简体/繁体/火星文转换</a></p>
        <p><a href="#2_8">二维码生成识别</a></p>
        <p><a href="#2_9">标准中文电码查询</a></p>
      </li>
       <li>
        <h2>交通出行</h2>
        <p class="active"><a href="#3_1">全国交通违章查询</a></p>
        <p><a href="#3_2">今日油价</a></p>
        <p><a href="#3_3">车辆尾号限行</a></p>
        <p><a href="#3_4">火车查询</a></p>
        <p><a href="#3_5">违章代办</a></p>
        <p><a href="#3_6">车牌号校验</a></p>
        <p><a href="#3_7">公交地铁查询</a></p>
        <p><a href="#3_8">长途汽车</a></p>
        <p><a href="#3_9">违章高发地</a></p>
        <p><a href="#3_10">驾考题库</a></p>
        <p><a href="#3_11">驾驶证扣分查询</a></p>
        <p><a href="#3_12">VIN车辆识别代码查询</a></p>
        <p><a href="#3_13">处罚决定书单号查询</a></p>
      </li>
      <li>
        <h2>金融理财</h2>
        <p class="active"><a href="#4_1">汇率查询</a></p>
        <p><a href="#4_2">黄金价格</a></p>
        <p><a href="#4_3">白银价格</a></p>
        <p><a href="#4_4">银行卡归属地查询</a></p>
        <p><a href="#4_5">企业工商信息</a></p>
        <p><a href="#4_6">失信被执行人黑名单</a></p>
      </li>
      <li>
        <h2>图像识别</h2>
        <p class="active"><a href="#5_1">名片识别</a></p>
        <p><a href="#5_2">动态活体检测</a></p>
        <p><a href="#5_3">人脸比对</a></p>
        <p><a href="#5_4">身份证识别</a></p>
        <p><a href="#5_5">车牌识别</a></p>
        <p><a href="#5_6">银行卡识别</a></p>
        <p><a href="#5_7">驾驶证识别</a></p>
        <p><a href="#5_8">行驶证识别</a></p>
        <p><a href="#5_9">营业执照识别</a></p>
        <p><a href="#5_10">通用文字识别</a></p>
        <p><a href="#5_11">色情图片识别</a></p>
      </li>
      <li>
        <h2>位置服务</h2>
        <p class="active"><a href="#6_1">基站查询</a></p>
        <p><a href="#6_2">经纬度地址转换</a></p>
        <p><a href="#6_3">坐标系转换</a></p>
      </li>
      <li>
        <h2>新闻媒体</h2>
        <p class="active"><a href="#7_1">新闻</a></p>
      </li>
    </ul>
  </div>
  <div class="hidden">
    <h1>更多</h1>
    <ul>
      <li class="active">
        <h2>帮助</h2>
        <p class="active"><a href="#1_1">如何使用</a></p>
      </li>
      <li>
        <h2>版本</h2>
        <p class="active"><a href="#2_1">V0.1</a></p>
        <p><a href="#2_2">V0.2</a></p>
      </li>
       <li>
        <h2>联系我们</h2>
        <p class="active"><a href="#3_1">联系我们</a></p>
        <p><a href="#2_2">工作时间</a></p>
      </li>
    </ul>
  </div>
</div>

<script type="text/javascript">
  $(document).ready(function(){

     function getMd(path, file, fn) {
      $.ajax({
        url: './md/' + path + '/' + file,
        type: "get",
        success: function (data) {
          fn(data)
        }
      })
    }

    $('.leftmenu li p').click(function(e){
      $(this).addClass('active').siblings('p').removeClass('active')
      $('.srch .pos').hide()
      $('.search').val('')
      e.stopPropagation()
    })
    $('.leftmenu li').click(function(){
      var i = $(this).parents('.hidden').index()
      var index = $(this).index() + 1
      var path = i == 0 ? 'index' : 'more'
      getMd(path, index + '.md', function(data){
        $("#mdcontent").html(data);
        $('pre code').each(function(i, block) {
          hljs.highlightBlock(block);
        });
      })
      $(this).addClass('active').siblings('li').removeClass('active')
    })
  })
</script>
</body>
</html>
