Investigar como usar,
display-flex  
La herramienta Flexbox (de _Flexible Box_) fue creada para hacer estas tareas más sencillas y funcionales: los secundarios de un elemento con Flexbox se pueden posicionar en cualquier dirección y pueden tener dimensiones flexibles para adaptarse.

Llamaremos contenedores flexibles a los elementos que hay dentro de un elemento que usa el estilo **display:flex**.
Usando **display:flex** o **display:inline-flex** en una capa, la convertimos en un contenedor flexible. En el primer caso, la capa se comporta con respecto a otros elementos de la página como si tuviese **display:block**, en el segundo, como si tuviese **display:inline-block**

## Estilos fundamentales de display flex

### flex-direction

Especifica cómo se sitúan los elementos flexibles dentro del contenedor.

<style> .containerFlex c{ 
	display: flex; 
	flex-direction: row 
	} .colKhaki{ 
	background: Khaki;
	 } .colSalmon{ 
	 background: salmon; 
	 } 
	 </style>
### flex-wrap

- **wrap**: Los elementos de la capa se distribuirán en una o varias filas en función de su tamaño.
- **nowrap**: Los elementos de la capa estarán sí o sí en una sola fila.

![[Pasted image 20230831211424.png]]

# display grid 
Para crear diseños basados en **Grid CSS** necesitaremos tener en cuenta una serie de conceptos que utilizaremos a partir de ahora y que definiremos a continuación:
![[Pasted image 20230831205557.png]]
Te proporciona una cuadrícula de una sola columna, por lo que tus elementos continúan mostrándose uno debajo del otro, como lo hacen en el flujo normal. Para ver algo que se parezca más a una cuadrícula, necesitamos añadir columnas a la cuadrícula.