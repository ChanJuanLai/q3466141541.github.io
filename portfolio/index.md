---
layout: default
title:  "网页设计作品——H5最最最邀请的邀请函"
date:   2018-01-03 22:07:50 +0800
categories: portfolio
image:
  teaser: B.jpg
  feature: B.jpg
---
---
## 运用基础所学知识可以做一个有小按钮的网页邀请函！（example：https://q3466141541.github.io/hapipi/ ）
代码如下 耐心一个一个慢慢打出来  
```
 @charset "UTF-8";
	html,body{
		       height:100%;
			   color:#ffffff;
			   font-family:sans-serif;
	}
    body{
		       background:url(dream.jpg) center center;  #注解：dream是我自己选的背景图的名字哦，注意修改
		       background-size:cover;
			   margin:0;
			   padding:0;
			   position:relative;
	}
    #container{
		      width:100%;
			  text-align:center;
			  position:absolute;
			  top:50%;
			  transform:translateY(-50%)
			  -ms-transform:translateY(-50%); 
			  -moz-transform:translateY(-50%); 
			  -webkit-transform:translateY(-50%); 
			  -o-transform:translateY(-50%);
	}
	h1{
		     font-size:60px;
		     margin-bottom:20px;
	}
	p{
		     font-size:32px;
			 margin-bottom:40px;
			 margin-left:40px;
			 margin-right:40px;
	}
	a{
		     font-size:20px;
			 color:#fff;
			 border:5px solid #fff;
			 border-radius:3px;
			 padding:10px  50px;
			 text-decoration:none;
	}

```

