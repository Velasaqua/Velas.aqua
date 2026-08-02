*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Georgia', serif;
}

body{
    background:#f8f3e8;
    color:#123b4a;
}

.hero{
    height:100vh;
    background:
    linear-gradient(rgba(0,80,100,.35),rgba(0,0,0,.35)),
    url("https://images.unsplash.com/photo-1507525428034-b723cf961d3e");
    background-size:cover;
    background-position:center;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero h1{
    font-size:70px;
    letter-spacing:3px;
    text-shadow:0 5px 20px #000;
}

.hero p{
    font-size:25px;
    margin:20px;
}

.btn{
    background:#d4af37;
    color:white;
    padding:15px 30px;
    border-radius:40px;
    text-decoration:none;
    font-weight:bold;
    transition:.3s;
}

.btn:hover{
    transform:scale(1.08);
}

section{
    padding:60px 20px;
    text-align:center;
}

h2{
    font-size:35px;
    margin-bottom:20px;
}

.cards{
    display:flex;
    justify-content:center;
    gap:25px;
    flex-wrap:wrap;
}

.card{
    background:white;
    width:280px;
    padding:30px;
    border-radius:25px;
    box-shadow:0 10px 30px rgba(0,0,0,.15);
}

.card h3{
    margin-bottom:15px;
    color:#007c91;
}

.contact{
    background:#007c91;
    color:white;
}

footer{
    background:#062f3a;
    color:white;
    text-align:center;
    padding:20px;
}

@media(max-width:600px){
    .hero h1{
        font-size:45px;
    }

    .hero p{
        font-size:18px;
    }
}
