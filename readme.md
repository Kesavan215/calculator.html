 # style.css
 *{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;            
    box-sizing: border-box;
}


.container {
    width: 100%;
    height: 100vh;
    background: #1585a4;
    display: flex;
    align-items: center;
    justify-content: center;
}
.calculator{
    background: #080808;
    padding: 100px;
    border-radius: 50px;
}
.calculator form input{
    border: 0;
    outline: 0;
    width: 60px;
    height: 60px;
    border-radius: 10px;
    box-shadow: -8px -8px 15px rgba(255, 255, 255, 0.1), 5px 5px 15px rgba(0, 0, 0, 0.2);
    background: transparent;
    font-size: 20px;
    color: #e1c406;
    cursor: pointer;
    margin: 10px;
}

form .display{
    display: flex;
    justify-content: flex-end;
    margin: 20px 0;
}
form display input{
    text-align: right;
    flex: 1;
    font-size: 45px;
    box-shadow: none;
}
form input.equal{
    width: 145px;
}



Form input.operator{
    color:#05eec3
}
    
