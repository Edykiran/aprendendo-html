*{
    margin: 0;
    padding: 0;
}

body{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 10px;
}

header{
    display: flex;
    background-color: #A0CCF2;
    align-items: center;
    justify-content: space-between;
    top: 0;
    box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    line-height: 60px;
}

.logo{
    font-size: 2.1rem;
    font-weight: 700;
    color: #072B59;
    text-shadow: 1px 1px #8C8080;
    text-decoration: none;
    letter-spacing: 2px;
    padding-left: 20px;
}

.navbar ul{
    display: flex;
    list-style: none;
}

.navbar a{
    text-decoration: none;
    font-size: 1.6rem;
    color: #266AA6;
    padding: 22px;
}

.navbar a:hover{
    background-color:#A6A6A6;
}
#hero{
    background-image: url('../img/hero.jpg');
    width: 100%;
    height: 100vh;
    background-position: center;
    background-position: no-repeat;
    background-size: cover;
}
