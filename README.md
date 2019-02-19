<!DOCTYPE <!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html;charset=utf-8">
    <title>Page Title</title>
    <script type="text/javascript" src="http://ajax.microsoft.com/ajax/jquery/jquery-1.4.min.js"></script>
    <script type="text/javascript">
    (function(){
        window.alert('sdawdsad')
    })();
    </script>
</head>

<body>
    <style>
        body{margin:0;padding:0;background: "./timg.jpg";font-size:14px;font-family:'微软雅黑','宋体',sans-serif;color:#231F20;overflow:auto}
        #font{color:aqua;font-weight: 100}
    </style>
        <p id="aa"></p>
        <font id="font">&emsp;dawdasd</font>
        <div style="display:none" id="w">今天的雨跟依萍找他爸要钱的那天一样大！</div>
        <script type="text/javascript">
            window.onload = type;
            var index = 0;
            var word = $("#w").html();
            function type(){
                $("#aa").html(word.substring(0,index++));
                if(index > word.length) {
                    return;
                } else {
                    setTimeout(type,50);
                };
            }
        </script>
</body>


</html>