<template>
	<div id="app">
		<div id="banner">
			<div id="banner-content">
				<p>起飞页自助建站平台</p>
				<h3>云建站自助平台,<span>成就梦想</span></h3>
				<span id="nr">自主建站平台</span>
				<div class="icon">
					<ul v-for="i in arr">
         				<li><img :src="i.img" /></li>
        			</ul>
				</div>
			</div>
		</div>
		<div class="content-wapper">
			<h3>您的创业梦想需要一个非同凡响的网站</h3>
			<p>云建站倾力打造的一个从网站建设.网网站运营管理到网站推广的自动化免费建站平台</p>
			<div class="content-wapper-content">
				<div class="content-wapper-content1">
					<img src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvZjgxMjkwZTg3YTEzM2ZkNWFiM2IzY2ExNjdhNTA3ZDgucG5n.png"/>
					<span>页面要炫酷,颜值要高</span>
					<p>人靠衣装马靠鞍,一个炫酷的网站才配得上创业者的新潮创 意.微企点采用HTML5最新技术,拥有大气舒适的界面和众多 精美模板,用起飞页制作一个高逼格.高颜值的炫酷网站, 让您的创业项目脱颖而出,非同凡响.</p>
				</div>
				<div class="content-wapper-content2">
					<img src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvZjgxMjkwZTg3YTEzM2ZkNWFiM2IzY2ExNjdhNTA3ZDgucG5n.png"/>
					<span>页面要炫酷,颜值要高</span>
					<p>人靠衣装马靠鞍,一个炫酷的网站才配得上创业者的新潮创 意.微企点采用HTML5最新技术,拥有大气舒适的界面和众多 精美模板,用起飞页制作一个高逼格.高颜值的炫酷网站, 让您的创业项目脱颖而出,非同凡响.</p>
				</div>
				<div class="content-wapper-content3">
					<img src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvZjgxMjkwZTg3YTEzM2ZkNWFiM2IzY2ExNjdhNTA3ZDgucG5n.png"/>
					<span>页面要炫酷,颜值要高</span>
					<p>人靠衣装马靠鞍,一个炫酷的网站才配得上创业者的新潮创 意.微企点采用HTML5最新技术,拥有大气舒适的界面和众多 精美模板,用起飞页制作一个高逼格.高颜值的炫酷网站, 让您的创业项目脱颖而出,非同凡响.</p>
				</div>
			</div>
		</div>
		<div class="yjz">
			<p>云建站自助平台</p>
			<span>上手快.颜值高.跨多屏.自传播.全免费.</span>
		</div>
		<div class="section">
			<div class="section-content">
				<span>在 起飞页自助建站平台，您不需要任何编程基础，就能做出功能强大，效果出众的专业级网站，您所要做的仅是选择网站模板、输入图片文字，以及鼠标拖拉拽；真正 的响应式建站，无论是在电脑的大屏幕，还是手机小屏幕上，网站都能友好地展示；您的访客还可以注册成为会员，并进行在线购物；当然，如果您需要多语言版 本，起飞页也可以轻松为您实现。</span>
			</div>
		</div>
		<div class="yzs">
			<span>云建站，一站式的在线H5建站平台</span>
			<p>云建站倾力打造的一个从网站建设.网网站运营管理到网站推广的自动化免费建站平台</p>
			<img src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvNTE1Y2RhYTQxNDg0YWRiZDY4Mjg1NmU0OGNkZjFlYWYucG5n.png"/>
		</div>
		<div class="nr-icon"></div>
		
	</div>
</template>


