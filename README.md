# Grafana-Loki-e2etravelsolutions-mmanuel-

# Grafana + Loki Docker Compose

Este proyecto proporciona una configuración de Docker Compose para desplegar y gestionar instancias de Grafana y Loki de manera sencilla y rápida. Grafana es una plataforma de análisis y monitorización que permite visualizar métricas y registros, mientras que Loki es un sistema de agregación de logs eficiente y fácil de usar. Esta combinación es esencial en el mundo de DevOps y Cloud Administration para el monitoreo y análisis de infraestructuras y aplicaciones.

## Requisitos

- Docker instalado
- Docker Compose instalado

## Uso

1. Clona este repositorio: `git clone https://github.com/mmanuele2etravelsolutions/Grafana-Loki-e2etravelsolutions-mmanuel-.git`
2. Navega hasta el directorio clonado: `cd Grafana-Loki-e2etravelsolutions-mmanuel-`
3. Inicia los contenedores de Grafana y Loki con Docker Compose: `docker-compose up -d`
4. Accede a Grafana a través de tu navegador web en `http://localhost:3000`. Las credenciales por defecto son `admin` como nombre de usuario y contraseña.
5. Configura Loki como una fuente de datos en Grafana para empezar a visualizar los registros.

## Configuración personalizada

Puedes personalizar la configuración de Grafana y Loki modificando los archivos de configuración correspondientes en el directorio `config/`.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún problema o tienes alguna sugerencia, por favor abre un issue en este repositorio.

## Notas adicionales

Asegúrate de revisar la documentación oficial de Grafana y Loki para obtener más información sobre cómo aprovechar al máximo estas herramientas en tus proyectos de DevOps y Cloud Administration.

- [Documentación de Grafana](https://grafana.com/docs/)
- [Documentación de Loki](https://grafana.com/docs/loki/latest/)

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](./LICENSE) para más detalles.
