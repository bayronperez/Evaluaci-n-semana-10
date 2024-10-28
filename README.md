# GPSMapApp

## Descripción
Este proyecto es una aplicación Android que implementa medidas de seguridad para proteger contra vulnerabilidades comunes. La aplicación está diseñada para ofrecer servicios de localización y navegación utilizando tecnología GPS y Google Maps, asegurando la privacidad y seguridad de los datos del usuario.

## Vulnerabilidades Identificadas 
Durante el análisis de seguridad, se detectaron las siguientes vulnerabilidades críticas:
- **Inyección SQL**: Posibilidad de que un atacante inyecte código SQL malicioso.
- **Comunicación no segura**: Uso de conexiones HTTP, exponiendo datos durante la transmisión.
- **Exposición de datos sensibles**: Configuraciones que permiten el respaldo no autorizado de datos.

## Mejoras Implementadas 
Para mitigar las vulnerabilidades identificadas, se implementaron las siguientes mejoras:
- **Cifrado de datos sensibles**: Los datos críticos se almacenan de manera cifrada utilizando estándares de seguridad.
- **Comunicación segura (HTTPS)**: Todas las comunicaciones de red se realizan a través de HTTPS para proteger la información del usuario.
- **Validación y sanitización de entradas**: Se validan y sanitizan todas las entradas del usuario para prevenir ataques de inyección.

## Documentación 
- [Vulnerabilidades](vulnerabilities.md) 
- [Best Practices](best_practices.md) 
- [Security Tips](security_tips.md) 
- [Security Improvement Program](security_improvement_program.md)

- ## Cómo Ejecutar la Aplicación de Forma Segura 
1. Clonar el repositorio 
2. Importar el proyecto en Android Studio 
3. Ejecutar la aplicación en un dispositivo o emulador 
4. Asegurarse de que los permisos necesarios están configurados 

## Reporte de Vulnerabilidades El reporte detallado de las pruebas de vulnerabilidad realizadas se encuentra en el archivo `vulnerability_report.pdf`.
