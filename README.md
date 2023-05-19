# Patrones-Gof-para-el-Desarrollo-y-Tipos-de-Pruebas-de-

hecho por: Heidy Vanessa Hernández Garzón Y Laura Valentina Cubillos Buitrago

1. Patrones GOF
  Los patrones de diseño tuvieron su origen a mediados de la década del noventa, a raíz de la publicación arriba nombrada, y a partir de  allí fueron ampliamente aceptados en el área de desarrollo de software tanto en empresas como en el mundo académico. 
  
  Los GoF dieron una definición precisa de lo que es un patrón de diseño y cómo debe ser usado: “descripciones de objetos que se comunican y clases que son personalizadas para resolver un problema de diseño general en un contexto particular”. Estos se encargan de las opciones de comportamiento de la aplicación, facilitando la variabilidad en el comportamiento durante le ejecución y hay siete tipos de patrones que son: Adapter, Bridge, Composite, Decorator, Façade,Flyweight y Proxy y iii).
  
  Describen soluciones a problemas de diseño específicos que surgen al refinar un diseño global. Estos patrones pueden ser dependientes o independientes del dominio de aplicación. En el primer caso los patrones de diseño se aplican a problemas de diseño en dominios específicos, tales como aplicaciones gráficas o de hipertexto. Los patrones independientes del dominio proveen soluciones para producir estructuras de diseño flexibles que pueden ser fácilmente adaptadas a nuevos requerimientos.
  
  Es puede identificar a los patrones de diseño GOF en desarrollo software para esto se debe hacer un conjunto de actividades; primero se construye unas normas o criterios que permitan un punto de análisis con el fin de identificar los procesos de desarrollo más representativos, a siendo obligatorio cumplir estos criterios que sean válidos en este análisis, y obtener la muestra de los procesos de desarrollo. El cumplimiento de las normas que se deben tener en estos procesos de desarrollos son estrictas e importantes, debido a que tienen como objetivo obtener resultados a partir del estudio de procesos de desarrollo formales, de esta manera se determina un grupo de procesos de desarrollo que le permite cumplir con un estricto control de calidad en las fases de requerimientos, diseño, desarrollo e implantación. Cabe tener en cuenta que todo proceso de calidad contiene variables que llegar a determinar la complejidad del mismo, en estas están: la cantidad de desarrolladores, diseños en UML, nivel de criticidad del sistema, costos del proyecto, modelo de requisitos empleado y el modelo de calidad utilizado.
  
Características
  
 1. Son soluciones concretas., no son teorías genéricas.
      
 2. Son soluciones técnicas, basadas en Programación Orientada a Objetos (POO). En ocasiones tienen más utilidad con algunos lenguajes de programación y en otras son aplicables a cualquier lenguaje.

 3. Se utilizan en situaciones frecuentes. Debido a que se basan en la experiencia acumulada al resolver problemas reiterativos.

 4. Favorecen la reutilización de código. 

 5. El uso de un patrón no se refleja en el código.

 6. Es difícil reutilizar la implementación de un patrón.
      
      
2. Pruebas 
   
