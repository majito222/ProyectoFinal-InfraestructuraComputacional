# CONCLUSIONES

A través de este proyecto se logró implementar exitosamente una infraestructura de virtualización basada en contenedores Docker, integrada con un sistema de almacenamiento robusto mediante RAID 1 y LVM. Los principales logros fueron:

1. **Configuración de RAID 1:** Se crearon tres arreglos RAID 1 que proporcionan redundancia de datos, garantizando que la información persista incluso si uno de los discos falla.

2. **Implementación de LVM:** Se configuró LVM sobre los arreglos RAID, permitiendo una gestión flexible del almacenamiento con la posibilidad de expandir o reducir volúmenes según las necesidades futuras.

3. **Creación de imágenes personalizadas:** Se construyeron tres imágenes Docker personalizadas (Apache, MySQL y Nginx) utilizando Dockerfiles, lo que permite la reproducibilidad y portabilidad de los servicios.

4. **Persistencia de datos:** Se comprobó exitosamente que los datos persisten al eliminar y recrear contenedores, gracias a la integración de volúmenes Docker con los volúmenes lógicos LVM.

5. **Servicios funcionales:** Los tres servicios (Apache, MySQL y Nginx) quedaron operativos y accesibles, demostrando una infraestructura lista para producción.

Este proyecto permitió comprender la importancia de la virtualización con contenedores, la redundancia de almacenamiento y la gestión eficiente de volúmenes en entornos de infraestructura computacional modernos.