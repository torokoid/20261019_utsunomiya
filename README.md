# 20261019_utsunomiya
<html lang="ja" data-loaded="false" data-scrolled="false" data-spmenu="closed">
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
p {
color: #fffafa;
font-size: 1.5em;
}


.red {color:#ff0000;}
.grey {color:#ffffff; background:#999999;}
.snow {color:#fffafa;}
.yellow {color:#ff0000; background:#ffff00;}
.blue {color:#0000ff;}
.white {color:#ffffff;}
.waku {border:2px dotted #99cc66;
line-height: 200%;
padding: 10px;}


main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}


/* 点滅 */
.blinking{
-webkit-animation:blink 1.5s ease-in-out infinite alternate;
-moz-animation:blink 1.5s ease-in-out infinite alternate;
animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@-moz-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/

/*背景を表示させる部分*/
body::before {
content:"";
display:block;
position:fixed;
top:0;
left:0;
z-index:-1;
width:100%;
height:100vh;
background:url(https://torokoid.github.io/20261019_utsunomiya/20261019_00014.jpeg) center/cover no-repeat;
-webkit-background-size:cover;/*Android4*/
}

a.p:hover {
position: relative;
text-decoration: none;
}
a.p span {
display: none;
position: relative;
top: -0.5em;
left: 2em;
}
a.p:hover span {
border: none;
display: block;
width: 800px;
}


@media screen and (min-width: 540px),
screen and (orientation: landscape) {
p.note { display: none; }
}


.media-container {
  width: 100%;
  max-width: 900px;
  margin: 0 auto;
}

.responsive-media {
  width: 100%;
  display: block;
}

.youtube-wrapper {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%; /* 16:9比率 */
  height: 0;
}

.youtube-wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
}





/* オープニング画面のスタイリング（写真を表示するように変更） */
#splash {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background-color: #000000; /* 読み込み前の万一の背景（黒） */
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  z-index: 9999; /* 最前面に表示 */
  opacity: 1;
  visibility: visible;
  transition: opacity 0.8s ease, visibility 0.8s ease; /* 0.8秒かけてふわっと消える */
  padding: 20px;
  box-sizing: border-box;
}

.splash-content {
  max-width: 800px;
  width: 100%;
  text-align: center;
}

.splash-content img {
  width: 100%;
  height: auto;
  max-height: 75vh;
  object-fit: contain;
  box-shadow: 0 10px 30px rgba(0,0,0,0.5);
  border-radius: 4px;
}

.splash-text {
  color: #fff;
  margin-top: 15px;
  font-size: 1.2em;
}

/* 読み込み完了後に付与するクラス（非表示状態） */
#splash.loaded {
  opacity: 0;
  visibility: hidden;
}

/* メインコンテンツ */
#container {
  opacity: 1;
}




/* --- スクロールでズームインしながら浮き出るアニメーション --- */
.scroll-fade {
  opacity: 0;
  transform: translateY(40px) scale(0.85); /* 最初は少し下にいて、サイズも少し縮小（0.85倍）しておく */
  transition: opacity 1.2s cubic-bezier(0.16, 1, 0.3, 1), transform 1.2s cubic-bezier(0.16, 1, 0.3, 1);
  will-change: opacity, transform;
}

/* 画面内に入ったときに、元のサイズ・透明度になりながらズームイン・アップする */
.scroll-fade.is-show {
  opacity: 1;
  transform: translateY(0) scale(1); /* 通常のサイズ・位置に戻る（ズームイン） */
}



</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>

<!-- オープニング（スプラッシュ画面に写真とタイトルを配置） -->
<div id="splash">
  <div class="splash-content">
    <img src="20261019_00010.jpeg" alt="オープニング画像">
    <div class="splash-text">最初の一枚はまんまるシマカンギク</div>
  </div>
</div>

<!-- メインコンテンツ -->
<div id="container">
  <h1>メインのホームページ画像</h1>
  <p><a href="20261019_00010.jpeg" target="_blank"><img src="20261019_00010.jpeg" alt="サンプル画像" class="responsive-media"></a></p>
</div>



<!--
    <p><a href="https://peyng.github.io/restart/">前回までの記録</a>><a><span class="grey">今回2026,05,28</span></a></p>
-->


<p class="note">
モバイル端末をお使いの場合は、画面を横向きにすると
背景画像の横方向がご覧頂けます。
</p>


<!--ここ上は、ほぼそのまま使います！-->


<!--QRコードの挿入例-->
<p align="left"> <img src="QR_2026Oct19.png" alt="アクセス用QRコード" width="100">QR for Access</p>
<p align="right"><marquee direction="left" scrollamount="20" width="30%">(^_^)/~alis</marquee></p>

<!--流れ文字の挿入例-->
<h1><span class="yellow"><marquee behavior="left">!!! 2026/10/19、ホームセンターのお花達から、プール玄関前のお花達とお月様まで !!!</marquee></span></h1>




<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<!--ここから下が、本体部分-->


<div class="media-container">

<h2><span class="yellow">2026Oct18、カインズホームのお花達が陽射しを浴びてこんにちは</span></h2>
<a href="20261019_00001.jpeg" target="_blank"><img src="20261019_00001.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00002.jpeg" target="_blank"><img src="20261019_00002.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00003.jpeg" target="_blank"><img src="20261019_00003.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00004.jpeg" target="_blank"><img src="20261019_00004.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00005.jpeg" target="_blank"><img src="20261019_00005.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00006.jpeg" target="_blank"><img src="20261019_00006.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00007.jpeg" target="_blank"><img src="20261019_00007.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00008.jpeg" target="_blank"><img src="20261019_00008.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00009.jpeg" target="_blank"><img src="20261019_00009.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00010.jpeg" target="_blank"><img src="20261019_00010.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00011.jpeg" target="_blank"><img src="20261019_00011.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00012.jpeg" target="_blank"><img src="20261019_00012.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00013.jpeg" target="_blank"><img src="20261019_00013.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00014.jpeg" target="_blank"><img src="20261019_00014.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00015.jpeg" target="_blank"><img src="20261019_00015.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00016.jpeg" target="_blank"><img src="20261019_00016.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">ここからは屋内お花売り場</span></h2>
<a href="20261019_00017.jpeg" target="_blank"><img src="20261019_00017.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00018.jpeg" target="_blank"><img src="20261019_00018.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00019.jpeg" target="_blank"><img src="20261019_00019.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00020.jpeg" target="_blank"><img src="20261019_00020.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">サボテンも元気</span></h2>
<a href="20261019_00021.jpeg" target="_blank"><img src="20261019_00021.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00022.jpeg" target="_blank"><img src="20261019_00022.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">お昼は青空の吉野家</span></h2>
<a href="20261019_00023.jpeg" target="_blank"><img src="20261019_00023.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">定番の牛丼サラダセット</span></h2>
<a href="20261019_00024.jpeg" target="_blank"><img src="20261019_00024.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">21日まで¥100引きセール</span></h2>
<a href="20261019_00025.jpeg" target="_blank"><img src="20261019_00025.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">午後は河内総合運動公園のプール、かわちの丘に午後の陽射しがさしてのどかさを醸し出してます</span></h2>
<a href="20261019_00026.jpeg" target="_blank"><img src="20261019_00026.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">玄関前のお花もニッコリ</span></h2>
<a href="20261019_00027.jpeg" target="_blank"><img src="20261019_00027.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00028.jpeg" target="_blank"><img src="20261019_00028.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00029.jpeg" target="_blank"><img src="20261019_00029.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00030.jpeg" target="_blank"><img src="20261019_00030.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261019_00031.jpeg" target="_blank"><img src="20261019_00031.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">プールの空にお月様</span></h2>
<a href="20261019_00032.jpeg" target="_blank"><img src="20261019_00032.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">月齢7.1日のお月様がクッキリ鮮やか</span></h2>
<a href="20261019_00033.jpeg" target="_blank"><img src="20261019_00033.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">夕暮れの空も綺麗でした</span></h2>
<a href="20261019_00034.jpeg" target="_blank"><img src="20261019_00034.jpeg" alt="サンプル画像" class="responsive-media"></a>


<h2><span class="yellow">宇都宮市北部、カインズホームと吉野家までの走行経路はこのルート</span></h2>
<a href="20261019_00001.png" target="_blank"><img src="20261019_00001.png" alt="サンプル画像" class="responsive-media"></a>


<h2><span class="yellow">今回の市内走行動画</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/SXTf-w-FuZI?si=qz--GtWTDGt1fSLH&autoplay=1&mute=1&loop=1&playlist=SXTf-w-FuZI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>


<h2><span class="yellow">以上、今回も写真少なめでしたが、ホームセンターのお花特集でした</span></h2>


<br><br>
<h2><span class="yellow">月齢の説明リンク貼ります</span></h2>
<h2><a href="https://starwalk.space/ja/moon-calendar" target="_blank"><span class="snow">月齢カレンダー・リンク</span></a></h2>

<br><br>
<br><br>

<h2><span class="yellow">今日のBGMは、12 Hours of Deep Sleep Music for Dogs 🐶🍁 Anti-Separation Anxiety Relief | Soothing Sounds for Calm 🎶</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/r6tAvPuzoaA?si=rYVEmzpwZ5RNaAYa&autoplay=1&mute=0&loop=1&playlist=r6tAvPuzoaA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

<br><br><br>
<h2><span class="yellow">2026Oct19、ホームセンターのお花達から、プール玄関前のお花達とお月様まででした<br>Thank you for reading this far.</span></h2>

<br><br><br>

<!-- hitwebcounter Code START -->
<a href="https://www.hitwebcounter.com" target="_blank">
<p>you are <img src="https://hitwebcounter.com/counter/counter.php?page=21345151&style=0018&nbdigits=5&type=page&initCount=0" title="Counter Widget" Alt="Visit counter For Websites"   border="0" />visitor<br>The numbers are cumulative for the Bangkok ＆ Utsunomiya series websites launched since 2025 August 1st.</p></a>  



<style>
.responsive-media {
    opacity: 1 !important;
    filter: brightness(100%) !important;
}
</style>


<br><br><br><br><br><br><br><br><br>





<br><br>

<br><br><br><br><br><br>

<!--本体はここまで-->
    </div>

<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
<p>Copyright 2026/10/19 alis</p>
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>


<script>
window.addEventListener('load', function() {
  const splash = document.querySelector('#splash');
  setTimeout(function() {
    splash.classList.add('loaded');
  }, 800);
});
</script>


<script>
// オープニング画面を消す既存のコード
window.addEventListener('load', function() {
  const splash = document.querySelector('#splash');
  setTimeout(function() {
    splash.classList.add('loaded');
  }, 800);
});

// --- スクロール連動のフェードイン処理 ---
document.addEventListener("DOMContentLoaded", function() {
  // 動きをつけたい要素（ここでは画像と見出し h2）を指定
  const targets = document.querySelectorAll('.responsive-media, h2');

  const observer = new IntersectionObserver((entries, observer) => {
    entries.forEach(entry => {
      // 画面に少し入ってきたら
      if (entry.isIntersecting) {
        entry.target.classList.add('is-show');
        // 何度もアニメーションさせたい場合は unobserve を外してください
        // observer.unobserve(entry.target); 
      }
    });
  }, {
    threshold: 0.25 // 要素が25%見えたタイミングで発火
  });

  targets.forEach(target => {
    target.classList.add('scroll-fade'); // 初期状態のクラスを付与
    observer.observe(target); // 監視を開始
  });
});
</script>

    </body>
    
</html>
