<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>网站地图 - 成语大全 | 全站链接导航</title>
<meta name="description" content="成语大全网站地图：汇集全站所有栏目、字母索引、字数分类及成语详解页面链接，方便快速查找与浏览。">
<style>
  :root {
    --primary: #2f7d5b;
    --primary-light: #eaf5f0;
    --primary-dark: #1f5a40;
    --text: #2c3e3a;
    --text-muted: #6b7f79;
    --bg: #f6faf8;
    --card: #ffffff;
    --border: #e2ece7;
    --accent: #d9822b;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    font-family: "PingFang SC", "Microsoft YaHei", "Noto Sans SC", sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
  }
  .hero {
    background: linear-gradient(135deg, var(--primary-dark), var(--primary));
    color: #fff;
    text-align: center;
    padding: 56px 20px 48px;
  }
  .hero h1 { font-size: 2rem; letter-spacing: 2px; }
  .hero p { margin-top: 10px; opacity: .9; font-size: 1rem; }
  .hero .stat {
    display: inline-block;
    margin-top: 18px;
    background: rgba(255,255,255,.15);
    padding: 6px 18px;
    border-radius: 999px;
    font-size: .9rem;
  }
  .container { max-width: 1080px; margin: 0 auto; padding: 40px 20px 60px; }

  section { margin-bottom: 44px; }
  .sec-title {
    display: flex;
    align-items: center;
    gap: 10px;
    font-size: 1.25rem;
    color: var(--primary-dark);
    margin-bottom: 18px;
    padding-bottom: 10px;
    border-bottom: 2px solid var(--border);
  }
  .sec-title .icon {
    width: 34px; height: 34px;
    display: inline-flex; align-items: center; justify-content: center;
    background: var(--primary-light);
    border-radius: 8px;
    font-size: 1.1rem;
  }
  .sec-title small { color: var(--text-muted); font-weight: normal; font-size: .85rem; margin-left: auto; }

  .grid {
    display: grid;
    gap: 14px;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  }
  a.item {
    display: flex;
    align-items: center;
    gap: 10px;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 12px 16px;
    text-decoration: none;
    color: var(--text);
    transition: all .2s ease;
  }
  a.item:hover {
    border-color: var(--primary);
    transform: translateY(-2px);
    box-shadow: 0 6px 16px rgba(47,125,91,.12);
  }
  a.item .dot {
    width: 8px; height: 8px;
    background: var(--primary);
    border-radius: 50%;
    flex-shrink: 0;
  }
  a.item span.txt { flex: 1; }
  a.item span.tag {
    font-size: .72rem;
    color: var(--text-muted);
    background: var(--primary-light);
    border-radius: 6px;
    padding: 2px 8px;
    white-space: nowrap;
  }
  a.item.home { background: var(--primary); color: #fff; border-color: var(--primary); font-weight: 600; }
  a.item.home .dot { background: #fff; }

  .letter-grid { grid-template-columns: repeat(auto-fill, minmax(96px, 1fr)); }
  a.letter {
    display: flex;
    align-items: center;
    justify-content: center;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 14px 0;
    text-decoration: none;
    font-weight: 700;
    font-size: 1.15rem;
    color: var(--primary-dark);
    transition: all .2s ease;
  }
  a.letter:hover {
    background: var(--primary);
    color: #fff;
    border-color: var(--primary);
    transform: translateY(-2px);
  }

  footer {
    text-align: center;
    padding: 30px 20px;
    color: var(--text-muted);
    font-size: .85rem;
    border-top: 1px solid var(--border);
    background: var(--card);
  }
  footer a { color: var(--primary); text-decoration: none; }

  @media (max-width: 560px) {
    .hero h1 { font-size: 1.5rem; }
    .grid { grid-template-columns: 1fr 1fr; }
    .letter-grid { grid-template-columns: repeat(4, 1fr); }
  }
</style>
</head>
<body>

<div class="hero">
  <h1>🗺️ 网站地图 · 链接导航</h1>
  <p>成语大全 —— 在线查询成语词典</p>
  <span class="stat">共收录 66 个页面链接，一站直达</span>
</div>

<div class="container">

  <section>
    <div class="sec-title"><span class="icon">🏠</span>网站首页</div>
    <div class="grid">
      <a class="item home" href="https://cd.qingmeilv.cn/"><span class="dot"></span><span class="txt">成语大全 - 首页</span></a>
    </div>
  </section>

  <section>
    <div class="sec-title"><span class="icon">📂</span>分类栏目 <small>按主题浏览成语</small></div>
    <div class="grid">
      <a class="item" href="https://cd.qingmeilv.cn/fable/"><span class="dot"></span><span class="txt">寓言故事成语</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/season/"><span class="dot"></span><span class="txt">季节成语</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/number/"><span class="dot"></span><span class="txt">数字成语</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/animal/"><span class="dot"></span><span class="txt">动物成语</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/quality/"><span class="dot"></span><span class="txt">品质成语</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/study/"><span class="dot"></span><span class="txt">学习成语</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/scenery/"><span class="dot"></span><span class="txt">景色成语</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/cat-309085/"><span class="dot"></span><span class="txt">讽刺骂人成语</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/other/"><span class="dot"></span><span class="txt">其他成语</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/jielong"><span class="dot"></span><span class="txt">成语接龙</span></a>
    </div>
  </section>

  <section>
    <div class="sec-title"><span class="icon">🔤</span>字母索引 <small>按首字母查询成语</small></div>
    <div class="grid letter-grid">
      <a class="letter" href="https://cd.qingmeilv.cn/zm/B" title="B 字母成语">B</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/C" title="C 字母成语">C</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/D" title="D 字母成语">D</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/F" title="F 字母成语">F</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/G" title="G 字母成语">G</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/H" title="H 字母成语">H</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/J" title="J 字母成语">J</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/K" title="K 字母成语">K</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/L" title="L 字母成语">L</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/M" title="M 字母成语">M</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/N" title="N 字母成语">N</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/P" title="P 字母成语">P</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/Q" title="Q 字母成语">Q</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/R" title="R 字母成语">R</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/S" title="S 字母成语">S</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/T" title="T 字母成语">T</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/W" title="W 字母成语">W</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/X" title="X 字母成语">X</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/Y" title="Y 字母成语">Y</a>
      <a class="letter" href="https://cd.qingmeilv.cn/zm/Z" title="Z 字母成语">Z</a>
    </div>
  </section>

  <section>
    <div class="sec-title"><span class="icon">🔢</span>按字数分类</div>
    <div class="grid">
      <a class="item" href="https://cd.qingmeilv.cn/zs/3"><span class="dot"></span><span class="txt">三字成语</span><span class="tag">3 字</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/zs/4"><span class="dot"></span><span class="txt">四字成语</span><span class="tag">4 字</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/zs/5"><span class="dot"></span><span class="txt">五字成语</span><span class="tag">5 字</span></a>
    </div>
  </section>

  <section>
    <div class="sec-title"><span class="icon">📖</span>成语详解页面 <small>拼音 · 释义 · 出处 · 造句 · 故事</small></div>
    <div class="grid">
      <a class="item" href="https://cd.qingmeilv.cn/study/han-ying-ju-hua.html"><span class="dot"></span><span class="txt">含英咀华</span><span class="tag">学习</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/yue-wang-shi-wa.html"><span class="dot"></span><span class="txt">越王式蛙</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/yi-yang-yi-niu.html"><span class="dot"></span><span class="txt">以羊易牛</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/ying-shu-yan-shuo.html"><span class="dot"></span><span class="txt">郢书燕说</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/zeng-zi-sha-zhi.html"><span class="dot"></span><span class="txt">曾子杀彘</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/wang-liang-wen-ying.html"><span class="dot"></span><span class="txt">罔两问景</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/xing-xing-neng-yan.html"><span class="dot"></span><span class="txt">猩猩能言</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/pao-ding-jie-niu-dao.html"><span class="dot"></span><span class="txt">庖丁解牛刀</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/ye-gong-wen-kong.html"><span class="dot"></span><span class="txt">叶公问孔</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/yu-bang-xiang-chi.html"><span class="dot"></span><span class="txt">鹬蚌相持</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/season/sui-han-san-you.html"><span class="dot"></span><span class="txt">岁寒三友</span><span class="tag">季节</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/season/chun-song-xia-xian.html"><span class="dot"></span><span class="txt">春诵夏弦</span><span class="tag">季节</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/season/dong-wen-xia-qing.html"><span class="dot"></span><span class="txt">冬温夏凊</span><span class="tag">季节</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/study/kai-juan-you-yi.html"><span class="dot"></span><span class="txt">开卷有益</span><span class="tag">学习</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/cat-309085/shi-wei-su-can.html"><span class="dot"></span><span class="txt">尸位素餐</span><span class="tag">讽刺骂人</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/animal/dui-niu-tan-qin.html"><span class="dot"></span><span class="txt">对牛弹琴</span><span class="tag">动物</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/cat-309085/huang-liang-yi-meng.html"><span class="dot"></span><span class="txt">黄粱一梦</span><span class="tag">讽刺骂人</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/dong-shi-xiao-pin.html"><span class="dot"></span><span class="txt">东施效颦</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/mai-du-huan-zhu.html"><span class="dot"></span><span class="txt">买椟还珠</span><span class="tag">寓言故事</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/cat-309085/tiao-liang-xiao-chou.html"><span class="dot"></span><span class="txt">跳梁小丑</span><span class="tag">讽刺骂人</span></a>
      <a class="item" href="https://cd.qingmeilv.cn/fable/bing-zhu-zhi-ming.html"><span class="dot"></span><span class="txt">炳烛之明</span><span class="tag">寓言故事</span></a>
    </div>
  </section>

  <section>
    <div class="sec-title"><span class="icon">🔗</span>友情链接</div>
    <div class="grid">
      <a class="item" href="https://cd.qingmeilv.cn/links"><span class="dot"></span><span class="txt">友情链接页面</span></a>
    </div>
  </section>

</div>

<footer>
  <p><a href="https://cd.qingmeilv.cn/">成语大全</a> · 网站地图 | 本页面收录全站栏目、索引与文章链接，便于访客与搜索引擎快速导航。</p>
</footer>

</body>
</html>
