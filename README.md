<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">

<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
  <title>O12</title>
  <head>
  <style>
  *{
  margin:0;/*�����߾�*/
  padding:0;
  }
  body{
background:url("images/timg.jpg") ;
  }
  
    #box{
	width:1000px;
	height:500px;
	/*background:#ff6600;*/
	margin:50px auto;
         }
		 #box ul li{/*�ڲ���ʽ ����ѡ����*/
		 position:relative;/*���Զ�λdiv*/
		 list-style:none;/*Ӱ�ص�*/
		 width:180px;
		 height:105px;
		 background:rgba(1,2,1,0.4);
		 float:left;
		 margin:30px 5px;

		 }
		 #box ul li.six{
		 margin-left:100px;
		 }
		  #box ul li div{
		  position:absolute;/*���Զ�λ������*/
		  left:0;
		  top:0;
		  width:180px;
		  height:105px;
		  background:rgba(1,2,1,0.4);
		  }
		  /*
		  #box ul li div.first{
		  transform:rotate(60deg);
		  }*/
		  /*#box ul li div.second{
		  transform:rotate(-60deg);
		  }
		 */
/*α��*/

#box ul li:before,#box ul li:after{/*,���м�����ͬ����*/
content:"";
position:absolute;/*���Զ�λ������*/
		  left:0;
		  top:0;
		  width:180px;
		  height:105px;
		  transform:rotate(60deg);
		  background:rgba(1,2,1,0.4);

}
#box ul li:after
{
		  transform:rotate(-60deg);
		
}
#box ul li img{
position:absolute;
z-index:10;/*����Խ����ʾԽǰ��*/
left:0;
top:0;
right:0;
bottom:0;
margin:auto;
transition:0.5s;
}
#box ul li img:hover{/*��̬α��*/
transform:rotate(360deg) scale(1.3);/*css�任 ��ת�Ŵ� */
}
  </style>
 </head>
   <body>
  
    <div id="box">
	 <ul>
	
	 <li>
	 <img src="images/1.png" width="80" height="80" border="0" alt="">
	 </li>
	 <li>
	 <img src="images/2.png" width="80" height="80" border="0" alt="">
	 </li>
	 <li>
	 <img src="images/3.png" width="80" height="80" border="0" alt="">
	 </li>
	 <li>
	 <img src="images/4.png" width="80" height="80" border="0" alt="">
	 </li>
	 <li>
	 <img src="images/5.png" width="80" height="80" border="0" alt="">
	 </li>
	 <li class="six">
	 <a href="http://map.baidu.com/?newmap=1&ie=utf-8&s=s%26wd%3D%E4%BC%8A%E7%8A%81%E6%9E%9C%E5%AD%90%E6%B2%9F%26c%3D1
"><img src="images/06.png" width="120" height="90" border="0" alt="���ӹ�">
	 </li>
	 <li>
	 <a href="http://map.baidu.com/?newmap=1&ie=utf-8&s=s%26wd%3D%E9%9C%8D%E5%9F%8E%E8%96%B0%E8%A1%A3%E8%8D%89%26c%3D1"><img src="images/07.png" width="120" height="90" border="0" alt="����޹�²�">
	 </li>
	 <li>
	 <a href="http://map.baidu.com/?newmap=1&ie=utf-8&s=s%26wd%3D%E9%82%A3%E6%8B%89%E6%8F%90%E8%8D%89%E5%8E%9F%26c%3D1"><img src="images/08.png" width="120" height="90" border="0" alt="����������ԭ">
	 </li>
	 <li>
	 <a href="http://map.baidu.com/?newmap=1&ie=utf-8&s=s%26wd%3D%E6%81%B0%E8%A5%BF%E7%BE%8E%E6%99%AF%26c%3D1"><img src="images/09.png" width="120" height="90" border="0" alt="ǡ������">
	 </li>
	 <li>
	 <a href="http://map.baidu.com/?newmap=1&ie=utf-8&s=s%26wd%3D%E8%B5%9B%E9%87%8C%E6%9C%A8%E6%B9%96%26c%3D1"><img src="images/010.png" width="120" height="90" border="0" alt="����ľ��">
	 </li>
	 <li>
	 <a href="http://map.baidu.com/?newmap=1&ie=utf-8&s=s%26wd%3D%E5%94%90%E5%B8%83%E6%8B%89%E7%99%BE%E9%87%8C%E7%94%BB%E5%BB%8A%26c%3D1"><img src="images/011.png" width="120" height="90" border="0" alt="�Ʋ���">
	 </li>
	 <li>
	<a href="http://map.baidu.com/?newmap=1&ie=utf-8&s=s%26wd%3D%E6%96%B0%E7%96%86%E6%96%B0%E6%BA%90%E9%87%8E%E6%9E%9C%E6%9E%97%26c%3D1"> <img src="images/012.png" width="120" height="90" border="0" alt="��ԴҰ����">
	 </li>
	 <li>
	 <a href="http://map.baidu.com/?newmap=1&ie=utf-8&s=s%26wd%3D%E8%B5%9B%E9%87%8C%E6%9C%A8%E6%B9%96%26c%3D1"><img src="images/013.png" width="120" height="90" border="0" alt="�ӻ���">
	 </li>
	 <li>
	<a href="http://map.baidu.com/?newmap=1&ie=utf-8&s=s%26wd%3D%E6%96%B0%E7%96%86%E6%98%AD%E8%8B%8F%E8%8D%89%E5%8E%9F%26c%3D1"><a href="https://www.baidu.com"> <img src="images/014.png" width="120" height="90" border="0" alt="���ղ�ԭ"></a>
	 </li>

	</ul>
   </div>
 
  </body>
</html>
