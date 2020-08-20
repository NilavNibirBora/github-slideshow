<!DOCTYPE HTML>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trigonometry</title>
    
    
    <style type="text/css" media="all">
    body {
      background-color: yellow;
    }
    .mydiv {
      background-color: blue;
      border: 5px dotted orange;
    }
    button {
      background-color: yellow;
      color: red;
    }
    h1 {
      text-align: center;
    }
    #unit {
      color: white;
    }
      
    </style>
    
    
    <script>
    function func1() {
      var angle = document.getElementById('ang').value;
      var dist = document.getElementById('dist').value;
   
      
      var radn = angle * (Math.PI/180);
      var height = Math.tan(radn) * dist;
      
      alert('Hello ! The Height is : ' + height + ' cm/m');
      
      
    }
      
    </script>
    
    
  </head>
  
  
  
  
  
  
  <body>
    
    <h1>Find Height Using <br> Trigonometry</h1>
    
    
    <div class="mydiv">
      
    <input type="number" id="ang"
    placeholder="Type The Angle "/>
    
    
    <br />
    <br />
    
    
    <input type="number" id="dist" value="Distance" placeholder="Type The Distance"/>
    
    
    <div id="unit">
    <input type="radio" name="unit" id="unit1" value="cm"/>cm
    
    
    <input type="radio" name="unit" id="unit2" value="m" />m
    
    
    </div>
    
    
    <br>
    <br>
    
    
    <button onclick="func1()" type="submit">Click To Submit </button>
    </div>
    
    <p style="text-align:center"><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><em>
      Made In India <br />Copyright©2020 nilavnibirbora</em></p>
  </body>
</html>
