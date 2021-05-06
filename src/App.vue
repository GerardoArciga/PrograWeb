<template>}
  <section id='header'>
    <article id='banner'>
      <h1 >Mi proyecto web</h1>
    </article>
  </section>
  <section>
        <nav id="menu">
            <ul>
                <li><router-link to="/hola">Principal</router-link> </li>
                <li><router-link to="inicio.html">Saludo</router-link></li>
                <li><router-link to="/acerca">Acerca de</router-link></li>
                <li><router-link to="tablas.html">Tablas</router-link></li>
                <li><router-link to="card.html">Social Media</router-link></li>
            </ul>
        </nav>
       
    </section>

  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
  
</template>

<style>
@import url('https://necolas.github.io/normalize.css/8.0.1/normalize.css');
html, body { 
    margin: 0; padding: 0%;
}
#banner {
    background: url('assets/images/banner1.jpg'); 
    height: 250px;
}

#banner h1 {
    color: white;
    text-align: center;
}
#menu {
    background:#531B94 ;
    height: 50px;
    min-height: 50px;
}
#menu ul li {
    display: inline;
    
}

#menu ul li a {
    text-decoration: none;
    color: white;
}
#menu ul li a:hover {
    text-decoration: underline;
    color: rgba(255,255, 255, 0.5);
}

#menu ul {
    height: 100%;
    margin: 0px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
 }

</style>
