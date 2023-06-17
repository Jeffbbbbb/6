<!DOCTYPE html>
<html>
<head>
        <meta charset="UTF-8">
        
        <title>台灣六都人口
 </title>
<style>
        *{margin: 0px; 
    padding: 0px;}
section{
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #161623;
    min-height: 50vh;

    }

    section::before{
        content: '';
        position: absolute;
        width: 250px;
        height: 250px;
        background: linear-gradient(#ffc107,#fff);
        border-radius: 50%;
        transform: translate(-150px,-120px);
    }
    
    section::after{
        content: '';
        position: absolute;
        width: 250px;
        height: 250px;
        background: linear-gradient(#2196f3,#fff);
        border-radius: 50%;
        transform: translate(150px,120px);
    }    


h2{font-size: 24px;}
.box{ border-radius: 10px;
    background-color: rgba(255, 255, 255, 0.1);
    border: solid 1px rgba(255, 255, 255, 0.5);
    border-right: solid 1px rgba(255, 255, 255, 0.2);
    border-bottom: solid 1px rgba(255, 255, 255, 0.2);
    color: aliceblue;
    min-width: 200px;
    min-height: 100px;
    margin: 100px; 
    padding: 10px;
    backdrop-filter: blur(10px);

    z-index: 1  ;
}
.list{display: flex;
    position: relative;
    overflow: hidden;
    background-color: rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    padding: 10px 2cap;
    margin: 10px 10px;
}

.imgBox img{width: 50px; height: 50px;
}
.list:hover{
    transform: scale(1.1) translateX(30px) translateY(-15px);
    transition: 0.5s;
    background-color: aliceblue;
    color: #010121;
    box-shadow: -15px 30px 50px rgba(0, 0, 0, 0.5);

}
.rank{
position: absolute;
right: -25px;

}
.list:hover .rank{
    right: 5px;
    transition: 0.5s;
}
</style>
    </head>
    <body>
        <section>
            <div class="box">
                <h3>台灣六都人口排行</h3>
                <div class="list">
                    <div class="imgBox">
                        <img src="新北市.png" alt="">
                    </div>
                    <div class="content">
                        <h1 class="rank"><small>#</small>1</h1>
                        <h2>新北市</h2>
                    <p>New Taipei City</p>
                    </div>
                    
                </div>
                <div class="list">
                    <div class="imgBox">
                        <img src="台中市.png" alt="">
                    </div>
                    <div class="content">
                        <h1 class="rank"><small>#</small>2</h1>
                        <h2>台中市</h2>
                    <p>Taichang City</p>
                    </div>
                    
                </div>
                <div class="list">
                    <div class="imgBox">
                        <img src="高雄市.png" alt="">
                    </div>
                    <div class="content">
                        <h1 class="rank"><small>#</small>3</h1>
                        <h2>高雄市</h2>
                    <p>Kaohsiung City</p>
                    </div>
                    
                </div>
                <div class="list">
                    <div class="imgBox">
                        <img src="台北市.png" alt="">
                    </div>
                    <div class="content">
                        <h1 class="rank"><small>#</small>4</h1>
                        <h2>台北市</h2>
                        <p>Taipei City</p>
                    </div>
                  
                </div>
                <div class="list">
                    <div class="imgBox">
                        <img src="桃園市.png" alt="">
                    </div>
                    <div class="content">
                        <h1 class="rank"><small>#</small>5</h1>
                        <h2>桃園市</h2>
                        <p>Taoyuan City</p>
                    </div>
                   
                </div>
                <div class="list">
                    <div class="imgBox">
                        <img src="台南市.png" alt="">
                    </div>
                    <div class="content">
                        <h1 class="rank"><small>#</small>6</h1>
                        <h2>台南市</h2>
                        <p>Tainan City</p>
                    </div>
                
                </div>
            </div>
        </section>
    </body>
</html>













