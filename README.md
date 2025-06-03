<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>李圭元 - 个人网页</title>
  <style>
    body {
      font-family: "Microsoft YaHei", sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      background: white;
      padding: 40px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    h1 {
      text-align: center;
      color: #333;
    }
    .info, .company, .contact, .map {
      margin-bottom: 30px;
    }
    .info p, .company p, .contact p {
      line-height: 1.6;
    }
    .section-title {
      font-size: 20px;
      margin-bottom: 10px;
      color: #007acc;
    }
    img.avatar {
      display: block;
      margin: 0 auto 20px;
      width: 150px;
      height: 150px;
      border-radius: 50%;
      box-shadow: 0 0 10px #ccc;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      padding: 10px 20px;
      background-color: #007acc;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .lang-switch {
      text-align: right;
      margin-bottom: 20px;
    }
    .lang-switch a {
      margin-left: 10px;
      text-decoration: none;
      color: #007acc;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="lang-switch">
      <a href="en.html">English</a> | <a href="index.html">中文</a>
    </div>
    <img src="avatar.jpg" alt="头像" class="avatar">
    <h1>李圭元（Guewon Lee）</h1>
    <div class="info">
      <div class="section-title">个人信息</div>
      <p><strong>年龄：</strong>56岁</p>
      <p><strong>出生年月日：</strong>1968年10月12日</p>
      <p><strong>身高：</strong>175cm</p>
      <p><strong>联系方式：</strong>+1 323 831 3325 （WhatsApp / Telegram / Signal 同号）</p>
    </div>
    <div class="company">
      <div class="section-title">公司介绍 - 输变电建设有限公司</div>
      <p><strong>主营业务：</strong></p>
      <ul>
        <li>输电、供电、受电电力设施的安装、维修和试验</li>
        <li>建设工程施工、设计</li>
        <li>电气安装服务</li>
        <li>建筑劳务分包及劳务派遣服务</li>
        <li>道路货物运输（不含危险品）</li>
        <li>房屋建筑和市政基础设施工程总承包</li>
        <li>工程管理服务、工程技术服务</li>
        <li>普通机械设备安装服务</li>
        <li>土石方工程施工</li>
        <li>物业管理、设备与工程机械租赁</li>
        <li>光伏设备及元器件销售</li>
      </ul>
    </div>
    <div class="map">
      <div class="section-title">公司位置</div>
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3303.9948980407796!2d-118.2978449!3d34.0689211!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80c2c7b5113f7c0f%3A0x50b3e4b1d6c30158!2zTG9zIEFuZ2VsZXMsIENBLCBVU0E!5e0!3m2!1szh-CN!2sus!4v1717283888888" 
        width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy">
      </iframe>
    </div>
    <div class="contact">
      <div class="section-title">联系我</div>
      <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="您的名字" required>
        <input type="email" name="email" placeholder="您的邮箱" required>
        <textarea name="message" rows="5" placeholder="留言内容" required></textarea>
        <button type="submit">发送</button>
      </form>
    </div>
  </div>
</body>
</html>