[![Whats-App-Image-2023-05-18-at-6-46-58-PM.jpg](https://i.postimg.cc/HLM7vrvG/Whats-App-Image-2023-05-18-at-6-46-58-PM.jpg)](https://postimg.cc/4KJdmxTw) 
   
  Qué es Software Testing? 
  
  Software Testing es la actividad de probar un software para verificar el funcionamiento y encontrar errores. Existen varias técnicas de prueba manual que ayudan a reducir el número de casos de prueba que se ejecutarán al tiempo que aumentan la cobertura de prueba. Ayudan a identificar condiciones de prueba que de otro modo serían difíciles de reconocer
  
 2.1. Prueba de caja negra:      
          
  Se basa en los requisitos y la funcionalidad, sin considerar el diseño interno, cuya finalidad es analizar la compatibilidad entre las interfaces de cada uno de los componentes del software.
          
          
          
 2.2. Prueba de caja blanca:
     
  Su objetivo es realizar pruebas que cubran la estructura interna de un sistema, por estructura interna nos referimos a código, arquitectura y flujos de trabajo.
          
          
          
 2.3. Prueba Alfa:
     
  Es el tipo de prueba más utilizada. Su objetivo es identificar todos los posibles problemas o defectos antes de lanzarlo al mercado o al usuario. Se lleva a cabo al final de la fase de desarrollo, pero antes de la prueba beta.
          
          
          
 2.4. Prueba Beta:
     
  Es un tipo formal de prueba de software que lleva a cabo el cliente. Se realiza en el entorno real antes de lanzar el producto al mercado para los usuarios finales reales. Con ella, se garantiza que no haya fallas importantes en el software y que el producto cumpla con los requisitos comerciales y las expectativas del cliente.
          
          
          
 2.5. Pruebas de aceptación:
      
  En este caso, es el cliente quien realiza una prueba de aceptación y verifica el flujo del sistema de extremo a extremo según los requisitos comerciales. 
           
           
           
 2.6. Pruebas Ad-hoc:
      
  Se realiza sobre una base Ad-hoc y su objetivo es encontrar los defectos y romper la aplicación ejecutando cualquier flujo de la aplicación o cualquier funcionalidad aleatoria.
           
           
           
 2.7. Pruebas de accesibilidad:
       
  Determina si el software es accesible para personas con discapacidades (sordos, daltónicos, discapacitados mentales, ciegos, ancianos y otros grupos discapacitados). 
            
            
            
 2.8. Pruebas de fondo:
       
  La prueba realizada en la base de datos (SQL Server, MySQL y Oracle, etc) se conoce como Prueba de base de datos o Prueba de fondo. Estas pruebas implican test de estructura de tabla, esquema, procedimiento almacenado, estructura de datos, etc.
            
            
            
 2.9. Pruebas de compatibilidad del navegador:
       
  Es un subtipo de Pruebas de compatibilidad y lo realiza el equipo de pruebas para garantizar que el software pueda ejecutarse con la combinación de diferentes navegadores y sistemas operativos.
            
            
            
 2.10. Pruebas de compatibilidad con versiones anteriores:
      
  Es un Test que valida si el software recientemente desarrollado o el software actualizado funciona bien con versiones anteriores del entorno o no.
            
            
            
 2.11. Prueba de valor límite:
      
  Verifica el comportamiento de la aplicación a nivel de límite. Se realiza para verificar si existen defectos en los valores límite.
            
            
            
 2.12. Prueba de rama:
       
  También llamada prueba de caja blanca, se lleva a cabo durante la prueba de la unidad. El nombre en sí sugiere que el código se prueba a fondo al atravesar cada rama
             
             
             
 2.13. Pruebas de comparación: 
       
  Compara las fortalezas y debilidades de un producto con sus versiones anteriores u otros productos similares.
             
             
             
 2.14. Prueba de compatibilidad:
       
  Evalúa cómo se comporta y ejecuta el software en un entorno diferente, servidores web, hardware y entorno de red.
             
             
             
 2.15. Pruebas unitarias:
       
  Son una forma de comprobar que un fragmento de código funciona correctamente. Es un procedimiento más de los que se llevan a cabo dentro de una metodología ágil de trabajo.
             
             
             
 2.16. Prueba de componentes:
       
  Generalmente se lleva a cabo luego de las pruebas unitarias. Evalúa múltiples funcionalidades como  un solo código y su objetivo es identificar si existe algún defecto después de conectar esas múltiples funcionalidades entre sí.
             
             
             
 2.17. Pruebas de extremo a extremo:
        
  Evalúa el entorno de aplicación en un contexto que simula el uso real. Puede consistir en interactuar con una base de datos, usar comunicaciones de red o interactuar con otro hardware, aplicaciones o sistemas.
              
              
              
 2.18. Particionamiento de equivalencia:
        
  Es una técnica de prueba y un tipo de prueba de caja negra. Durante esta partición de equivalencia, se selecciona un conjunto de grupos y se recogen algunos valores o números para la prueba. Dichos valores deben generar la misma salida. El objetivo de la prueba es eliminar los casos de prueba redundantes.
              
              
              
 2.19. Ejemplo de prueba:
        
  Son pruebas en tiempo real que se realizan en un escenario real o escenarios basados en la experiencia de los probadores.        
              
              
              
 2.20. Pruebas exploratorias:
        
  Es una prueba informal realizada por el equipo de prueba para explorar la aplicación y buscar defectos que existan en la aplicación
        
        
        
 2.21. Pruebas funcionales:
        
  Ignora las partes internas y se enfoca solo en la salida para verificar si la aplicación cumple con el requisito o no. Es un tipo de prueba de caja negra.
              
              
              
 2.22. Prueba de interfaz gráfica de usuario (GUI):
        
  Valida la GUI según el requisito comercial. Incluye el tamaño de los botones y el campo de entrada presente en la pantalla, la alineación de todo el texto, las tablas y el contenido de las tablas.
              
              
              
 2.23. Prueba de gorila:
        
  Aplicada por probadores y desarrolladores, la prueba de gorila o Gorilla Testing evalúa exhaustivamente cada módulo para verificar la solidez de la aplicación.
              
              
              
 2.24. Prueba Happy Path:
        
  Su objetivo es probar la aplicación con éxito en un flujo positivo. No busca condiciones negativas o errores.
              
              
              
 2.25. Prueba de integración incremental:
        
  Es un enfoque ascendente para pruebas que se aplica cuando se agrega una nueva funcionalidad. Queda a cargo de programadores y probadores. 
              
              
              
 2.26. Pruebas de instalar / desintalar:
        
  Es un tipo de prueba que se aplica en procesos de instalación / desinstalación completos, parciales o de actualización en diferentes sistemas operativos en diferentes entornos de hardware o software.
              
              
              
 2.27. Pruebas de integración:
        
  Es un tipo de prueba no funcional utilizada para verificar cuánta carga de trabajo máxima puede manejar un sistema sin ninguna degradación del rendimiento. Estas pruebas ayudan a encontrar la capacidad máxima del sistema bajo una carga específica y cualquier problema que cause la degradación del rendimiento del software.
              
              
              
 2.28. Monkey Testing:
       
  Es una prueba que supone que si un mono usa la aplicación, ingresará los valores sin ningún conocimiento o comprensión de la aplicación. De esta manera, el objetivo de Monkey Testing es verificar si una aplicación o sistema se bloquea proporcionando datos / valores de entrada aleatorios.
              
              
              
 2.29. Prueba de mutación:
       
  Es una prueba de caja blanca en  la que se cambia el código fuente de uno de los programas y verifica si los casos de prueba existentes pueden identificar estos defectos en el sistema.
             
             
             
 2.30. Pruebas negativas:
       
  Su objetivo es ver si se puede “romper” el sistema. Para ello se utilizan datos incorrectos, datos no válidos o entradas.
             
             
             
 2.31. Pruebas no funcionales
        
  Son pruebas de carga, pruebas de tensión, seguridad, volumen, pruebas de recuperación, etc. que se realizan para garantizar si el tiempo de respuesta del software o la aplicación es lo suficientemente rápido según los requisitos del negocio.
              
              
              
 2.32. Pruebas de rendimiento:
        
  Son pruebas que se realizan para verificar si el sistema cumple con los requisitos de rendimiento. Para ello, se utilizan diferentes herramientas de rendimiento y carga.
              
              
              
 2.33. Pruebas de recuperación:
        
  Se encarga de validar qué tan bien se recupera la aplicación o el sistema de fallas o desastres. Determina si el sistema puede continuar la operación después de un desastre.
              
              
              
 2.34. Pruebas de localización:
        
  Se evalúa una versión localizada de un producto, de un servicio o de sus contenidos para asegurarse de que esté bien hecha.
              
              
              
 2.35. Prueba basada en la tabla de decisiones:
        
  También conocida como tabla causa-efecto, es una técnica para funciones que responden a una combinación de entradas o eventos. Por ejemplo, prueba que el botón de envío esté habilitado si el usuario llena todos los campos obligatorios.
              
  Para cada función, debes crear una tabla y enumerar todos los tipos de combinaciones de entradas y sus respectivas salidas. Así, puedes identificar una condición que el tester pasa por alto. 
              
Sigue estos pasos para crear una tabla de decisiones:
    
 1. Alista las entradas en filas.
         
 2. Ingresa todas las reglas en la columna.
         
 3. Rellena la tabla con la combinación diferente de entradas.
         
 4. En la última fila, anota la salida contra la combinación de entrada.
         
Bibliografías:

Patrones gof:

https://www.torresburriel.com/weblog/2022/03/14/que-son-los-patrones-de-diseno-y-por-que-utilizarlos/

https://www.ecured.cu/Patrones_Gof

https://www.scielo.cl/scielo.php?script=sci_arttext&pid=S0718-07642013000300012#:~:text=Los%20patrones%20que%20hacen%20parte%20de%20esta%20categor%C3%ADa%20son%20siete,interact%C3%BAan%20y%20distribuyen%20la%20responsabilidad.

Pruebas:

https://www.tecnologias-informacion.com/software-testing.html

Imágenes:

https://es.vecteezy.com/arte-vectorial/3762477-instalacion-prueba-concepto-icono-software-programacion-etapa-idea-linea-delgada-ilustracion-desarrollo-aplicacion-implementacion-prueba-proyecto-vector-aislado-esquema-dibujo-trazo-editable

