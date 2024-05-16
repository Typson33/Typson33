<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora Multas CNP</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<style>
    .hidden {
        display: none;
    }
</style>

<body class="bg-gray-200 p-20">
    <div class="bg-blue-600 p-4 fixed top-0 left-0 w-full z-10">
        <div class="container flex justify-between items-center">
            <!-- Searchbar en la navbar -->
            <div>
                <input type="text" id="searchInput" class="p-2 rounded" placeholder="Buscar...">
                <button id="goToCommand"
                    class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded mr-4">Ir Al
                    Comando</button>
            </div>
            <div>

                <span class="text-white">                                                                                                                                                  
                    </div>
                    <img class="icon" src="" <class="container flex justify-between items-center">
                    <img class="icon" src=""  <class="container flex justify-between items-right">
                   
              
            </div>
        </div>
    </div>

    <div class="container mx-auto pt-16">

        <ul class="list-inside pl-5 space-y-3" id="articlesList">
            
            
        




            <li id="art-1-1" class="flex items-center py-2" data-sancion="200 €"> Art. 1.1 - Uso excesivo de claxon: 200 € 

            <li id="art-1-2" class="flex items-center py-2" data-sancion="250 €"> Art. 1.2 - Giro indebido: 250 €
               
            <li id="art-1-3" class="flex items-center py-2" data-sancion="275 €"> Art. 1.3 - Cambio de carril en línea continua: 275 €
 
            <li id="art-1-4" class="flex items-center py-2" data-sancion="400 € + Retirada de la licencia."> Art. 1.4 - Circular en sentido contrario: 400 € + Retirada de la licencia. 

            <li id="art-1-5" class="flex items-center py-2" data-sancion="150 €"> Art. 1.5 - Estacionar de manera incorrecta: 150 € 

            <li id="art-1-6" class="flex items-center py-2" data-sancion="300 €"> Art. 1.6 - Obstruir la circulación: 300 € 

            <li id="art-1-7" class="flex items-center py-2" data-sancion="225 €"> Art. 1.7 - Saltarse un STOP: 225 €
              
            <li id="art-1-8" class="flex items-center py-2" data-sancion="300 €"> Art. 1.8 - Saltarse un semáforo: 300 €
              
            <li id="art-1-9" class="flex items-center py-2" data-sancion="1250 € + Retirada de la licencia."> Art. 1.9 - No ceder el paso a vehículos de emergencia: 1250 € + Retirada de la licencia. 

            <li id="art-1-10" class="flex items-center py-2" data-sancion="325 €"> Art. 1.10 - Realizar un adelantamiento indebido: 325 € 

            <li id="art-1-11" class="flex items-center py-2" data-sancion="350 € + Retirada de la licencia."> Art. 1.11 - Circular marcha atrás: 350 € + Retirada de la licencia.
 
            <li id="art-1-12" class="flex items-center py-2" data-sancion="375 €"> Art. 1.12 - Ignorar las indicaciones de un policía: 375 € 

            <li id="art-1-13" class="flex items-center py-2" data-sancion="450 €"> Art. 1.13 - Evadir un control policial: 450 €
 
            <li id="art-1-14" class="flex items-center py-2" data-sancion="1150 € + Retirada de la licencia."> Art. 1.14 - Darse a la fuga de un control policial: 1150 € + Retirada de la licencia. 

            <li id="art-1-15" class="flex items-center py-2" data-sancion="350 €"> Art. 1.15 - Exceso de velocidad en vías interurbanas: 350 €

            <li id="art-1-16" class="flex items-center py-2" data-sancion="250 €"> Art. 1.16 Exceso de velocidad en vías secundarias: 250 €

            <li id="art-1-17" class="flex items-center py-2" data-sancion="275 € + Vehículo Incautado."> Art. 1.17 - Conducir con el vehículo en malas condiciones: 275 € + vehículo incautado.

            <li id="art-1-18" class="flex items-center py-2" data-sancion="300 €"> Art. 1.18 - Conducir por la noche sin las luces: 300 € 

            <li id="art-1-19" class="flex items-center py-2" data-sancion="100 €"> Art. 1.19 - Conducir por el día con las luces: 100 € 

            <li id="art-1-20" class="flex items-center py-2" data-sancion="325 €"> Art. 1.20 - Conducir en un túnel o lugares oscuros sin luces: 325 € 

            <li id="art-1-21" class="flex items-center py-2" data-sancion="350 €"> Art. 1.21 - Circular por zonas no autorizadas: 350 € 
                
            <li id="art-1-22" class="flex items-center py-2" data-sancion="450 €"> Art. 1.22 - Estacionar en zonas no autorizadas: 450 € 
                
            <li id="art-1-23" class="flex items-center py-2" data-sancion="4500 € + Retirada de la licencia."> Art. 1.23 - Conducir bajo las influencias del alcohol: 4500 € + Retirada de la licencia. 
                
            <li id="art-1-24" class="flex items-center py-2" data-sancion="5500  € + Retirada de la licencia."> Art.1.24 - Conducir bajo la influencia de estupefacientes: 5500  € + Retirada de la licencia. 
                
            <li id="art-1-25" class="flex items-center py-2" data-sancion="750 € + Vehículo Incautado."> Art. 1.25 - Circular sin permiso de conducir: 750 € + Vehículo Incautado. 
                
            <li id="art-1-26" class="flex items-center py-2" data-sancion="375 € + Vehículo Incautado."> Art. 1.26 - Circular con el permiso de conducir caducado: 375 € + Vehículo Incautado. 
                
            <li id="art-1-27" class="flex items-center py-2" data-sancion="1000 € + Retirada de la licencia."> Art. 1.27 - Provocar una accidente: 1000 € + Retirada de la licencia. 
            
            <li id="art-1-28" class="flex items-center py-2" data-sancion="2100 € + Retirada de la licencia + Vehículo Incautado."> Art. 1.28 - Provocar un accidente y darse a la fuga: 2100 € + Retirada de la licencia + Vehículo Incautado. 
                
            <li id="art-1-29" class="flex items-center py-2" data-sancion="175 €"> Art. 1.29 - Acoso al volante: 175 €
                
            <li id="art-1-30" class="flex items-center py-2" data-sancion="100-5500 € (Depende de los daños)"> Art. 1.30 - Dañar mobiliario urbano: 100-5500 € (Depende de los daños) 
                
            <li id="art-1-31" class="flex items-center py-2" data-sancion="1250 € + Retirada de la licencia + Vehículo Incautado."> Art. 1.31 - Atropellar a alguien: 1250 € + Retirada de la licencia + Vehículo Incautado. 
                
            <li id="art-1-32" class="flex items-center py-2" data-sancion="1570 € + Retirada de la licencia + Vehículo Incautado."> Art. 1.32 - Participar o crear una carrera ilegal: 1570 € + Retirada de la licencia + Vehículo Incautado. 
                
            <li id="art-1-33" class="flex items-center py-2" data-sancion="300 €"> Art. 1.33 - Conducir con la ITV caducada: 300 € 
                
            <li id="art-1-34" class="flex items-center py-2" data-sancion="100€"> Art. 1.34 - Conducir sin el cinturón de seguridad: 100€ 
                
            <li id="art-1-35" class="flex items-center py-2" data-sancion="1575 € + Vehículo Incautado."> Art. 1.35 - Llevar a una persona en el maletero: 1575 € + Vehículo Incautado. 
                
            <li id="art-1-36" class="flex items-center py-2" data-sancion="2100 € + Retirada de la licencia + Vehículo Incautado."> Art. 1.36 - Iniciar una persecución: 2100 € + Retirada de la licencia + Vehículo Incautado. 
                
            <li id="art-1-37" class="flex items-center py-2" data-sancion="100 €"> Art. 1.37 - Tirar objetos por la ventanilla del coche: 100 € 
                
            <li id="art-1-38" class="flex items-center py-2" data-sancion="150 €"> Art. 1.38 - Uso de suspensión hidráulica en movimiento: 150 € 
                
            <li id="art-1-39" class="flex items-center py-2" data-sancion="450 € + Retirada de la licencia."> Art. 1.39 - Conducir un vehículo sin matrícula: 450 € + Retirada de la licencia. 
                
            <li id="art-1-40" class="flex items-center py-2" data-sancion="1000 € + Retirada de la licencia + Vehículo Incautado."> Art. 1.40 - Conducir un vehículo con matrícula modificada o falsa: 1000 € + Retirada de la licencia + Vehículo Incautado. 

            <li id="art-1-41" class="flex items-center py-2" data-sancion="1350 €"> Art. 1.41 - Omisión al socorro de una persona no atendida: 1350 € 
                
            <li id="art-1-42" class="flex items-center py-2" data-sancion="900 € + Devolver lo estafado."> Art. 1.42 - Alterar el taxímetro: 900 € + Devolver lo estafado. 
                
            <li id="art-1-43" class="flex items-center py-2" data-sancion="250-3000 € (Dependiendo del tiempo en el que haya permanecido)"> Art. 1.43 - Dejar a un niño sin supervisión en el interior de un vehículo: 250-3000 € (Dependiendo del tiempo en el que haya permanecido) 
                
            <li id="art-1-44" class="flex items-center py-2" data-sancion="200 €"> Art. 1.44 - No hacer uso de los intermitentes: 200 € 
                
            <li id="art-1-45" class="flex items-center py-2" data-sancion="350 €"> Art. 1.45 - Hacer mal uso de los intermitentes: 350 € 
                
            <li id="art-1-46" class="flex items-center py-2" data-sancion="500 € + Retirada de la licencia."> Art. 1.46 - Utilizar dispositivos móviles mientras conduces: 500 € + Retirada de la licencia. 
                
            <li id="art-1-47" class="flex items-center py-2" data-sancion="300 €"> Art. 1.47 - Conducir siendo menor de edad: 300 € 
                
            <li id="art-1-48" class="flex items-center py-2" data-sancion="100 €"> Art. 1.48 - No guardar la distancia de seguridad entre vehículos: 100 € 
                
            <li id="art-1-49" class="flex items-center py-2" data-sancion="625 € + Retirada de la licencia."> Art. 1.49 - Conducción temeraria: 625 € + Retirada de la licencia. 
                
            <li id="art-1-50" class="flex items-center py-2" data-sancion="75 €"> Art. 1.50 - Llevar la música demasiado alta: 75€ 
                
            <li id="art-1-51" class="flex items-center py-2" data-sancion="100-3500€ (Dependiendo del elemento encontrado)"> Art. 1.51 - Posesión de elementos ilícitos en el interior del vehículo: 100-3500€ (Dependiendo del elemento encontrado) 
                
            <li id="art-1-52" class="flex items-center py-2" data-sancion="850 € + Retirada del material."> Art. 1.52 - Transportar material inflamable o explosivo en vehículos no acondicionados: 850 € + Retirada del material. 
                
            <li id="art-1-53" class="flex items-center py-2" data-sancion="575€ + Retirada del material."> Art. 1.53 - Transportar material inflamable o explosivo sin permiso: 575€ + Retirada del material. 
                
            <li id="art-1-54" class="flex items-center py-2" data-sancion="375€ + Retirada de la licencia + Vehículo Incautado."> Art. 1.54 - Conducir un vehículo sin tener el seguro activo: 375€ + Retirada de la licencia + Vehículo Incautado. 



                
            <li id="art-2-1" class="flex items-center py-2" data-sancion="150 €"> Art. 2.1 - Robo a un civil: 150 €
                
            <li id="art-2-2" class="flex items-center py-2" data-sancion="250 €"> Art. 2.2 - Robo a un civil con arma blanca: 250 € 
                
            <li id="art-2-3" class="flex items-center py-2" data-sancion="400 €"> Art. 2.3 - Robo a un civil con arma de fuego corta: 400 € 
                
            <li id="art-2-4" class="flex items-center py-2" data-sancion="700 €"> Art. 2.4 - Robo a un civil con arma de fuego larga: 700 € 
                
            <li id="art-2-5" class="flex items-center py-2" data-sancion="750 €"> Art. 2.5 - Robo a un civil con arma de fuego "casera/especial": 750 € 
                
            <li id="art-2-6" class="flex items-center py-2" data-sancion="700 €"> Art. 2.6 - Robo a un funcionario del estado: 700 € 
                
            <li id="art-2-7" class="flex items-center py-2" data-sancion="750 €"> Art. 2.7 - Robo a un funcionario del estado con arma blanca: 750 € 
                
            <li id="art-2-8" class="flex items-center py-2" data-sancion="875 €"> Art. 2.8 - Robo a un funcionario del estado con arma de fuego corta: 875 € 
                
            <li id="art-2-9" class="flex items-center py-2" data-sancion="1000 €"> Art. 2.9 - Robo a un funcionario del estado con arma de fuego larga: 1000 € 

            <li id="art-2-10" class="flex items-center py-2" data-sancion="1250 €"> Art. 2.10 - Robo a un funcionario del estado con arma de fuego "casera/especial": 1250 € 
                
            <li id="art-2-11" class="flex items-center py-2" data-sancion="225 €"> Art. 2.11 - Asalto a un civil con un arma falsa: 225 € 
                
            <li id="art-2-12" class="flex items-center py-2" data-sancion="300 €"> Art. 2.12 - Intimidación a un civil con un arma falsa: 300 € 
                
            <li id="art-2-13" class="flex items-center py-2" data-sancion="500 €"> Art. 2.13 - Asalto a un funcionario del estado con un arma falsa: 500 € 
                
            <li id="art-2-14" class="flex items-center py-2" data-sancion="600 €"> Art. 2.14 - Intimidación a un funcionario del estado con un arma falsa: 600 € 
                
            <li id="art-2-15" class="flex items-center py-2" data-sancion="1500 €"> Art. 2.15 - Asalto a una propiedad publica: 1500 € 
                
            <li id="art-2-16" class="flex items-center py-2" data-sancion="2250 €"> Art. 2.16 - Asalto a una propiedad publica a mano armada: 2250 € 
                
            <li id="art-2-17" class="flex items-center py-2" data-sancion="1800 €"> Art. 2.17 - Asalto a una propiedad privada: 1800 € 
                
            <li id="art-2-18" class="flex items-center py-2" data-sancion="2500 €"> Art. 2.18 - Asalto a una propiedad privada a mano armada: 2500 € 
                
            <li id="art-2-19" class="flex items-center py-2" data-sancion="4500 €"> Art. 2.19 - Robo a una tienda de herramienta: 4500 € 
                
            <li id="art-2-20" class="flex items-center py-2" data-sancion="2250 €"> Art. 2.20 - Robo a una gasolinera: 2250 € 
                
            <li id="art-2-21" class="flex items-center py-2" data-sancion="1900 €"> Art. 2.21 - Robo a una empresa: 1900 € 
                
            <li id="art-2-22" class="flex items-center py-2" data-sancion="1250 €"> Art. 2.22 - Robo a un ATM: 1250 €
                
            <li id="art-2-23" class="flex items-center py-2" data-sancion="1600 €"> Art. 2.23 - Robo al taller de coches: 1600 € 
                
            <li id="art-2-24" class="flex items-center py-2" data-sancion="1900 €"> Art. 2.24 - Robo a un restaurante de comida rápida: 1900 € 
                
            <li id="art-2-25" class="flex items-center py-2" data-sancion="10000 €"> Art. 2.25 - Robo a un furgón bancario: 10000 € 
                
            <li id="art-2-26" class="flex items-center py-2" data-sancion="9500 €"> Art. 2.26 - Robo a una joyería: 9500 € 
                
            <li id="art-2-27" class="flex items-center py-2" data-sancion="27000 €"> Art. 2.27 - Robo a una sucursal bancaria: 27000 € 
                
            <li id="art-2-28" class="flex items-center py-2" data-sancion="1000 €"> Art. 2.28 - Robo a un furgón de comida: 1000 € 
                
            <li id="art-2-29" class="flex items-center py-2" data-sancion="700 €"> Art. 2.29 - Apropiarse de pertenencias ajenas legales encontradas en la vía publica: 700 € 
                
            <li id="art-2-30" class="flex items-center py-2" data-sancion="1450 €"> Art. 2.30 - Apropiarse de  pertenencias ajenas ilegales encontradas en la vía publica: 1450 € 
                
            <li id="art-2-31" class="flex items-center py-2" data-sancion="7000 - 25000€ (Dependiendo del vehículo robado)"> Art. 2.31 - Robo de un vehículo civil: 7000 - 25000€ (Dependiendo del vehículo robado) 
                
            <li id="art-2-32" class="flex items-center py-2" data-sancion="20500 €"> Art. 2.32 - Robo de un vehículo médico: 20500 € 
                
            <li id="art-2-33" class="flex items-center py-2" data-sancion="25750 €"> Art. 2.33 - Robo de un vehículo de  bomberos: 25750 € 
                
            <li id="art-2-34" class="flex items-center py-2" data-sancion="30500€"> Art. 2.34 - Robo de un vehículo policial: 30500€ 
                
            <li id="art-2-35" class="flex items-center py-2" data-sancion="50000 €"> Art. 2.35 - Robo de un vehículo presidencial: 50000 € 
                
            <li id="art-2-36" class="flex items-center py-2" data-sancion="7500 €"> Art. 2.36 - Robo de un vehículo de transporte público: 7500 €
                
            <li id="art-2-37" class="flex items-center py-2" data-sancion="8500 €"> Art. 2.37 - Robo de un vehículo de  transporte privado: 8500 €
                
            <li id="art-2-38" class="flex items-center py-2" data-sancion="1850 €"> Art. 2.38 - Allanamiento de morada: 1850 € 
                
            <li id="art-2-39" class="flex items-center py-2" data-sancion="100000 € + Solicitar Juicio"> Art. 2.39 - Robo de material radiactivo: 100000 € + Solicitar Juicio 
                
            <li id="art-2-40" class="flex items-center py-2" data-sancion="32500 €"> Art. 2.40 - Robo en edificio estatal: 32500 € 
                
            <li id="art-2-41" class="flex items-center py-2" data-sancion="11500 €"> Art. 2.41 - Robo de información confidencial: 11500 € 
                
            <li id="art-2-42" class="flex items-center py-2" data-sancion="5000 €"> Art. 2.42 - Robo de evidencias: 5000 € 
                
            <li id="art-2-43" class="flex items-center py-2" data-sancion="1150 €"> Art. 2.43 - Robo de utensilios policiales: 1150 € 
                
            <li id="art-2-44" class="flex items-center py-2" data-sancion="750 €"> Art. 2.44 - Robo de material médico: 750 € 
                
            <li id="art-2-45" class="flex items-center py-2" data-sancion="850 €"> Art. 2.45 - Robo de material público: 850 € 



                
            <li id="art-3-1" class="flex items-center py-2" data-sancion="100 €"> Art. 3.1 - Intento de agresión: 100 €
                
            <li id="art-3-2" class="flex items-center py-2" data-sancion="250 €"> Art. 3.2 - Agresión a un civil: 250 €
                
            <li id="art-3-3" class="flex items-center py-2" data-sancion="350 €"> Art. 3.3 - Agresión a un bombero: 350 € 
                
            <li id="art-3-4" class="flex items-center py-2" data-sancion="350 €"> Art. 3.4 - Agresión a un médico: 350 €
                
            <li id="art-3-5" class="flex items-center py-2" data-sancion="900 €"> Art. 3.5 - Agresión a un policía: 900 € 
                
            <li id="art-3-6" class="flex items-center py-2" data-sancion="1100 €"> Art. 3.6 - Agresión a un fiscal: 1100 € 
                
            <li id="art-3-7" class="flex items-center py-2" data-sancion="175 €"> Art. 3.7 - Agresión a un abogado: 175 € 
                
            <li id="art-3-8" class="flex items-center py-2" data-sancion="1250 €"> Art. 3.8 - Agresión a un juez: 1250 €   
                
            <li id="art-3-9" class="flex items-center py-2" data-sancion="375 €"> Art. 3.9 - Alteración del orden publico: 375 € 
                
            <li id="art-3-10" class="flex items-center py-2" data-sancion="100€"> Art. 3.10 - Racismo: 100€ 
                
            <li id="art-3-11" class="flex items-center py-2" data-sancion="100 €"> Art. 3.11 - Homofobia: 100 € 
                
            <li id="art-3-12" class="flex items-center py-2" data-sancion="250 €"> Art. 3.12 - Acoso: 250 € 
                
            <li id="art-3-13" class="flex items-center py-2" data-sancion="275 €"> Art. 3.13 - Acoso inmobiliario: 275 €
                
            <li id="art-3-14" class="flex items-center py-2" data-sancion="325 €"> Art. 3.14 - Acoso laboral: 325 €
               
            <li id="art-3-15" class="flex items-center py-2" data-sancion="650€"> Art. 3.15 - Acoso escolar: 650€
            
            <li id="art-3-16" class="flex items-center py-2" data-sancion="450 €"> Art. 3.16 - Acoso psicológico: 450 €
             
            <li id="art-3-17" class="flex items-center py-2" data-sancion="1250 €"> Art. 3.17 - Acoso mediante coacción: 1250 € 
                
            <li id="art-3-18" class="flex items-center py-2" data-sancion="900 €"> Art. 3.18 - Acoso cibernético: 900 € 
                
            <li id="art-3-19" class="flex items-center py-2" data-sancion="1275 €"> Art. 3.19 - Acoso sexual: 1275 €
                
            <li id="art-3-20" class="flex items-center py-2" data-sancion="2700 €"> Art. 3.20 - Intento de violación: 2700 € 
                
            <li id="art-3-21" class="flex items-center py-2" data-sancion="2500 €"> Art. 3.21 - Abuso sexual: 2500 €

            <li id="art-3-22" class="flex items-center py-2" data-sancion="17000 €"> Art. 3.22 - Violación: 17000 €
                
            <li id="art-3-23" class="flex items-center py-2" data-sancion="3000 €"> Art. 3.23 - Suplantación de identidad: 3000 € 
                
            <li id="art-3-24" class="flex items-center py-2" data-sancion="12500 €"> Art. 3.24 - Suplantación de identidad para inculpar a un civil: 12500 € 
                
            <li id="art-3-25" class="flex items-center py-2" data-sancion="10500 € (por cada persona)"> Art. 3.25 - Tráfico de personas: 10500 € (por cada persona) 
                
            <li id="art-3-26" class="flex items-center py-2" data-sancion="12500 € (por cada persona)"> Art. 3.26 -  Tráfico de menores: 12500 € (por cada persona) 
                
            <li id="art-3-27" class="flex items-center py-2" data-sancion="475 €"> Art. 3.27 - Maltrato: 475 € 
                
            <li id="art-3-28" class="flex items-center py-2" data-sancion="450 €"> Art. 3.28 - Maltrato animal: 450 €
                
            <li id="art-3-29" class="flex items-center py-2" data-sancion="125 €"> Art. 3.29 - Maltrato psicológico: 125 € 
                
            <li id="art-3-30" class="flex items-center py-2" data-sancion="1350 €"> Art. 3.30 - Violencia de género: 1350 € 
                
            <li id="art-3-31" class="flex items-center py-2" data-sancion="2550 €"> Art. 3.31 - Intento de agresión a un menor de edad: 2550 € 
                
            <li id="art-3-32" class="flex items-center py-2" data-sancion="3050 €"> Art. 3.32 - Agresión a un menor de edad: 3050 € 
                
            <li id="art-3-33" class="flex items-center py-2" data-sancion="20000 €"> Art. 3.33 - Intento de violación a un menor de edad: 20000 € 
                
            <li id="art-3-34" class="flex items-center py-2" data-sancion="25000 €"> Art. 3.34 - Violación a un menor de edad: 25000 € 
                
            <li id="art-3-35" class="flex items-center py-2" data-sancion="2100 €"> Art. 3.35 - Abuso a un menor de edad: 2100 €
                
            <li id="art-3-36" class="flex items-center py-2" data-sancion="1950 €"> Art. 3.36 - Prostitución la vía publica: 1950 €
                
            <li id="art-3-37" class="flex items-center py-2" data-sancion="9925 € + Cierre del local."> Art. 3.37 - Prostitución locales que no están diseñados para esa actividad: 9925 € + Cierre del local. 
                
            <li id="art-3-38" class="flex items-center py-2" data-sancion="400-2500 € (Dependiendo de la gravedad)"> Art. 3.38 - Disturbios en la vía publica: 400-2500 € (Dependiendo de la gravedad) 
                
            <li id="art-3-39" class="flex items-center py-2" data-sancion="800 - 4250€ (Dependiendo de la gravedad)"> Art. 3.39 - Disturbios en una propiedad privada: 800 - 4250€ (Dependiendo de la gravedad) 
                
            <li id="art-3-40" class="flex items-center py-2" data-sancion="570 € + Incautar lo vendido."> Art. 3.40 - Comercialización ilegal: 570 € + Incautar lo vendido.
                
            <li id="art-3-41" class="flex items-center py-2" data-sancion="1500 €"> Art. 3.41 - Intentar convencer a alguien para que haga un delito: 1500 € 
                
            <li id="art-3-42" class="flex items-center py-2" data-sancion="2000 €"> Art. 3.42 - Convencer a alguien para que haga un delito: 2000 €
                
            <li id="art-3-43" class="flex items-center py-2" data-sancion="175 €"> Art. 3.43 - Conducta violenta: 175 €
                
            <li id="art-3-44" class="flex items-center py-2" data-sancion="Solicitar Juicio."> Art. 3.44 - Crear una banda u organización ilegal peligrosa: Solicitar Juicio. 
                
            <li id="art-3-45" class="flex items-center py-2" data-sancion="17500 €"> Art. 3.45 - Reclutar a civiles a una banda u organización ilegal: 17500 € 
                
            <li id="art-3-46" class="flex items-center py-2" data-sancion="85000 € + Solicitar Juicio."> Art. 3.46 - Pertenecer a una banda u organización ilegal peligrosa: 85000 € + Solicitar Juicio. 
                
            <li id="art-3-47" class="flex items-center py-2" data-sancion="375 €"> Art. 3.47 - Realizar una manifestación ilegal: 375 € 
                
            <li id="art-3-48" class="flex items-center py-2" data-sancion="300 €"> Art. 3.48 - Participar en una manifestación ilegal: 300 € 
                
            <li id="art-3-49" class="flex items-center py-2" data-sancion="450 €"> Art. 3.49 - Ir desnudo por la vía publica: 450 € 
                
            <li id="art-3-50" class="flex items-center py-2" data-sancion="575 €"> Art. 3.50 - Exhibicionismo desde una propiedad privada: 575 € 
                
            <li id="art-3-51" class="flex items-center py-2" data-sancion="625 €"> Art. 3.51 - Ir enmascarado sin motivo: 625 € 
                
            <li id="art-3-52" class="flex items-center py-2" data-sancion="1000 €"> Art. 3.52 - Ir enmascarado para evitar reconocimiento y realizar actividades ilícitas: 1000 € 
                
            <li id="art-3-53" class="flex items-center py-2" data-sancion="1750 €"> Art. 3.53 - Suplantación de identidad de un funcionario público: 1750 € 
                
            <li id="art-3-54" class="flex items-center py-2" data-sancion="5500 €"> Art. 3.54 - Suplantación de identidad de un policía : 5500 € 
                
            <li id="art-3-55" class="flex items-center py-2" data-sancion="125€"> Art. 3.55 - Insulto hacía un funcionario público: 125€ 
                
            <li id="art-3-56" class="flex items-center py-2" data-sancion="170€"> Art. 3.56 - Uso de una aeronave no tripulada sin licencia: 170€ 
                
            <li id="art-3-57" class="flex items-center py-2" data-sancion="350€ + Retirada de la Licencia."> Art. 3.57 - Obstruir el trafico aéreo con una aeronave no tripulada: 350€ + Retirada de la Licencia. 
                
            <li id="art-3-58" class="flex items-center py-2" data-sancion="650€ + Retirada de la Licencia."> Art. 3.58 - Volar una aeronave no tripulada por zonas restringidas/privadas: 650€ + Retirada de la Licencia.
                
            <li id="art-3-59" class="flex items-center py-2" data-sancion="950€ +  Retirada de la Licencia."> Art. 3.59 - Alterar el orden en una detención con una aeronave no tripulada: 950€ + Retirada de la Licencia.
                
            <li id="art-3-60" class="flex items-center py-2" data-sancion="525€ +  Retirada de la Licencia."> Art. 3.60 - Utilizar una aeronave no tripulada con fines ilícitos: 525€ + Retirada de la Licencia. 
                
            <li id="art-3-61" class="flex items-center py-2" data-sancion="450€"> Art. 3.61 - Contaminar o degradar zonas naturales: 450€ 
                
            <li id="art-3-62" class="flex items-center py-2" data-sancion="400€ | 1.000€ de ser reincidente."> Art. 3.62 - Entrar en zonas restringidas: 400€ | 1.000€ de ser reincidente. 
                
            <li id="art-3-63" class="flex items-center py-2" data-sancion="2700-8500€ (Dependiendo de los efectivos y recursos empleados)"> Art. 3.63 - Accionar una alarma de incendios sin ser una emergencia real: 2700-8500€ (Dependiendo de los efectivos y recursos empleados) 
                
            <li id="art-3-64" class="flex items-center py-2" data-sancion="675€ + retirada del arma."> Art. 3.64 - Exhibir un arma de fuego en publico: 675€ + retirada del arma. 
                
            <li id="art-3-65" class="flex items-center py-2" data-sancion="650€"> Art. 3.65 - Portar un chaleco antibalas sin pertenecer a las FCSE o medios de comunicación (Telecinco): 650€ 



                
            <li id="art-4-1" class="flex items-center py-2" data-sancion="1000€"> Art. 4.1 - Posesión de arma ilegal: 1000€ 
                
            <li id="art-4-2" class="flex items-center py-2" data-sancion="1500 €"> Art. 4.2 - Posesión de arma corta sin licencia: 1500 € 
                
            <li id="art-4-3" class="flex items-center py-2" data-sancion="2250 €"> Art. 4.3 - Posesión de armas larga: 2250 € 
                
            <li id="art-4-4" class="flex items-center py-2" data-sancion="2500 €"> Art. 4.4 - Posesión de armas "caseras/especiales": 2500 € 
                
            <li id="art-4-5" class="flex items-center py-2" data-sancion="2000 €"> Art. 4.5 - Uso indebido de armas cortas sin licencia: 2000 € 
                
            <li id="art-4-6" class="flex items-center py-2" data-sancion="2250€"> Art. 4.6 - Uso indebido de arma corta ilegal: 2250€ 
                
            <li id="art-4-7" class="flex items-center py-2" data-sancion="3250 €"> Art. 4.7 - Uso indebido de armas largas: 3250 €
                
            <li id="art-4-8" class="flex items-center py-2" data-sancion="3500 €"> Art. 4.8 - Uso indebido de armas "caseras/especiales": 3500 € 
                
            <li id="art-4-9" class="flex items-center py-2" data-sancion="4500 €"> Art. 4.9 - Posesión de armas cortas con intención de realizar contrabando: 4500 € 
                
            <li id="art-4-10" class="flex items-center py-2" data-sancion="9750 €"> Art. 4.10 - Posesión de armas largas con intención de realizar contrabando: 9750 €
                
            <li id="art-4-11" class="flex items-center py-2" data-sancion="12000 €"> Art. 4.11 - Posesión de armas "caseras/especiales" con intención de contrabando: 12000 € 
                
            <li id="art-4-12" class="flex items-center py-2" data-sancion="2200 € + Retirada de la licencia."> Art. 4.12 - Uso indebido de armas cortas con licencia: 2200 € + Retirada de la licencia. 
                
            <li id="art-4-13" class="flex items-center py-2" data-sancion="2750€"> Art. 4.13 - Iniciar un tiroteo con un arma corta: 2750€ 

            <li id="art-4-13" class="flex items-center py-2" data-sancion="3250€"> Art. 4.14 - Iniciar un tiroteo con un arma corta ilegal: 3250€ 

            <li id="art-4-15" class="flex items-center py-2" data-sancion="4100 €"> Art. 4.15 - Iniciar un tiroteo con un arma larga: 4100 € 
                
            <li id="art-4-16" class="flex items-center py-2" data-sancion="4300 €"> Art. 4.16 - Iniciar un tiroteo con un arma "casera/especial": 4300 € 
                
            <li id="art-4-17" class="flex items-center py-2" data-sancion="2300 €"> Art. 4.17 - Iniciar un tiroteo con un arma corta sin licencia: 2300 € 
                
            <li id="art-4-18" class="flex items-center py-2" data-sancion="2450 €"> Art. 4.18 - Iniciar un tiroteo con  un arma corta con licencia: 2450 € 
                
            <li id="art-4-19" class="flex items-center py-2" data-sancion="15750 €"> Art. 4.19 - Venta ilícita de armas: 15750 € 
                
            <li id="art-4-20" class="flex items-center py-2" data-sancion="2570 €"> Art. 4.20 - Compra de armas ilegales: 2570 € 
                
            <li id="art-4-21" class="flex items-center py-2" data-sancion="1250 €"> Art. 4.21 - Provocar disturbios con arma de fuego: 1250 € 

            <li id="art-4-22" class="flex items-center py-2" data-sancion="875 €"> Art. 4.22 - Provocar disturbios con arma blanca: 875 € 
                
            <li id="art-4-23" class="flex items-center py-2" data-sancion="500 €"> Art. 4.23 - Posesión de arma blanca: 500 € 
                
            <li id="art-4-24" class="flex items-center py-2" data-sancion="825 €"> Art. 4.24 - Intento de agresión con arma blanca: 825 € 
                
            <li id="art-4-25" class="flex items-center py-2" data-sancion="950 €"> Art. 4.25 - Agresión con arma blanca: 950 €
                
            <li id="art-4-26" class="flex items-center py-2" data-sancion="2000 € X Kg"> Art. 4.26 - Posesión de estupefacientes: 2000 € X Kg 
                
            <li id="art-4-27" class="flex items-center py-2" data-sancion="350 €"> Art. 4.27 - Consumo de bebidas alcohólicas en la vía publica: 350 € 
                
            <li id="art-4-28" class="flex items-center py-2" data-sancion="1150 €"> Art. 4.28 - Consumo de estupefaciente en la vía publica: 1150 € 
                
            <li id="art-4-29" class="flex items-center py-2" data-sancion="5700€"> Art. 4.29 - Posesión de sustancias ilícitas con intención de contrabando: 5700€ 
                
            <li id="art-4-30" class="flex items-center py-2" data-sancion="750 €"> Art. 4.30 - Venta de alcohol a menores: 750 € 
                
            <li id="art-4-31" class="flex items-center py-2" data-sancion="1075 €"> Art. 4.31 - Venta de estupefacientes a menores: 1075 €
                
            <li id="art-4-32" class="flex items-center py-2" data-sancion="7500 € X Kg"> Art. 4.32 - Tráfico de drogas: 7500 € X Kg 
                
            <li id="art-4-33" class="flex items-center py-2" data-sancion="1000 €"> Art. 4.33 - Ir bajo los efectos de estupefacientes en vía pública: 1000 € 

            <li id="art-4-34" class="flex items-center py-2" data-sancion="720 €"> Art. 4.34 - Portar una caja de munición: 720 € 



                
            <li id="art-5-1" class="flex items-center py-2" data-sancion="1100 €"> Art. 5.1 - Intento de homicidio sin armas a un civil: 1100 € 

            <li id="art-5-2" class="flex items-center py-2" data-sancion="1500 €"> Art. 5.2 - Intento de homicidio con arma blanca a un civil: 1500 € 
                
            <li id="art-5-3" class="flex items-center py-2" data-sancion="1850 €"> Art. 5.3 - Intento de homicidio con arma corta a un civil: 1850 € 
                
            <li id="art-5-4" class="flex items-center py-2" data-sancion="2150 €"> Art. 5.4 - Intento de homicidio con arma larga a un civil: 2150 € 
                
            <li id="art-5-5" class="flex items-center py-2" data-sancion="2250 €"> Art. 5.5 - Intento de homicidio con arma "casera/especial" a un civil: 2250 € 
                
            <li id="art-5-6" class="flex items-center py-2" data-sancion="1600 €"> Art. 5.6 - Intento de homicidio sin armas a un funcionario: 1600 € 
                
            <li id="art-5-7" class="flex items-center py-2" data-sancion="1750 €"> Art. 5.7 - Intento de homicidio con arma blanca a un funcionario: 1750 € 
                
            <li id="art-5-8" class="flex items-center py-2" data-sancion="1900 €"> Art. 5.8 - Intento de homicidio con arma corta a un funcionario: 1900 € 
                
            <li id="art-5-9" class="flex items-center py-2" data-sancion="2000 €"> Art. 5.9 - Intento de homicidio con arma larga a un funcionario: 2000 € 
                
            <li id="art-5-10" class="flex items-center py-2" data-sancion="2100 €"> Art. 5.10 - Intento de homicidio con arma "casera/especial" a un funcionario: 2100 € 
                
            <li id="art-5-11" class="flex items-center py-2" data-sancion="1500 €"> Art. 5.11 - Homicidio sin armas a un civil: 1500 € 
                
            <li id="art-5-12" class="flex items-center py-2" data-sancion="1850 €"> Art. 5.12 - Homicidio con arma blanca a un civil: 1850 € 
                
            <li id="art-5-13" class="flex items-center py-2" data-sancion="2100 €"> Art. 5.13 - Homicidio con arma corta a un civil: 2100 € 
                
            <li id="art-5-14" class="flex items-center py-2" data-sancion="2350 €"> Art. 5.14 - Homicidio con arma larga a un civil: 2350 €
                
            <li id="art-5-15" class="flex items-center py-2" data-sancion="2500 €"> Art. 5.15 - Homicidio con arma "casera/especial" a un civil: 2500 € 
                
            <li id="art-5-16" class="flex items-center py-2" data-sancion="1750 €"> Art. 5.16 - Homicidio sin armas a un funcionario: 1750 € 
                
            <li id="art-5-17" class="flex items-center py-2" data-sancion="2000 €"> Art. 5.17 - Homicidio con arma blanca a un funcionario: 2000 € 
                
            <li id="art-5-18" class="flex items-center py-2" data-sancion="2250 €"> Art. 5.18 - Homicidio con arma corta a un funcionario: 2250 € 
                
            <li id="art-5-19" class="flex items-center py-2" data-sancion="2750 €"> Art. 5.19 - Homicidio con arma larga a un funcionario: 2750 € 
                
            <li id="art-5-20" class="flex items-center py-2" data-sancion="3000 €"> Art. 5.20 - Homicidio con arma "casera/especial" a un funcionario: 3000 € 
                
            <li id="art-5-21" class="flex items-center py-2" data-sancion="500 €"> Art. 5.21 - Intento de homicidio a un animal sin arma: 500 €
                
            <li id="art-5-22" class="flex items-center py-2" data-sancion="750 €"> Art. 5.22 - Intento de homicidio a un  animal con arma blanca: 750 € 
                
            <li id="art-5-23" class="flex items-center py-2" data-sancion="900 €"> Art. 5.23 - Homicidio a un animal sin arma: 900 € 
                
            <li id="art-5-24" class="flex items-center py-2" data-sancion="1000 €"> Art. 5.24 - Intento de homicidio a un animal con arma de fuego: 1000 € 
                
            <li id="art-5-25" class="flex items-center py-2" data-sancion="1150 €"> Art. 5.25 - Intento de secuestro a  un civil: 1150 € 
                
            <li id="art-5-26" class="flex items-center py-2" data-sancion="1750€"> Art. 5.26 - Intento de secuestro a un menor: 1750€
                
            <li id="art-5-27" class="flex items-center py-2" data-sancion="1250 €"> Art. 5.27 - Intento de secuestro a un funcionario: 1250 €
                
            <li id="art-5-28" class="flex items-center py-2" data-sancion="1500 €"> Art. 5.28 - Secuestro a un civil: 1500 € 
                
            <li id="art-5-29" class="flex items-center py-2" data-sancion="2500 €"> Art. 5.29 - Secuestro a un menor: 2500 € 
                
            <li id="art-5-30" class="flex items-center py-2" data-sancion="2000 €"> Art. 5.30 - Secuestro a un funcionario: 2000 € 
                
            <li id="art-5-31" class="flex items-center py-2" data-sancion="3500 €"> Art. 5.31 - Realizar un secuestro para coaccionar a un tercero: 3500 € 
                
            <li id="art-5-32" class="flex items-center py-2" data-sancion="1000 €"> Art. 5.32 - Realizar un secuestro con la intención de robar: 1000 € 
                
            <li id="art-5-33" class="flex items-center py-2" data-sancion="3000 €"> Art. 5.33 - Amenaza realizada pidiendo una cantidad o poniendo condiciones: 3000 € 
                
            <li id="art-5-34" class="flex items-center py-2" data-sancion="600 €"> Art. 5.34 - Amenaza realizada de manera no condicional: 600 € 
                
            <li id="art-5-35" class="flex items-center py-2" data-sancion="100 €"> Art. 5.35 - Amenazar con un mal que no constituya peligro: 100 € 
                
            <li id="art-5-36" class="flex items-center py-2" data-sancion="1000 €"> Art. 5.36 - Extorsión a una persona: 1000 € 
                
            <li id="art-5-37" class="flex items-center py-2" data-sancion="3200 €"> Art. 5.37 - Extorsión a un negocio: 3200 € 
                
            <li id="art-5-38" class="flex items-center py-2" data-sancion="2900 €"> Art. 5.38 - Extorsión a un funcionario: 2900 € 
                
            <li id="art-5-39" class="flex items-center py-2" data-sancion="18500 €"> Art. 5.39 - Extorsión a un juez: 18500 € 
                
            <li id="art-5-40" class="flex items-center py-2" data-sancion="1500 €"> Art. 5.40 - Extorsión a un detenido: 1500 € 
                
            <li id="art-5-41" class="flex items-center py-2" data-sancion="500-2750€ (Dependiendo de la situación)"> Art. 5.41 - Falso testimonio: 500-2750€ (Dependiendo de la situación) 


                

                
            <li id="art-6-1" class="flex items-center py-2" data-sancion="50 €"> Art. 6.1 - No llevar licencia de arma teniendo el arma: 50 € 
                
            <li id="art-6-2" class="flex items-center py-2" data-sancion="75 €"> Art. 6.2 - No llevar el carnet de conducir estando conduciendo: 75 € 
                
            <li id="art-6-3" class="flex items-center py-2" data-sancion="350€"> Art. 6.3 - No llevar documentación que permita identificarte en alerta roja: 350€ 
                
            <li id="art-6-4" class="flex items-center py-2" data-sancion="Incautación del Vehículo."> Art. 6.4 - No llevar la documentación del coche en el coche: Incautación del Vehículo. 
                
            <li id="art-6-5" class="flex items-center py-2" data-sancion="600 €"> Art. 6.5 - Negarse a identificarse: 600 € 
                
            <li id="art-6-6" class="flex items-center py-2" data-sancion="Auditoria con Fiscal y Fronteras."> Art. 6.6 - No llevar la documentación en regla/no tener documentación: Auditoria con Fiscal y Fronteras. 
                
            <li id="art-6-7" class="flex items-center py-2" data-sancion="12000 €"> Art. 6.7 - Falsificar un documento: 12000 €
                
            <li id="art-6-8" class="flex items-center py-2" data-sancion="1950 €"> Art. 6.8 - Posesión de un documento falso: 1950 € 
                
            <li id="art-6-9" class="flex items-center py-2" data-sancion="1900 €"> Art. 6.9 - Falsificar una licencia: 1900 € 
                
            <li id="art-6-10" class="flex items-center py-2" data-sancion="1750 €"> Art. 6.10 - Posesión de una licencia falsificada: 1750 € 
                
            <li id="art-6-11" class="flex items-center py-2" data-sancion="600 €"> Art. 6.11 - Pescar en lugares no autorizados para esa actividad: 600 € 
                
            <li id="art-6-12" class="flex items-center py-2" data-sancion="7500 €"> Art. 6.12 - Hacer uso de artefactos explosivos sin permiso o licencia: 7500 € 
                
            <li id="art-6-13" class="flex items-center py-2" data-sancion="3500 €"> Art. 6.13 - Intento de soborno a un  funcionario: 3500 € 
                
            <li id="art-6-14" class="flex items-center py-2" data-sancion="8500 €"> Art. 6.14 - Sobornar a un funcionario: 8500 € 
                
            <li id="art-6-15" class="flex items-center py-2" data-sancion="1600 €"> Art. 6.15 - Realizar una llamada falsa: 1600 €
                
            <li id="art-6-16" class="flex items-center py-2" data-sancion="19000 €"> Art. 6.16 - Realizar un falso reporte de bomba: 19000 € 
                
            <li id="art-6-17" class="flex items-center py-2" data-sancion="28000 €"> Art. 6.17 - Reportar un falso atentado terrorista: 28000 € 
                
            <li id="art-6-18" class="flex items-center py-2" data-sancion="550 €"> Art. 6.18 - Desobediencia a la justicia: 550 € 
                
            <li id="art-6-19" class="flex items-center py-2" data-sancion="500 €"> Art. 6.19 - Desacato a la autoridad: 500 € 
                
            <li id="art-6-20" class="flex items-center py-2" data-sancion="1000 €"> Art. 6.20 - Uso indebido de la línea de emergencias: 1000 € 
                
            <li id="art-6-21" class="flex items-center py-2" data-sancion="825 €"> Art. 6.21 - Resistirse al arresto: 825 € 
                
            <li id="art-6-22" class="flex items-center py-2" data-sancion="1250 €"> Art. 6.22 - Huir de la justicia: 1250 € 
                
            <li id="art-6-23" class="flex items-center py-2" data-sancion="100000 € + Solicitar Juicio."> Art. 6.23 - Terrorismo: 100000 € + Solicitar Juicio. 
                
            <li id="art-6-24" class="flex items-center py-2" data-sancion="25000 €"> Art. 6.24 - Provocar un incendio: 25000 €
                
            <li id="art-6-25" class="flex items-center py-2" data-sancion="2250 €"> Art. 6.25 - Suplantación de identidad cibernética: 2250 € 
                
            <li id="art-6-26" class="flex items-center py-2" data-sancion="1570 €"> Art. 6.26 - Doxeo: 1570 € 
                
            <li id="art-6-27" class="flex items-center py-2" data-sancion="1350 €"> Art. 6.27 - Violación de la privacidad: 1350 €
                
            <li id="art-6-28" class="flex items-center py-2" data-sancion="2700 €"> Art. 6.28 - Estafa cibernética: 2700 €
                
            <li id="art-6-29" class="flex items-center py-2" data-sancion="6250 €"> Art. 6.29 - Fraude bancario: 6250 €
                
            <li id="art-6-30" class="flex items-center py-2" data-sancion="9400 €"> Art. 6.30 - Hackear instituciones estatales: 9400 € 
                
            <li id="art-6-31" class="flex items-center py-2" data-sancion="1200 €"> Art. 6.31 - Manipular las luces de la ciudad: 1200 € 
                
            <li id="art-6-32" class="flex items-center py-2" data-sancion="1500 €"> Art. 6.32 - Manipular señales de radio o conección: 1500 € 
                
            <li id="art-6-33" class="flex items-center py-2" data-sancion="1900 €"> Art. 6.33 - Realizar ataques de denegación de servicio: 1900 € 
                
            <li id="art-6-34" class="flex items-center py-2" data-sancion="1550 €"> Art. 6.34 - Hackear un dispositivo móvil para localizarlo: 1550 € 
                
            <li id="art-6-35" class="flex items-center py-2" data-sancion="19000 €"> Art. 6.35 - Destruir información confidencial de la red: 19000 € 
                
            <li id="art-6-36" class="flex items-center py-2" data-sancion="1800 €"> Art. 6.36 - Manipular los sistemas de seguridad de un local: 1800 € 
                
            <li id="art-6-37" class="flex items-center py-2" data-sancion="2200 €"> Art. 6.37 - Manipular los sistemas de seguridad de un lugar público: 2200 € 
                
            <li id="art-6-38" class="flex items-center py-2" data-sancion="32.000€ (Menos de 20K blanqueados)   74.500€ (Menos de 50K blanqueados)   97.300€ (Menos de 100K blanqueados)   145.600€ (Mas de 100K blanqueados)"> Art. 6.38 - Blanqueo de capitales: 32.000€ (Menos de 20K blanqueados) 74.500€ (Menos de 50K blanqueados) 97.300€ (Menos de 100K blanqueados) 145.600€ (Mas de 100K blanqueados)
                
            <li id="art-6-39" class="flex items-center py-2" data-sancion="Pagar el importe que se evadió + 25.000€"> Art. 6.39 - Evasión de impuestos: Pagar el importe que se evadió + 25.000€ 
                
            <li id="art-6-40" class="flex items-center py-2" data-sancion="Dinero intervenido + 600€"> Art. 6.40 - Portar mas de 100.000€ en efectivo en vía publica: Dinero intervenido + 800€ 



                
                
            <li id="art-7-1" class="flex items-center py-2" data-sancion="15000 €"> Art. 7.1 - Corrupción: 15000 €
              
            <li id="art-7-2" class="flex items-center py-2" data-sancion="7500 €"> Art. 7.2 - Dictar una sentencia opuesta a la real a propósito: 7500 € 
                
            <li id="art-7-3" class="flex items-center py-2" data-sancion="750-18000€ (Dependiendo del tipo de abuso)"> Art. 7.3 - Abuso de poder: 750-18000€ (Dependiendo del tipo de abuso) 
                
            <li id="art-7-4" class="flex items-center py-2" data-sancion="900-1200€ (Dependiendo del tipo de abuso)"> Art. 7.4 - Abuso policial: 900-1200€ (Dependiendo del tipo de abuso) 
                
            <li id="art-7-5" class="flex items-center py-2" data-sancion="1500 €"> Art. 7.5 - Omitir una señal de socorro: 1500 € 
                    
            <li id="art-7-6" class="flex items-center py-2" data-sancion="2350 €"> Art. 7.6 - Ignorar delitos de terceros no mencionados en el capítulo 1: 2350 € 
                
            <li id="art-7-7" class="flex items-center py-2" data-sancion="14000 €"> Art. 7.7 - Acusar a un civil con la intención de inculparlo cuando no ha hecho nada: 14000 € 
                
            <li id="art-7-8" class="flex items-center py-2" data-sancion="18000 €"> Art. 7.8 - Encubrir a un criminal: 18000 €                

            <li id="art-7-9" class="flex items-center py-2" data-sancion="700 €"> Art. 7.9 - No acudir a una llamada sin un motivo: 700 € 
                
            <li id="art-7-10" class="flex items-center py-2" data-sancion="2500 €"> Art. 7.10 - No acudir a una llamada de QRR sin motivo: 2500 € 
                
            <li id="art-7-11" class="flex items-center py-2" data-sancion="1865 €"> Art. 7.11 - No asistir a un código 0 sin motivo: 1865 € 
                
            <li id="art-7-12" class="flex items-center py-2" data-sancion="250 €"> Art. 7.12 - Desobedecer una orden directa de un superior: 250 € 

            <li id="art-7-13" class="flex items-center py-2" data-sancion="5000 €"> Art. 7.13 - Filtrar información confidencial: 5000 € 

            <li id="art-7-14" class="flex items-center py-2" data-sancion="10000 €"> Art. 7.14 - Robar documentos estatales: 10000 € 
                
            <li id="art-7-15" class="flex items-center py-2" data-sancion="950 €"> Art. 7.15 - Revelar datos personales: 950 € 
                
            <li id="art-7-16" class="flex items-center py-2" data-sancion="9000 €"> Art. 7.16 - Revelar datos de una operación: 9000 € 
                
            <li id="art-7-17" class="flex items-center py-2" data-sancion="Solicitar Juicio."> Art. 7.17 - Revelar secretos del estado: Solicitar Juicio. 
                
            <li id="art-7-18" class="flex items-center py-2" data-sancion="5000 €"> Art. 7.18 - Aceptar un soborno comprendido entre 0-10k: 5000 € 
                
            <li id="art-7-19" class="flex items-center py-2" data-sancion="10000 €"> Art. 7.19 - Aceptar un soborno comprendido entre 11k-20k: 10000 € 
                
            <li id="art-7-20" class="flex items-center py-2" data-sancion="15000 €"> Art. 7.20 - Aceptar un soborno comprendido entre 21k-30k: 15000 € 
                
            <li id="art-7-21" class="flex items-center py-2" data-sancion="20000 €"> Art. 7.21 - Aceptar un soborno comprendido entre 31k-40k: 20000 € 
                
            <li id="art-7-22" class="flex items-center py-2" data-sancion="25000 €"> Art. 7.22 - Aceptar un soborno comprendido entre 41k-50k: 25000 € 
                
            <li id="art-7-23" class="flex items-center py-2" data-sancion="70000 €"> Art. 7.23 - Aceptar un soborno comprendido entre 51k-90k: 70000 € 
                
            <li id="art-7-24" class="flex items-center py-2" data-sancion="120000 €"> Art. 7.24 - Aceptar un soborno mayor de 100k: 120000 € 
                
            <li id="art-7-25" class="flex items-center py-2" data-sancion="500 €"> Art. 7.25 - Hacer mal uso general de la radio: 500 € 
                
            <li id="art-7-26" class="flex items-center py-2" data-sancion="1250 €"> Art. 7.26 - Saturar la radio: 1250 €
                
            <li id="art-7-27" class="flex items-center py-2" data-sancion="1500 €"> Art. 7.27 - Poner música en la radio: 1500 € 
                
            <li id="art-7-28" class="flex items-center py-2" data-sancion="1000 €"> Art. 7.28 - Insultar o faltar el respeto a un compañero en radio: 1000 € 

            <li id="art-7-29" class="flex items-center py-2" data-sancion="750 €"> Art. 7.29 - Hablar de cosas irrelevantes por radio: 750 € 
                
            <li id="art-7-30" class="flex items-center py-2" data-sancion="950 €"> Art. 7.30 - Hablar de cosas irrelevantes por radio en un momento de tensión: 950 € 

            <li id="art-7-31" class="flex items-center py-2" data-sancion="500 €"> Art. 7.31 - Dejar el vehículo obstruyendo la vía publica innecesariamente: 500 € 
                
            <li id="art-7-32" class="flex items-center py-2" data-sancion="1500 €"> Art. 7.32 - Hacer un uso indebido de las luces de emergencia: 1500 € 
                
            <li id="art-7-33" class="flex items-center py-2" data-sancion="1750 €"> Art. 7.33 - Hacer un uso indebido de las sirenas de emergencia: 1750 € 
                
            <li id="art-7-34" class="flex items-center py-2" data-sancion="500-12500€ (Dependiendo del mal uso que se le da al vehículo)"> Art. 7.34 - Hacer uso incorrecto del vehículo de emergencias: 500-12500€ (Dependiendo del mal uso que se le da al vehículo)
               
            <li id="art-7-35" class="flex items-center py-2" data-sancion="950€"> Art. 7.35 - Hacer mal uso de dispositivos o aeronaves de vigilancia: 950€ 













                


        </ul>
    </div>
    </ul>

    </div>
    <div id="result" class="mt-5 p-4 bg-white rounded border">


        <label for="command">Comando:</label>
        <textarea id="command" rows="4" cols="150" readonly>/multar </textarea>
        <button id="copyButton" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Copiar al
            portapapeles</button>
    </div>
    </div>
    <div id="arrestReport" class="hidden p-4 bg-white rounded-lg shadow-md mt-4">
        <h3 class="text-lg font-semibold mb-2">Plantilla arrestos</h3>
        <p>Detenido: </p>
        <p>Agente de la ley: </p>
        <p>Razón: <span id="razon" class="font-medium">Razón del Arresto</span></p>
        <p>Total de multa: <span id="totalMulta" class="font-medium">Total de la Multa</span> €</p>
        <p>Foto: </p>
    </div>
    <script src="app.js"></script>

</body>

</html>
