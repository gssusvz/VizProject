# Progreso GYM

### Proyecto de Vizcarra


<p> En este proyecto el objetivo es llevar la cuenta de series, repeticiones y progreso semanal de un usuario que tenga como meta mejorar en el gimnnasio cada dia o x tiempo.
La motivaion de este proyecto es el estancamiento en el gimnasio muy comun en principiantes <p>


##Normalizacion

<p> El diagrama de flujo que tenia no necesito un cambio ya que al normalizar el proyeto no se necesito modificar, donde si se necesitaron modificaciones fue en el UML donde lo que hice fue para poder normalizarlo a la forma 1FN es eliminar algunos grupos repetidos para que cada dat sea atomico, para la forma 2FN tuve en cuenta que todos los atributos dependan de la su clave primaria y no de una parte de ella y para convertir en 3FN aqui si fueron mas cambios separe ejercicio de sesione, para que un ejericio exista independientemente de si se entrena hoy o mañana y asi la relacion entre ambos ocurra solo en la tabla intermedia que seria set_series <p>
