# dashboard
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="stylesheet" href="styleD.css">
</head>
<body>
    <header>
        <div>
        <h4>Temperatura Média</h4>
        <h4>23</h4>
    </div>
    <div>
        <h4>Quantidade de Vans</h4>
        <h4>3</h4>
    </div>
    <div>
        <h4>Número de Alertas</h4>
        <h4>2</h4>
    </div>
        
    </header>



    <aside class="menu-lateral">
        <img src="./assets/frizzapixelfinal.png" alt="">

        <button>PetFrizza</button>
</aside>

    <main>
        <section class="main-content">
           
            <div class="van-1">
                <h3>Van 1</h3>
                <img src="./assets/van_8692766.png" alt="">

            </div>
            <div class="van-2">
                <h3>Van 2</h3>
                <img src="./assets/van_8692766.png" alt="">

            </div>
            <div class="van-3">
                <h3>Van 3</h3>
                <img src="./assets/van_8692766.png" alt="">

            </div>
        </section>
    </main>

</body>


*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;

}




header{
   
    height: 200px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    background: linear-gradient(180deg, #B3EFFF 0%, #4cb9eb 100%);

}

header div{
    height:150px;
    width: 220px;
    background: linear-gradient(#7F00FF , #E100FF);
    border: none;
    border-radius: 25px;
    font-size: 20px;
    font-weight: bold;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;

}

header h4{
    font-size: 22px;
}

aside {
    

aside img{
    height: 60px;
    width: 60px;

}

section{
    height: 100vh;
    background: linear-gradient(180deg, #B3EFFF 0%, #4cb9eb 100%);
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
    

}

section img{
    height: 200px;
    
}

section div{
    background-color: #fff;
    height: 400px;
    width: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 20px;
    flex-direction: column;
}

section h3{
    margin-bottom: 25px;
    color: rgb(163, 84, 236);
    font-size: 40px;

 
}

.van-1{
    
    
}
</html>




original
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="stylesheet" href="dashboard.css">
</head>

<body>
    <div class="container">
        <aside>
            <img src="./assets/frizzapixelfinal.png" alt="">
            <button>PetFrizza</button>

        </aside>


        <header>
            <div>
                <h4>Temperatura Média</h4>
                <h4>24</h4>
            </div>
            <div>
                <h4> Quantidade de Vans</h4>
                <h4>3</h4>
            </div>
            <div>
                <h4>Número de alertas</h4>
                <h4>2</h4>
            </div>
        </header>

      
        <section>
            <div class="van-1">
                <h5>Van 1</h5>
                <img src="./assets/van_8692766.png" alt="">
            </div>
            <div class="van-2">
                <h5>Van 2</h5>
                <img src="./assets/van_8692766.png" alt="">
            </div>
            <div class="van-3">
                <h5>Van 3</h5>
                <img src="./assets/van_8692766.png" alt="">
            </div>
        </section>

    </div>
</body>

</html>



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    height: 200px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    background: linear-gradient(180deg, #B3EFFF 0%, #4cb9eb 100%);
    position: fixed; /* Adiciona fixação */
    top: 0; /* Alinha no topo */
    z-index: 1000; /* Certifica-se de que o header fique sobre os outros elementos */
}

header div {
    height: 150px;
    width: 220px;
    background: linear-gradient(#7F00FF, #E100FF);
    border: none;
    border-radius: 25px;
    font-size: 20px;
    font-weight: bold;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;

}

header h4 {
    font-size: 22px;
}

aside img {
    height: 60px;
    width: 60px;

}



.container {
    margin-left: 200px; /* corresponde à largura do aside */
}

aside {
    width: 200px;
    height: 100vh;
    position: fixed;
    top: 0;
    left: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(180deg, #B3EFFF 0%, #4cb9eb 100%);
}

section {
   
    height: 100vh;
    background: linear-gradient(180deg, #B3EFFF 0%, #4cb9eb 100%);
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
    margin-top: 200px; /* Corresponde à altura do header */

}

section img {
    height: 200px;

}

section div {
    background-color: #fff;
    height: 400px;
    width: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 20px;
    flex-direction: column;
}

section h3 {
    margin-bottom: 25px;
    color: rgb(163, 84, 236);
    font-size: 40px;

}
