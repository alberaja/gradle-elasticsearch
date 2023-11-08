# gradle-elasticsearch
https://www.youtube.com/watch?v=IiZZAu2Qtp0&amp;list=PLXy8DQl3058OoJqGLFdqoBkBKm2T0kS9B code:  https://github.com/liliumbosniacum/elasticsearch

Ventajas: Ejecuta querys de otra forma en : VehicleService.java 


Desventajas: . gradle que no se me importa como Java Project y NO puedo ejecutatlo Run As->Spring o Java Aplication


Acciones: 
RecreateIndices 
.save(person) 
.findById(id) 
 

Vehicle:    
- insertDummyData(); 
- .getById(id); 
- .search(dto);   match query: //Busquedas por el valor de cada 'field'       // Respuesta de todos documentos en los que haya 1 "columna" llamada number y su valor contenga "Vehicle":
 ![image](https://github.com/alberaja/gradle-elasticsearch/assets/29755489/71087d50-bd68-4608-8e7e-de2487e6fc15)
![image](https://github.com/alberaja/gradle-elasticsearch/assets/29755489/6df7dc51-dd9e-4bc6-b2bb-7d00f7af80d9)
![image](https://github.com/alberaja/gradle-elasticsearch/assets/29755489/03c90ff3-d149-489d-9a24-5a519a5dee76)


-      .getAllVehiclesCreatedSince(date); 
- .searchCreatedSince(dto, date);  


