# Habilitacion_Sprint_6_JC

Gestión de ingreso al sistema de información. 
El sistema tendrá una interfaz gráfica para el ingreso a la aplicación (registro e inicio de sesión), la autorización de ingreso a la aplicación estaría a cargo de un tercero (Gmail) mediante “Oauth 2”; todos los usuarios que se registran entran en estado pendiente. 

● Módulo administrador de productos.  El sistema tendrá una interfaz gráfica para el registro de productos y otra para listar, buscar y actualizar productos, cada uno debe contar con los siguientes atributos: Identificador único (Inmutable), descripción, valor unitario y estado (disponible, no disponible). 

● Módulo administrador de ventas. El sistema tendrá una interfaz gráfica para el registro de las ventas y otra para listar, buscar y actualizar las ventas realizadas (Actualizar se refiere a establecer los diferentes estados de la venta: En proceso, cancelada o entregada, o editar alguno de sus otros campos modificables). Cada venta debe contar con los siguientes atributos: Identificador único de venta (Inmutable), el valor total de la venta, identificador, cantidad y precio unitario de cada producto, fecha de venta, el documento de identificación y nombre del cliente, y, además, deberá contar con un encargado de gestionar dicha venta (vendedor). 

● Gestión de usuarios. Permite ver y actualizar el rol (administrador y vendedor) y el estado del usuario (pendiente/autorizado/no autorizado)
