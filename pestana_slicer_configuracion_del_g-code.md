# 4. Pestaña Slicer (Configuración del G-Code)

En esta pestaña, mostrada en la siguiente figura, se puede acceder a la configuración de la impresora para la pieza a imprimir.

<img src="image02.png" alt="1" height="400" width="300" align="middle">

*Figura 17. Pestaña Slicer.*

Es **recomendable** utilizar el perfil **Default** para las impresiones. No obstante, también existe la posibilidad de utilizar el perfil **Default_raft** para impresiones con material de soporte.
**Nota:**
Actualmente se esta empleando el perfil **config-brim (JorFru)** como sustituto al perfil **Default**
 
<img src="image03.png" alt="2" height="75" width="500" align="middle">

*Figura 18. Perfil config-brim (JorFru).*

Una vez seleccionado el perfil de Slicer, es posible configurar el relleno de las piezas y las capas del perímetro exterior. En la zona de Slicer, pulsar el botón **Configurar**.

Aparecerá una nueva interfaz en la que se podrán seleccionar características avanzadas. La má importante es **Fill**. Si selecciona dicho botón se desplegará un menú en la parte de abajo con distintas opciones. Interesan los campos **Extra Shells on Alternating Solid Layer** **(layers)**, que es el número de capas exteriores o perímetros; y **Infill Solidity (ratio)**, que es el porcentaje de relleno en tanto por uno.



---



***Recomendación:***

***Utilizar entre 1 y 3 layers para el extra shell; y entre 0.05 y 0.8 para el infill. Este rango de valores es más que adecuado, intentar no sobrepasarlo.***


---

<img src="image04.png" alt="3" height="400" width="400" align="middle">

*Figura 19. Configuración avanzada Slicer 1.*

<img src="image05.png" alt="3" height="400" width="400" align="middle">

*Figura 20. Configuración avanzada Slicer 2.*

<img src="image06.png" alt="3" height="400" width="400" align="middle">

*Figura 21. Configuración avanzada Slicer 3.*

Por último, guardar el estado de las modificaciones pulsando **Save All** y cerrar la ventana. En la pestaña en la que estábamos, darle al botón **Slice con slic3r** para generar el **G-Code**. Aparecerá una ventana mientras se genera.

<img src="4.png" alt="4" height="200" width="500" align="middle">
 
*Figura 22. Generando el G-Code.*
