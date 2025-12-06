# -2.0
配件库存批发零售版
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>汽配中心首页</title>
  <style>
    body {
      margin: 0;
      font-family: system-ui, -apple-system, "PingFang SC", "Microsoft YaHei", sans-serif;
      background: #0b0c10;
      color: #f5f7ff;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 12px 16px;
      background: #050609;
      position: sticky;
      top: 0;
    }
    .logo { font-weight: 800; }
    nav a {
      margin-left: 12px;
      color: #aeb4c6;
      text-decoration: none;
      font-size: 14px;
    }
    nav a:hover { color: #ffffff; }
    .hero {
      padding: 40px 16px 32px;
      max-width: 900px;
      margin: 0 auto;
    }
    .hero h1 { margin: 0 0 12px; font-size: 26px; }
    .hero p { margin: 0 0 16px; color: #aeb4c6; }
    .btn {
      display: inline-block;
      padding: 10px 18px;
      border-radius: 999px;
      background: #00c2a8;
      color: #01221b;
      font-weight: 700;
      text-decoration: none;
      font-size: 14px;
    }
    section {
      max-width: 900px;
      margin: 0 auto;
      padding: 24px 16px;
    }
    h2 { font-size: 20px; margin-bottom: 8px; }
    ul { padding-left: 18px; color: #aeb4c6; }
    footer {
      padding: 16px;
      text-align: center;
      font-size: 12px;
      color: #8690a4;
      border-top: 1px solid #151827;
      margin-top: 24px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">汽配中心</div>
    <nav>
      <a href="#about">关于我们</a>
      <a href="#products">主营配件</a>
      <a href="#contact">联系方式</a>
    </nav>
  </header>

  <main>
    <!-- 首屏 -->
    <section class="hero">
      <h1>丰田 / 现代 / 起亚 / 德系<br>灯具 & 保险杠 专业批发零售</h1>
      <p>
        提供大灯、尾灯、雾灯、保险杠、水箱、冷凝器等常用外观件。<br>
        支持 VIN 对码，阿斯塔纳 / 阿拉木图发货，自提或送货均可。
      </p>
      <a class="btn" href="#contact">立即询价</a>
    </section>

    <!-- 关于 -->
    <section id="about">
      <h2>关于我们</h2>
      <p style="color:#aeb4c6;">
        这里写你的店铺介绍，例如：我们长期经营丰田、现代、起亚等车型配件，
        与多家工厂合作，常备热门车型外观件现货，可为修理厂、电商卖家提供稳定货源。
      </p>
    </section>

    <!-- 主营配件 -->
    <section id="products">
      <h2>主营配件</h2>
      <ul>
        <li>前大灯 / 尾灯 / 雾灯 / 日行灯总成</li>
        <li>前保险杠 / 后保险杠 / 中网 / 叶子板</li>
        <li>水箱 / 冷凝器 / 中冷器 / 风扇框</li>
        <li>原厂件、副厂件均可按需采购，支持 OEM 号对码</li>
      </ul>
    </section>

    <!-- 联系方式 -->
    <section id="contact">
      <h2>联系方式</h2>
      <ul>
        <li>📍 地址：哈萨克斯坦 · 阿斯塔纳（示例，改成你的）</li>
        <li>📞 电话 / WhatsApp：+7 XXX XXX XX XX</li>
        <li>📷 Instagram：@yourshop</li>
      </ul>
    </section>
  </main>

  <footer>
    © 2025 汽配中心 · 这是示例主页内容，你可以根据自己业务继续完善
  </footer>
</body>
</html>
