# Patrones-Gof-para-el-Desarrollo-y-Tipos-de-Pruebas-de-Software
hecho por: Heidy Vanessa Hernández Garzón Y Laura Valentina Cubillos Buitrago

1. Patrones GOF
  Los patrones de diseño tuvieron su origen a mediados de la década del noventa, a raíz de la publicación arriba nombrada, y a partir de  allí fueron ampliamente aceptados en el área de desarrollo de software tanto en empresas como en el mundo académico. 
  
  Los GoF dieron una definición precisa de lo que es un patrón de diseño y cómo debe ser usado: “descripciones de objetos que se comunican y clases que son personalizadas para resolver un problema de diseño general en un contexto particular”. Estos se encargan de las opciones de comportamiento de la aplicación, facilitando la variabilidad en el comportamiento durante le ejecución y hay siete tipos de patrones que son: Adapter, Bridge, Composite, Decorator, Façade,Flyweight y Proxy y iii).
  
  Describen soluciones a problemas de diseño específicos que surgen al refinar un diseño global. Estos patrones pueden ser dependientes o independientes del dominio de aplicación. En el primer caso los patrones de diseño se aplican a problemas de diseño en dominios específicos, tales como aplicaciones gráficas o de hipertexto. Los patrones independientes del dominio proveen soluciones para producir estructuras de diseño flexibles que pueden ser fácilmente adaptadas a nuevos requerimientos.
  
  Es puede identificar a los patrones de diseño GOF en desarrollo software para esto se debe hacer un conjunto de actividades; primero se construye unas normas o criterios que permitan un punto de análisis con el fin de identificar los procesos de desarrollo más representativos, a siendo obligatorio cumplir estos criterios que sean válidos en este análisis, y obtener la muestra de los procesos de desarrollo. El cumplimiento de las normas que se deben tener en estos procesos de desarrollos son estrictas e importantes, debido a que tienen como objetivo obtener resultados a partir del estudio de procesos de desarrollo formales, de esta manera se determina un grupo de procesos de desarrollo que le permite cumplir con un estricto control de calidad en las fases de requerimientos, diseño, desarrollo e implantación. Cabe tener en cuenta que todo proceso de calidad contiene variables que llegar a determinar la complejidad del mismo, en estas están: la cantidad de desarrolladores, diseños en UML, nivel de criticidad del sistema, costos del proyecto, modelo de requisitos empleado y el modelo de calidad utilizado.
  
  Características:
      1.1. Son soluciones concretas., no son teorías genéricas.
      
      1.2. Son soluciones técnicas, basadas en Programación Orientada a Objetos (POO). En ocasiones tienen más utilidad con algunos lenguajes de programación y en otras son aplicables a cualquier lenguaje
      
      1.3. Se utilizan en situaciones frecuentes. Debido a que se basan en la experiencia acumulada al resolver problemas reiterativos.
      
      1.4. Favorecen la reutilización de código. 
      
      1.5. El uso de un patrón no se refleja en el código
      
      1.6. Es difícil reutilizar la implementación de un patrón
      
      
2. Pruebas 
   
   
   
  Qué es Software Testing? 
  
  Software Testing es la actividad de probar un software para verificar el funcionamiento y encontrar errores. Existen varias técnicas de prueba manual que ayudan a reducir el número de casos de prueba que se ejecutarán al tiempo que aumentan la cobertura de prueba. Ayudan a identificar condiciones de prueba que de otro modo serían difíciles de reconocer
  
     2.1. Prueba de caja negra:      
          
          Se basa en los requisitos y la funcionalidad, sin considerar el diseño interno, cuya finalidad es analizar la compatibilidad entre las interfaces de cada uno de los componentes del software.
          
          
          
     2.2.  Prueba de caja blanca:
     
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
      
            
          
