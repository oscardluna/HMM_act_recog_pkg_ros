# HMM_act_recog_pkg_ros

## Paquete de ROS que se utliza como un servicio que infiere acciones mediante el uso de HMM
### Este paquete se utiliza mediante el uso conjunto de CNNs que obtienen el esqueleto de personas en imágenes
### Este paquete se separó del uso conjunto mencionado anteriormente para que funcione de manera independiente. Se asume que la entrada será una secuencia de esqueletos obtenidos de otro medio, por ejemplo con la salida de utilizar una red convoucional (OpenPose) en una secuencia de imágenes (video). 

### La salida de este servicio es un indice de la acción inferida, siendo esta lista de acciones la siguiente: 'Saludar (mano derecha)", "saludar (mano izquierda)", "Apuntar", "Beber"; mas una 'no accion' denominada "neutral".

