<!DOCTYPE html>
<html>
<head>

<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">    
<title>Week 2 - Solution</title>
<style>

*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: sans-serif;
}

h1 {
    margin-bottom: 15px;
    text-align: center;
    font-size: 1.75rem;
}

.container {
    width: 100%;
    position: absolute;
}

span {
    padding: 0% 5% 0% 5%;
    margin: 0% 0% 3% 180%;
    float: right;
    text-align: center;
}


p {
    width: 90%;
    margin-left: 15px;
    margin-bottom: 15px;
    padding: 0 1% 1% 1%;
    background-color: darkgrey;
    height: auto;
    border: 1px solid black;
   
}



.title1 {
    left: 80%;
    border: 1px solid black;
    color: white;
    background-color: #6C2AD5;
    font-size: 1.25em;
}

.title2 {
    left: 80%;
    border: 1px solid black;
    color: white;
    background-color: #D56C2A;
    font-size: 1.25em;
   
}

.title3 {
    left: 80%;
    border: 1px solid black;
    color: white;
    background-color: #2AD56C;
    font-size: 1.25em;
}
    
/********** Large devices only **********/
@media (min-width: 992px) {
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
     float: left;
    }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {
   .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float:left;
    border-right:-15px;
   }
    .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;

  }

</style> 
</head>
    
<body>
  <h1>Our Menu</h1>  
    <div class="container">
    <div class="col-lg-3 col-md-6 col-sm-12 box"><p><span class="title1">chicken</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat</p></div>  
   
    <div class="col-lg-3 col-md-6 col-sm-12 box"><p><span class="title2">beef</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat</p></div>
        
    <div class="col-lg-3 col-md-12 col-sm-12 box"><p><span class="title3">shushi</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat</p></div>    
    </div>
    
</body>     
</html>

