<!DOCTYPE html>
<html>
<head>
    <title>测试网站</title>
</head>
<body>
    <h1>测试成功！</h1>
    <p>如果看到这行字，说明 GitHub Pages 工作正常。</p>
    <p>当前时间：<span id="time"></span></p>
    
    <script>
        document.getElementById('time').textContent = new Date().toLocaleString();
    </script>
</body>
</html>
