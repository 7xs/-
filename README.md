# -
使用ckplayer播放视频
<body>
<script type="text/javascript" src="ckplayer/ckplayer.js"></script>
<div class="video" style="width: 1000px;height: 600px;"></div>
<script type="text/javascript">
    var videoObject = {
        container: '.video',//“#”代表容器的ID，“.”或“”代表容器的class
        variable: 'player',//该属性必需设置，值等于下面的new chplayer()的对象
        autoplay:true,//自动播放
        live:true,//直播视频形式
        video:'rtmp://192.168.134.128:1936/live/dc'//视频地址
    };
    var player=new ckplayer(videoObject);
</script>
