<template>
  <header>
    <div class="navbar-container">
      <div class="navbar-contenet">
        <div class="nav-text">
          </div>
          <div class="hora">
          <h1 >Milky Way Cakes</h1>
          <h5>Lunes a Viernes: 9am a 5pm</h5>
          <h5>sabados: 11am a 4pm</h5>
          <h5>Telefono (+54) 55 74 96 38 51</h5>
          </div>
          <div>
         </div>
        </div>
      </div>
      <div><img class="portada"   src=".\assets\header-bg.jpg"></div>
      <br>
  </header>
  <body>
		<div >
				<h6>Galaxy Cakes.</h6>
					<h1>Pasteles Hechos A Mano <br>
					</h1>
					<p><span>El Mejor Sabor fuera de este mundo</span></p>
					<p>
						Nuestros pasteles son de la mejor calidad con el mejor sabor somos una pasteleria conocida por hacer pasteles y adornos con la tematica del espacio.
					</p>
			</div>
      <br>
      <div class="pasteles" >
					<h1 class="mb-10">Estacion de Pasteles Internacional🚀</h1>
							<p>Paquetes Favoritos de Nuestros Clientes.</p>
              <h4>Space  Chocolate</h4>
              <div><img class="p1"   src=".\assets\p1.png"></div>
								<p class="price float-right">
									$179
								</p>
								<p>
									Pastel de 3 leches con  cubiertas de chocolate.
								</p>
      </div>
      <div class="pasteles" >
              <h4>Space  vainilla</h4>
              <div><img class="p1"   src=".\assets\p2.png"></div>
								<p class="price float-right">
									$179
								</p>
								<p>
									Pastel de 3 leches con  cubiertas de vainilla.
								</p>
      </div>
      <div class="pasteles" >
              <h4>Space  Fresa</h4>
              <div><img class="p1"   src=".\assets\p3.png"></div>
								<p class="price float-right">
									$179
								</p>
								<p>
									Pastel de 3 leches con  cubiertas de Fresa.
								</p>
      </div>
      <div class="adornos" >
					<h1 class="mb-10">Adornos🚀</h1>
							<p></p>
              <h4>Space  Chocolate</h4>
              <div><img class="p1"   src=".\assets\f4.png"></div>
              <p>
                adornos de plastico Precio: $74
              </p>
              <div><img class="p1"   src=".\assets\f5.png">
              <p>
                adornos de coleccionables Precio: $99
              </p>
              </div><div><img class="p1"   src=".\assets\f6.png"></div>
              <p>
                adornos de comestibles Precio: $99
              </p>
				
      </div>
      <div class="adornos">
					<h1 class="mb-10">Personalizado</h1>
										<h3 class="mb-30">Adornos</h3>
										<div class="default-select" id="default-select">
											<select>
												<option value="1">Escoge una opcion</option>
												<option value="1">Plastico</option>
												<option value="1">Coleccionable</option>
												<option value="1">Comestible</option>
											</select>
										</div>
			
      </div>
										<h3 class="mb-30">Pastel</h3>
										<div class="default-select" id="default-select">
											<select>
												<option value="1">Escoge una opcion</option>
												<option value="1">Chocolate</option>
												<option value="1">Fresa</option>
												<option value="1">Vainilla</option>
											</select>
			</div>
								<h3 class="mb-30">Pedido Personalizados</h3>
									<div class="mt-10">
										<input type="text" name="first_name" placeholder="Nombre" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Nombre'" required class="single-input">
									</div>
									<div class="mt-10">
										<input type="text" name="last_name" placeholder="apellidos" onfocus="this.placeholder = ''" onblur="this.placeholder = 'apellidos'" required class="single-input">
									</div>
									<div class="mt-10">
										<input type="text" name="fhone" placeholder="Numero de telefono" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Numero de telefono'" required class="single-input">
									</div>
									<div class="mt-10">
										<input type="email" name="EMAIL" placeholder="Correo electronico" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Correo electronico'" required class="single-input">
									</div>
									<div class="input-group-icon mt-10">
										<div class="icon"><i class="fa fa-thumb-tack" aria-hidden="true"></i></div>
										<input type="text" name="Direccion" placeholder="Direccion" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Direccion'" required class="single-input">
									</div>
									<div class="input-group-icon mt-10">
										<div class="icon"><i class="fa fa-plane" aria-hidden="true"></i></div>
										<div class="form-select" id="default-select">
											<select>
												<option value="1">Ciudad</option>
												<option value="1">CD de Mexico</option>
												<option value="1">EDO de Mexico</option>
												<option value="1">Puebla</option>
											</select>
										</div>
									</div>
									<div class="input-group-icon mt-10">
										<div class="icon"><i class="fa fa-globe" aria-hidden="true"></i></div>
										<div class="form-select" id="default-select">
											<select>
												<option value="1">Pais</option>
												<option value="1">Mexico</option>
												<option value="1">EUA Coming soon</option>
											</select>
										</div>
									</div>
                  <div>
												<button><a href="" class="genric-btn primary">Enviar</a></button>
										</div>             
   </body>
     

     
</template>

<script>

</script>

<style>

.navbar-container{
width: 100%;
background-color: rgba(182, 107, 8, 0.527);
}

.navbar-contenet{
padding: 10px;
}

.icons{
  size: 100px;
  width: 90px;
  height: 50px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  margin-top: 60px;
}

.hora{
height: auto;
color: rgb(255,255,255);
}

.portada{ 
  height: 100%;
  width: 100%;
  
}
.pasteles{
  background-color:rgba(182, 107, 8, 0.527);
}

.p1{
  width: 101px;
  height: 101px;
}

</style>
