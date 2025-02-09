# Servidor WEB

Un servidor web es un SW que gestiona y entrega contenido web a los usuarios a través de Internet. Los Servidores más importantes son:

## Apache

Es uno de los más antiguos y ampliamente utilizados. Su arquitectura está basada en procesos y hilos, lo que significa que cada solicitud se maneja en un proceso o hilo independiente. Esto hace que Apache sea muy flexible y fácil de configurar para una amplia variedad de necesidades.

### Ventajas:

Tiene una configurabilidad bastante amplia

Tiene bastante compatibilidad

Gran soporte amplio

### Desventajas:

El rendimiento: En servidores con muchas conexiones simultáneas, Apache puede consumir más recursos porque maneja cada solicitud con un proceso o hilo independiente, lo que puede ser menos eficiente.

## Nginx

Nginx es un servidor web más moderno, diseñado para ser ligero y altamente eficiente en el manejo de un gran volumen de conexiones simultáneas. Utiliza un enfoque basado en eventos asincrónicos, lo que significa que puede manejar muchas conexiones sin la necesidad de crear un nuevo proceso o hilo por cada una de ellas. Esto lo hace muy adecuado para sitios web con alto tráfico o aplicaciones que requieren un alto rendimiento.

### Ventajas:

Tiene un rendimiento más alto

Bajo consumo de recursos

Interfaz atractiva

### Desventajas:
  
Tiene configuración más compleja; su configuración y gestión pueden ser más complicadas para principiantes.

Menos módulos: En comparación con Apache, Nginx tiene menos módulos disponibles y, por lo tanto, menos opciones de personalización directa.
