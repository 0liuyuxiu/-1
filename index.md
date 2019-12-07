<!DOCTYPE html>
<html lang="en" >
<head>
<meta charset="UTF-8">
<title>给最爱的静静</title>

<style>
@import url('https://fonts.googleapis.com/css?family=Oswald:700');
@import url('https://fonts.googleapis.com/css?family=Rubik');

body {
  background-color:/* #3757D0 */green;
  background-image:radial-gradient(#81BCFF, #303391);
  background-size:100%;
  background-repeat:no-repeat;
  background-attachment:fixed;
  color:#fff;
  text-align:center;
}

#rotate-words {
  max-width:400px;
  margin:auto;
  padding:20% 0;
  font-size:2.2em;
  text-transform:uppercase;
  font-family: 'Oswald', sans-serif;
}

#rotate-words span {
  display:block;
  height:50px;
  font-size:.7em;
  text-transform:lowercase;
  opacity:.8;
  font-family: 'Rubik', sans-serif;
}

#rotate-words div {
 position:absolute;
 opacity:0;
 overflow:hidden;
 left:10vw;
 width:80vw;
 line-height:1.2em;
 animation: rotate-word 32s linear infinite 0s;
}

@keyframes rotate-word {
    0% { opacity: 0;  transform: translateX(0);filter:blur(10px);transform:scale(1.2)}
    3% { opacity: 1;  transform: translateX(0);filter:blur(0px);transform:scale(.9)}
    12% { opacity: 1; transform: translateX(0);filter:blur(0px);transform:scale(1)}
    16% { opacity: 0; transform: translateX(0);filter:blur(10px);transform:scale(1.2)}
    80% { opacity: 0}
    100% { opacity: 0}
}

#rotate-words div:nth-child(2) { animation-delay: 4s}
#rotate-words div:nth-child(3) { animation-delay: 8s}
#rotate-words div:nth-child(4) { animation-delay: 12s}
#rotate-words div:nth-child(5) { animation-delay: 16s}
#rotate-words div:nth-child(6) { animation-delay: 20s}
#rotate-words div:nth-child(7) { animation-delay: 24s}
#rotate-words div:nth-child(8) { animation-delay: 28s}

@keyframes author {
    0% { opacity: 0;  transform: translateY(100px);filter:blur(10px);transform: scaleY(2)}
    20% { opacity:0; transform: translateY(200px);filter:blur(10px); transform: scaleY(2)}
    30% { opacity:1; transform: translateY(0);filter:blur(0px);transform: scaleY(1)}
    90% { opacity:1; transform: translateY(0);filter:blur(0px);transform: scaleY(.9)}
    100% { opacity:0; transform: translateY(0);filter:blur(10px);transform: scale(2)}
}
</style>

</head>
<body >

<div id="rotate-words">  
	<div>Baby<br />  <span>宝贝</span></div>
	<div>I saw<br />  <span>我感同身受</span></div>
	<div>Your ordeal<br />  <span>你的煎熬</span></div>
	<div> Me too<br />  <span>我也是</span></div>
	<div>I think about you day and night<br />  <span>日夜都在想你</span></div>
	<div>I don't know <br />  <span>我不知道</span></div>
	<div>how to express my feelings<br />  <span>该怎么表达我的感情</span></div>
	<div>My feelings<br />  <span>我的感情</span></div>
	<div>I took myself <br />  <span>我带着我自己</span></div>
	<div>Come to your DongYing<br />  <span>来了你的东营</span></div>
	<div>All I can say is<br/>  <span>我只能说</span></div>
	<div>,without your life<br />  <span>，没有你的生活</span></div>
	<div>I'm like half<br />  <span>我就好像是半个人</span></div>
	<div>If you can <br />  <span>如果可以的话</span></div>
	<div>I dream of pulling you<br />  <span>做梦都想拉着你</span></div>
	<div>Travelling the world<br />  <span>游走世间</span></div>
        	
</div>

<div style="text-align:center;margin:50px 0; font:normal 14px/24px 'MicroSoft YaHei';">
</div>
</body>
</html>
