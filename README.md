# renderizado-condicional-thymeleaf
Ejemplo de renderizado condicional con Thymeleaf que muestra botnones y texto diferentes en función de una condición

Con un campo en la base de datos tipo tinyint ( boolean en Java ) renderizamos un botón 
con un texto 'ACTIVO' y botón de color verde si el valor es un 1 ( true en Java ) y
con un texto 'INACTIVO' y botón de color rojo si el valor es distinto de 1 ( false en Java).

Es un caso práctico de uso de th:if y th:unless
