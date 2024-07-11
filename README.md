{
    margin: 0;
    padding: 0;
    font-family: 'poppins', sans-serif;
    box-sizing: border-box;
}
body{
    background: blue;
}
.app{
    background: #fff;
    width: 90%;
    max-width: 600px;
    margin: 100px auto 0;
    border-radius: 10px;
    padding: 30px;
}
.app h1{
    font-size: 25px;
    color: #001e4d;
    font-weight: 600;
    border-bottom: 1px solid black;
    padding-bottom: 30px;
}
.quiz{
    padding: 20px 0;
}
.quiz h2{
font-size: 18px;
color: #001e4d;
font-weight: 600;
}
.btn{
    background: white;
    color: #222;
    font-weight: 500;
    width: 100%;
    border: 1px solid black;
    padding: 10px;
    margin: 10px 0;
    text-align: left;
    border-radius: 4px;
    cursor: pointer;
    transition: all 0.3s;
}
.btn:hover:not([disabled]){
    background: #222;
    color: white;
}
.btn:disabled{
    cursor: no-drop;
}
#next-btn{
    background: #001e4d;
    color: white;
    font-weight: 500;
    width: 150px;
    border: 0;
    padding: 10px;
    margin: 20px auto 0;
    border-radius: 4px;
    cursor: pointer;
    display: block;
}
.correct{
    background: #9aeabc;
}
.incorrect{
    background: #ff9393;