<script>
	export default {
  data() {
   return {
    arr: [
     {
      img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvYjgxZjYwZjI5NWFlMzgzODExMzliNDU2ZTkwMGUyYTEtNDd4NDcucG5n.png'
     },
     {
      img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvODUyMjA2ZWViZDZiMmY0YjU1ZjkwZGI3MjNhODRjNWMtNDd4NDcucG5n.png'
     },
     {
      img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvZjU4N2RiMTkzOWE0YjI4NTk0NzA3MjFjYTJhZTYwMDAtNDd4NDcucG5n.png'
     },
     {
      img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvOWIxMTg4ODYwZDI4MzE0MTlmNjkyZjJhM2Y5ZTY5OGUtNDd4NDcucG5n.png'
     },
     {
      img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvZDczNTgwOTlmZWEzN2UyY2E4YTVjZWVjNmIxMDU4NmUtNDd4NDcucG5n.png'
     },
     {
      img: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvZjcxMDlkMGU1YmUwZWQ1MjA5ZTk0YjFlYjMwMzY3YjYtNDd4NDcucG5n.png'
     },
    ]
   }
  }
 }
	
</script>

<style>
	* {
		margin: 0;
		padding: 0;
		list-style: none;
	}
	#banner{
		height: 700px;
		position: relative;
		background-image: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDMvNzIzNGQ1MjBkZjBiODhiMDIwYTc3ZmYwZjk1MGM3OGEuanBn.jpg'); background-repeat:no-repeat; background-size:cover; background-attachment:fixed; background-position:0 0%;}
	#banner-content{
		width: 80%;
		position: absolute;
		top: 250px;
		left: 10%;
	}
	#banner-content p{
		font-size: 60px;
		color: #fff;
		text-align: center;
	}
	#banner-content h3{
		width: 500px;
		margin: 0 auto;
		line-height: 80px;
		text-align: center;
		border-bottom: 1px #ccc solid;
		border-top: 1px #ccc solid;
		color: #fff;
		margin-top: 30px;
	}
	#banner-content h3 span{
		color: #E84C3D;
	}
	#nr{
		font-size: 26px;
		display: block;
		text-align: center;
		color:#fff;
		margin-top: 30px;
	}
	#banner .icon{
		width: 350px;
		margin: 40px auto;
	}
	.icon div{
		float: left;
	}
	.icon ul{
		width: 380px;
	}
	.icon ul li{
		float: left;
		margin-left: 10px;
	}
	
	.content-wapper{
		height: 400px;
	}
	.content-wapper h3{
		color: #E84C3D;
		text-align: center;
		padding-top: 20px;
	}
	.content-wapper p{
		color: rgb(105, 105, 105);
		text-align: center;
		padding-top: 20px;
	}
	.content-wapper-content{
		width: 80%;
		height: 400px;
		margin: 0 auto;
		margin-top: 40px;
	}
	.content-wapper-content1{
		width: 30%;
		float: left;
	}
	.content-wapper-content2{
		width: 30%;
		float: left;
		margin-left: 30px;
	}
	.content-wapper-content3{
		width: 30%;		float: left;
		margin-left: 30px;
	}
	.content-wapper-content img{
		margin-left: 35%;
	}
	.content-wapper-content span{
		display: block;
		color: #fff;
	}
	.content-wapper-content p{
		text-align: center;
		margin-top: 20px;
	}
	.yjz{
		height: 130px;
		background: rgba(5,5,5,0.3);
	}
	.yjz p{
		text-align: center;
		font-size:24px;
		padding-top: 25px;
	}
	.yjz span{
		display: block;
		text-align: center;
		font-size: 24px;
		color: #E84C3D;
		margin-top: 20px;
	}
	.section{
		height: 300px;
		background: rgba(5,5,5,0.5);
	}
	.section-content{
		width: 50%;
		text-align: center;
		margin: 0 auto;
	}
	.section-content span{
		line-height: 30px;
		display: block;
		color: #fff;
		padding-top: 50px;
	}
	.yzs{
		height: 500px;
	}
	.yzs span{
		display: block;
		font-size: 30px;
		color: #E84C3D;
		text-align: center;
		margin-top: 20px;
	}
	.yzs p{
		font-size: 30px;
		text-align: center;
		margin-top: 20px;
	}
	.yzs img{
		margin-left: 40%;
		margin-top: 30px;
		height: 400px;
	}
	.nr-icon{
		height: 300px;
		background-color: black;
	}
</style>