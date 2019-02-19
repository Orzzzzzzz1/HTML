<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>框架</title>
		<style type="text/css">
			body{
				background-image: url(img/timg.jpg);
				background-repeat: no-repeat;
				background-size:100%;
				height:100%;
				}
			html{height: 100%;}
			#from{
				position:absolute;
				left: 1150px;
				top:240px;
				background-color: white;
				height: 470px;
				width: 500px;
				background: rgba(0, 0, 0, 0.3);
				border-radius:20px 20px 20px 20px;
			}	
			#login_click{ 
				margin-top:32px; 
				height:80px;
					
				position:absolute;
				left:180px;
				top:250px;
				}  
			#login_click a{ text-decoration:none;  
							background:#2f435e;  
							color:#f2f2f2;
							padding: 10px 50px 10px 50px;  
							font-size:16px;  
							font-family: 微软雅黑,宋体,Arial,Helvetica,Verdana,sans-serif;  
							font-weight:bold;  
							border-radius:3px;  
							-webkit-transition:all linear 0.30s;  
							-moz-transition:all linear 0.30s;  
							transition:all linear 0.30s;}  
			#login_click a:hover { background:#385f9e; }  
			
			#form_account{
				position:absolute;
				left: 120px;
				top:83px;
				}
			#form_account input{
				
				
                border-radius: 10px;
                margin: 20px 0;
                background: url(img/1.jpg) no-repeat;
                background-color: white;
                background-position: 8px;
                padding-left: 50px;
                border: 1px solid black;
                outline: none;
			}
			#form_password{
				position:absolute;
				left:120px;
				top:173px;	
				}
			#form_password input{
				
				border-radius: 10px;
				margin: 10px 0;
				background: url(img/2.jpg) no-repeat;
				background-color: white;
				background-position: 8px;
				padding-left: 50px;
				border: 1px solid black;
				outline: none;
			}
			#password_test{
				position:absolute;
				left: 182px;
				top:56px;
				color:#385f9e ;
			}
			#password_true{
				position:absolute;
				left: 22px;
				top:34px;
			}
		</style>
	</head>
	<body>
		<div id="from">		
			<div id="form_account"> 
				<input id="txt_account" style="width: 215px; height: 35px;" runat="server" type="text" placeholder=" 用户名" />  
			</div>  
			<div id="form_password" >  
				<input id="txt_password"  style="width: 215px; height: 35px;" runat="server" type="password" placeholder=" 密码" /><br />
				<a id="password_test" href="#">忘记密码?</a>
				<p id="password_true">
					<span style="font-size:16px; color:#385f9e;">记住密码</span>
					<input id="saveCookie"   type="checkbox" value="" /></p>
				<p>
			</div>  
			<div id="login_click">  
				<a id="btlogin" href="#">登 录</a>
			</div>  
		</div>
			
		<div id="xinxi">
			
		</div>
	</body>
</html>
