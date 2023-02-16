
<html lang="en">
<head>

	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	
	<title></title>
	
	<link rel="stylesheet" href="assets/styles/main.css">
	
</head>
<body style=/* restoring all the default  

   properties of the browser */
*{ 

    margin: 0; 

    padding: 0; 

    box-sizing: border-box; 
} 

  
/* all similar effects of the web page  

   so we applied them to the body */
body{ 

    height: 100vh; 

    display: flex; 

    justify-content: center; 

    align-items: center; 
} 

  
/* css effects for the color picker */
input{ 

    margin: 2em; 

    width: 3em; 

    height: 3em; 

    border: .4em solid black; 

    border-radius: 20%; 

    outline: none; 

    cursor: pointer; 

    box-shadow: 0 0 .5em #111; 
} 

  
/* for the icon that we have added */
.fas{ 

    margin: 1em; 
} 

  
/* hover effects on color picker */
input:hover{ 

    animation: round 2s infinite; 
} 

  
/* animation for our color picker */
@keyframes round{ 

    0%{ 

        transform: rotate(0deg); 

    } 

    10%{ 

        transform: rotate(60deg); 

    } 

    20%{ 

        transform: rotate(120deg); 

    } 

    40%{ 

        transform: rotate(180deg); 

    } 

    60%{ 

        transform: rotate(240deg); 

    } 

    80%{ 

        transform: rotate(300deg); 

    } 

    100%{ 

        transform: rotate(360deg); 

    } 
}>
<P>hello</P>
	<script src="assets/scripts/main.js"></script>

</body>
</html>
