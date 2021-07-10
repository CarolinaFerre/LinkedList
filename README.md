# ejercicios_LinkedList

LISTAS ENLAZADAS:

Ventajas:

. Acceso aleatorio.
. Están ordenadas(collection.sort()).
. Añadir/eliminar sin restricción
. Listlterator modifca en cualquier dirección
. Sintaxis similar a Arrays

Inconvenientes:

.Bajo rendimiento en operaciones concretas que se resolverán mejor con otras interfaces.

Tipos: ArrayList, LinkedList, Vector, CopyOnWriteArrayList

Diferencias entre LinkedList y ArrayList:

Los arrayList se ordenan en forma de pila, si se elimina uno de los objetos se obliga a rellenar ese hueco. Con lo cual habría
que mover toda la información que tenemos a continuación una posición para que ese hueco quede cubierto.

La linkedlist cuando rellenamos la lista con ese objeto, tiene dos enlaces en cada uno de los extremos que permiten enlazar o linkar
cada uno de los datos. Si queremos eliminar uno de los datos, no hay que rellenar el hueco sino que se ajustan los enlaces.

Se pueden usar los iteradores para recorrer la linkedList hacia alante y hacia atrás se usa a través de la interfaz ListIterator<E> (a través de:
  add()-->para agregar elementos genéricos en la posición que quedamos
  hasNext()-->booleano, comprueba si hay elementos más adelante de donde se encuentra el cursor
  hasPrevious()-->booleano,comprueba si hay elementos hacia detrás de donde se encuentra el cursor
  next()--> movernos hacia delante
  nextIndex()-->movernos a una posición en concreto hacia delante
  previous()-->movernos hacia detrás
  previousIndex()-->movernos a una posición en concreto hacia atrás
  remove()-->Eliminar elementos
  set()-->Establecer o reemplazar elementos nuevos

  
  
