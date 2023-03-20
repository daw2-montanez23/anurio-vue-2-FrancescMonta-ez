<template>
      <div id="Alumnos" class="bg-success">
        <h1 class="pt-4 pb-4 text-center fs-1"><i class="fa-solid fa-user-tie pe-3"></i>Alumnos</h1>
        <div class="row">
            <div class="col-2 d-flex justify-content-center offset-1">
                <div class="card" style="width: 15rem;">
                  <a href="#"><img class="card-img-top imagen_card" src="../img/ElJavi.jpg" alt="Javi"></a>
                  <div class="card-body">
                    <h5 class="card-title">Javi</h5>
                </div>
            </div>
        </div>
        <div class="col-2 d-flex justify-content-center">
            <div class="card" style="width: 15rem;">
                <a href="#"><img class="card-img-top imagen_card" src="../img/ElJona.jpg" alt="Jona"></a>
                <div class="card-body">
                    <h5 class="card-title">Jona</h5>
                  </div>
                </div>
            </div>
            <div class="col-2 d-flex justify-content-center">
                <div class="card" style="width: 15rem;">
                  <a href="#"><img class="card-img-top imagen_card" src="../img/wilbern.jpg" alt="Wilbern"></a>
                  <div class="card-body">
                    <h5 class="card-title">Wilvern</h5>
                  </div>
                </div>
            </div>
            <div class="col-2 d-flex justify-content-center">
                <div class="card" style="width: 15rem;">
                  <a href="#"><img class="card-img-top imagen_card" src="../img/ElMati.jpg" alt="Mati"></a>
                  <div class="card-body">
                    <h5 class="card-title">Mati</h5>
                  </div>
                </div>
            </div>
            <div class="col-2 d-flex justify-content-center">
                <div class="card" style="width: 15rem;">
                  <a href="#"><img class="card-img-top imagen_card" src="../img/sergio.jpg" alt="Sergio"></a>
                  <div class="card-body">
                    <h5 class="card-title">Sergio Coco</h5>
                  </div>
                </div>
            </div>
        </div>
    </div>  
</template>

<script>
    export default{
        name: 'Alumnos',
        props:{
            msg: String
        }
    }
</script>