[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/SFLjl0fO)
# A3-Creaci-n-de-ficheros-XML
Conocimiento básico de XML 

## Creación de ficheros XML
### Ejercicio 1 Pedidos.xml
<?xml version="1.0" encoding="UTF-8"?>
<pedidos>
    <pedido cod=1>
        <fecha>05/09/2024</fecha>
        <cliente>Juan Pérez</cliente>
        <producto>Ordenador portátil</producto>
        <precio>800</precio>
    </pedido>
    <pedido cod=2>
        <fecha>05/10/2024</fecha>
        <cliente>Ana López</cliente>
        <producto>Teléfono móvil</producto>
        <precio>600</precio>
    </pedido>
    <pedido cod=3>
        <fecha>15/09/2024</fecha>
        <cliente>Pedro Gómez</cliente>
        <producto>Tablet</producto>
        <precio>400</precio>
    </pedido>
</pedidos>

### Ejercico 2 Bibliotecas.xml
<?xml version="1.0" encoding="UTF-8"?>
<biblioteca>
    <libro>
        <titulo>Cien años de soledad</titulo>
        <autor>Gabriel García Márquez</autor>
        <año>1967</año>
        <editorial>Editorial Sudamericana</editorial>
    </libro>
    <libro>
        <titulo>Don Quijote de la Mancha</titulo>
        <autor>Miguel de Cervantes</autor>
        <año>1605</año>
        <editorial>Francisco de Robles</editorial>
    </libro>
    <libro>
        <titulo>El Principito</titulo>
        <autor>Antoine de Saint-Exupéry</autor>
        <año>1943</año>
        <editorial>Reynal & Hitchcock</editorial>
    </libro>
</biblioteca>

### Ejerccio 3 Ciudades.xml
<?xml version="1.0" encoding="UTF-8"?>
<ciudades>
    <ciudad continente="Europa">
        <nombre>Madrid</nombre>
        <pais>España</pais>
    </ciudad>
    <ciudad continente="América">
        <nombre>Buenos Aires</nombre>
        <pais>Argentina</pais>
    </ciudad>
    <ciudad continente="Asia">
        <nombre>Tokio</nombre>
        <pais>Japón</pais>
    </ciudad>
</ciudades>

### Ejercicio 4 Hechos.xml
<?xml version="1.0" encoding="UTF-8"?>
<hechos>
    <hecho descripcion="Llegada del hombre a la Luna">
        <dia>20</dia>
        <mes>Julio</mes>
        <año>1969</año>
    </hecho>
    <hecho descripcion="Descubrimiento de América">
        <dia>12</dia>
        <mes>Octubre</mes>
        <año>1492</año>
    </hecho>
    <hecho descripcion="Independencia de los Estados Unidos">
        <dia>4</dia>
        <mes>Julio</mes>
        <año>1776</año>
    </hecho>
</hechos>
