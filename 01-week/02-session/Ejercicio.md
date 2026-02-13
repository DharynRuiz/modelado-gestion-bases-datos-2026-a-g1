# 1. ¿Qué pasaría si no definimos correctamente las claves de cada entidad desde el inicio?
## Si no se define correctamente las claves se comprometeria la integridad de los datos y su consistencia. Esto provocaria: imposibilidad de distinguir registro entre los datos, redundancias entre otras
## Ejemplo: Si una persona se acerca a una institucion que preste servicio al publico y tenga que manipular una gran cantidad de Datos, y solicite una informacion de (Sebastian Osorio) y aparece en su BD 20 Sebastian Osorio pero no tiene una clave deifinida para distinguir cada una, puede haber una error al entregar informacion de dicha persona 
| Nombres       | Apellidos     | 
|---------------|---------------| 
| Sebastian     | Osorio        | 
| Sebastian     | Osorio        |
| Sebastian     | Osorio        |
| Sebastian     | Osorio        |
| Sebastian     | Osorio        |
| Sebastian     | Osorio        |

# 2. ¿Qué ventajas aporta tener identificadas las entidades antes de pasar al diagrama ER formal?
## Tener claras las entidades antes de pasar al diagrama ER formal da claridad en los requerimientos ya que permite entender que informacion es relevante para el sistema, legnuaje comun
## Ejemplo: Entidad: Estudiante Atributo: nombre, correo (propiedades), relacion cursando (verbo que conecta);
# 3. ¿Qué información adicional consideras crítica en un sistema académico que aún no hemos modelado?
## para mi opinion seria bueno que en la misma BD se para el usuario estudiantes se le permita visualizar los horarios de los profesores para dar sus tutorias.
| Nombres | Apellidos | Aula       | Hora     |
|---------|-----------|------------|----------|
| Jesus   | Bonilla   | C-509      | 03:00 PM |
| Alvaro  | Alarcon   | BIBLIOTECA | 09:00 AM |