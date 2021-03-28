<html>
	<head>
		<title>
		      анимэйшн
		</title>
		<style>
		.container {
		   position: absolute;
		   top: 50px;
		   left: 50px;
		   width: 400px;
		   height: 200px;
		   background-color: red;
		   padding: 50px 25px 50px 25px;
		   transition: all 0.5s;
		  
		   
		   
		  
	
		}

		
		</style>
	</head>
	     <body>
		   <input type="button" value="start" onclick="startAnimation()">
		      <div id="container" class = "container">
			    <img src "https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.nlevel.ru%2Fwp-content%2Fuploads%2F2019%2F05%2Fefe2334ac0.jpg&imgrefurl=https%3A%2F%2Fwww.nlevel.ru%2Fkatalog%2Figrushki%2Figrushechnaia-mashinka-sphero-mcqueen%2F&tbnid=ZQKIhcYA-bTTMM&vet=12ahUKEwjnif7TyNLvAhXJvSoKHYZoAHQQMyhYegUIARCgAg..i&docid=9aOVPp5Yrm1RqM&w=500&h=500&q=%D0%BC%D0%B0%D1%88%D0%B8%D0%BD%D0%BA%D0%B0&ved=2ahUKEwjnif7TyNLvAhXJvSoKHYZoAHQQMyhYegUIARCgAg">
		 		  Block    
		      </div>
               <span class="circle">
			   </span>
			  <br>
 
			  

		       <input type = "button" value="start" onclick="startAnimation()">
			   <input type = "button" value="Save Cat" onclick="stopAnimation()">
	          <script>
			    let intervalId;
		        function startAnimation () {
				       intervalId = setInterval(function() {
					      container.style.top = parseInt(container.style.top || 50) + 10
				   
				   },1000);
				    
				
				
				}
				 
		         function stopAnimation () {
		             clearInterval(intervalId);
		       }
		  
		  
              </script>
	     </body>
</html># -
