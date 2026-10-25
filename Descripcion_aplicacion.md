# ExamTrainer

ExamTrainer es una aplicación Android para **entrenar exámenes tipo test**. La idea surge de
una necesidad concreta/personal: _practicar con exámenes reales de oposiciones_, 
de forma parecida a como se haría en el examen de verdad, 
pero llevando la cuenta de cómo vas mejorando.


## Qué hace

La app **se apoya en un servidor remoto donde están publicados los exámenes**. Para elegir uno,
te va guiando paso a paso: primero el año, luego el organismo y por último el examen
concreto. 

En el servidor desarrollé un frontend en Angular, pero me obligaba a realizar los 
tests con un ordenador, pq no dejé suficientemente bien preparada la interfaz para que funcionara
bien desde el navegador de un móvil o tablet. Mi intención es aprovechar esta oportunidad que 
se me presenta con la práctica de la asignatura.


Una vez empiezas, las **preguntas van saliendo de una en una**: Marcas tu respuesta, te dice en el
momento si has acertado o no, y pasa a la siguiente. La idea es 
**mostrar cómo llevas el simulacro**: tiempo que llevas, cuánto tardas de media por pregunta,
cuánto te queda y la nota que tendrías ahora mismo. Al terminar, **el resultado se guarda**.

Hay también una **pantalla de estadísticas para ver tu evolución**: en qué temas fallas más,
cuánto tardas según el tipo de pregunta, tu media... lo típico para saber por dónde flojeas.


## Otras cosas que quiero meter

- **Recordatorios** para que la app te avise de ponerte a entrenar.
- **Hacer una foto** a una hoja de preguntas en papel para subirla y que se añadan al sistema.
- **Cuentas de usuario**, con su login, para que cada uno tenga sus propios resultados.
- Poder ponerla en **modo claro u oscuro**, y que se acuerde de tu elección.


## Hasta dónde quiero llegar

Mi objetivo mínimo es que todo el ciclo funcione bien: elegir un examen, hacerlo y ver tus
estadísticas. El resto (recordatorios, la cámara, las cuentas de usuario) lo iré añadiendo
según me dé tiempo, porque algunas de esas partes dependen de que me de tiempo a ir 
adaptando el backend 🫤  
