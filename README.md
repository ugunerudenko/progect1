# hover
# progect1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
  <style>
    body, html {
      background: #fff;
      width: 350px;
      height: 700px;
    }

    .head_right, .head_center, .head_left {
    height: 85px;
    background: #152840;
    overflow: hidden;
    float: left; 
    } 


    .month_short {
    width: 47px;
    padding-top: 19px; 
    }
    
    .month_long {
    width: 107px;
    padding-top: 19px;
    text-align: center;
    }

    .month_long, .month_short {
    overflow: hidden;
    float: left;
    }

    .kursor_R {
    text-align: left;
    }

    .kursor_l {
    text-align: right;
    }

    p {
      color:white;
      font-size: 16px;
    }

    .kursor_l, .kursor_R {
    width: 46px;
    padding-top: 35px;
    overflow: hidden;
    float: left;
    }

    .head_right p {

     text-align: right; 
    }
    
    .head_left p {
     text-align: left; 
    }
  
  li {
    width: 40px;
    height: 32px;
    border: 1px solid white;
    float: left;
    overflow: hidden;
    font-size: 15px;
    padding-top: 10px;
    color:white;
  }


.data {
  width: 294px;
  height: 212px;
  overflow: hidden;
  background: #152840;
  text-align: center;
}

ul {
  margin: 0;
  padding: 0;
}

.weekend {
background-color: #263a54;
}

.today {
  background-color: #56ccc8;
}

ul :hover{
  background-color: #ea6060;
}

.headcenter {
  width: 100px;
}

.head_left, .head_right {
  width: 93px;
}

  </style>
</head>
<body>
    <div class="head_left"> 
        <div class="kursor_l"><img src="arr-left.png"alt=""></div>
        <div class="month_short"><p>oct</p></div>
    </div>
    <div class="head_center"> 
        <div class="month_long"><p> <strong>November </strong></p> </div>
    </div>
  <div class="head_right"> 
  <div class="month_short"><p>dec</p></div>
  <div class="kursor_R"><img src="arr-right.png"alt=""></div>
  </div>
  <div class="data">
  <ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li>01</li>
    <li class="weekend">02</li>
    <li class="weekend">03</li>
    <li>04</li>
    <li>05</li>
    <li class="today">06</li>
    <li>07</li>
    <li>08</li>
    <li class="weekend">09</li>
    <li class="weekend">10</li>
    <li>11</li>
    <li>12</li>
    <li>13</li>
    <li>14</li>
    <li>15</li>
    <li class="weekend">16</li>
    <li class="weekend">17</li>
    <li>18</li>
    <li>19</li>
    <li>20</li>
    <li>21</li>
    <li>22</li>
    <li class="weekend">23</li>
    <li class="weekend">24</li>
    <li>25</li>
    <li>26</li>
    <li>27</li>
    <li>28</li>
    <li>29</li>
    <li class="weekend">30</li>
    <li></li>
  </ul>
  </div>


</body>
</html>