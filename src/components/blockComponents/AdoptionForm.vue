<script setup lang="ts">

</script>

<template>
<form class="container needs-validation" novalidate>
    <div class="row mb-2">
        <div class="col-12">
            <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                <div class="col-12 p-4 d-flex flex-column position-static">
                    <h3 class="d-inline-block mb-2 text-primary text-center">Formulario de Adopción</h3>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput1" class="form-label">Tipo de documento*</label>
                      <select class="form-select" aria-label="Default select example" id="exampleFormControlInput1">
                        <option value="">Seleccione...</option>
                        <option value="1">Cédula</option>
                        <option value="2">NIT</option>
                        <option value="3">Cédula Extranjera</option>
                        <option value="4">Pasaporte</option>
                        <option value="5">Tarjeta de Identidad</option>
                        <option value="6">Permiso Especial de Permanencia</option> </select>
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput2" class="form-label">No. de documento*</label>
                      <input type="text" class="form-control" id="exampleFormControlInput2" placeholder="">
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput3" class="form-label">Nombres*</label>
                      <input type="text" class="form-control" id="exampleFormControlInput3" placeholder="">
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput4" class="form-label">Apellidos*</label>
                      <input type="text" class="form-control" id="exampleFormControlInput4" placeholder="">
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput5" class="form-label">Fecha de Nacimiento*</label>
                      <input type="date" class="form-control" id="exampleFormControlInput5" placeholder="">
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput6" class="form-label">Teléfono*</label>
                      <input type="text" class="form-control" id="exampleFormControlInput6" placeholder="">
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput7" class="form-label">Dirección*</label>
                      <input type="text" class="form-control" id="exampleFormControlInput7" placeholder="">
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput8" class="form-label">Localidad*</label>
                      <select class="form-select" aria-label="Default select example" id="exampleFormControlInput8">
                        <option value="">Seleccione...</option>
                        <option value="1">Usaquén</option>
                        <option value="2">Chapinero</option>
                        <option value="3">Santa Fe</option>
                        <option value="4">San Cristóbal</option>
                        <option value="5">Usme</option>
                        <option value="6">Tunjuelito</option>
                        <option value="7">Bosa</option>
                        <option value="8">Kennedy</option>
                        <option value="9">Fontibón</option>
                        <option value="10">Engativá</option>
                        <option value="11">Suba</option>
                        <option value="12">Barrios Unidos</option>
                        <option value="13">Teusaquillo</option>
                        <option value="14">Los Mártires</option>
                        <option value="15">Antonio Nariño</option>
                        <option value="16">Puente Aranda</option>
                        <option value="17">La Candelaria</option><option value="18">Rafael Uribe Uribe</option><option value="19">Ciudad Bolívar</option>
                        <option value="20">Sumapaz</option> 
                      </select>
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput9" class="form-label">Barrio*</label>
                      <input type="text" class="form-control" id="exampleFormControlInput9" placeholder="">
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput10" class="form-label">Profesión*</label>
                      <input type="text" class="form-control" id="exampleFormControlInput10" placeholder="">
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput11" class="form-label">Vive en*</label>
                      <select class="form-select" aria-label="Default select example" id="exampleFormControlInput11">
                        <option value="">Seleccione...</option>
                        <option value="Casa">Casa</option>
                        <option value="Apartamento">Apartamento</option>
                      </select>
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput12" class="form-label">Tipo de vivienda*</label>
                      <select class="form-select" aria-label="Default select example" id="exampleFormControlInput12">
                        <option value="">Seleccione...</option>
                        <option value="Propia">Propia</option>
                        <option value="Arrendada">Arrendada</option>
                      </select>
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput13" class="form-label">Correo electrónico*</label>
                      <input type="email" class="form-control" id="exampleFormControlInput13" placeholder="">
                    </div>
                </div>
                <div class="col-12 col-lg-6 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput14" class="form-label">¿Anteriormente o en la actualidad cuenta con animales de compañía?*</label>
                      <select class="form-select" aria-label="Default select example" id="exampleFormControlInput14">
                        <option value="">Seleccione...</option>
                        <option value="SI">Sí</option>
                        <option value="NO">No</option>
                      </select>
                    </div>
                </div>
                <div class="col-12 px-4">
                    <div class="mb-3">
                      <label for="exampleFormControlInput15" class="form-label">Nucleo familiar*</label>
                      <textarea class="form-control" id="exampleFormControlInput15" rows="3" placeholder="Explique brevemente como esta conformada su nucleo familiar."></textarea> 
                    </div>
                </div>
                <div class="col-12 p-4 d-flex flex-column position-static">
                    <p class="card-text">
                        Los datos solicitados en el presente formulario, tienen como único fin, recopilar información necesaria para que el Instituto Distrital de Protección y Bienestar Animal (IDPYBA) para el programa de adopciones. Dando cumplimiento a lo dispuesto en la Ley 1581 de 2012 y el Decreto 1377 de 2013, sobre la protección de datos personales, solicitamos públicamente su autorización, para continuar con el tratamiento de su información personal de una manera responsable, confiable y legal.
                    </p>
                    <div class="form-check">
                      <input class="form-check-input" type="checkbox" value="" id="invalidCheck" required>
                      <label class="form-check-label" for="invalidCheck">
                        Aceptar términos y condiciones.
                      </label>
                      <div class="invalid-feedback">
                        You must agree before submitting.
                      </div>
                    </div>
                    <div class="d-flex justify-content-center align-items-center text-center">
                        <button type="submit" class="btn btn-sm btn-success" >Enviar solicitud</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</form> 
</template>

<style scoped>
</style>
