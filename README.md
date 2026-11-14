# SOGED - Software de Gestión Documental

SOGED es un software de gestión documental para simular un entorno laboral. Lo desarrollamos como aprendices de **Análisis y Desarrollo de Software (ADSO) del SENA** para los aprendices del programa de **Gestión Documental**.

Su objetivo es que los aprendices practiquen, durante la etapa lectiva, cómo se maneja la documentación en un entorno de trabajo real: registrar, organizar y consultar documentos sin usar información de empresas reales.

> ⚠️ Proyecto de uso solo académico.

## ¿Qué puedes hacer en SOGED?

* Iniciar sesión (solo con usuarios creados por el administrador, no hay registro libre).
* Manejar la correspondencia **recibida**, **despachada** e **interna**.
* Trabajar con distintos tipos de documentos: cartas, memorandos, circulares, actas, informes, PQR y facturas.
* Consultar reportes.
* Administrar usuarios y roles.
* Usar una agenda con calendario para marcar fechas con etiquetas de colores.

## Usuarios y roles

| Rol | Quién lo usa | Qué hace |

| Administrador general | El equipo de desarrollo | Administra todo el sistema |

| Administrador principal | Instructores | Registra aprendices, asigna roles y asigna tareas |

| Administrador interno | Aprendiz con este rol | Delega tareas |

| Radicador general | Aprendiz | Radica la correspondencia |

| Usuario general | Aprendiz | Consulta y usa el sistema |

## Tecnologías utilizadas

* **HTML5:** estructura de todas las páginas.
* **CSS3:** estilos, colores y organización del diseño.
* **Bootstrap:** componentes y diseño de las páginas de inicio y usuarios, incluida la agenda.
* **Git y GitHub:** control de versiones y trabajo en equipo.

## Estructura del proyecto

```
SOGED/
├── index.html        → Página principal (inicio de sesión)
├── CSS/              → Hojas de estilo (general.css y una por cada página)
├── HTML/             → Páginas internas (comunicaciones, reportes, usuarios)
└── Imagenes/         → Logos, iconos y recursos gráficos
```

> `general.css` se carga primero en cada página porque ahí está el encabezado y el menú que comparten todas. Después se carga el CSS propio de cada página.

## Cómo ejecutar el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/TU-USUARIO/NOMBRE-DEL-REPOSITORIO.git
   ```
2. Abre la carpeta en **Visual Studio Code**.
3. Abre el archivo `index.html` en cualquier navegador web.

No necesitas instalar nada más. La agenda y los componentes de Bootstrap necesitan internet si el proyecto los carga desde un enlace (CDN).

## Equipo de desarrollo (ADSO - SENA)

* Justin Kalel Ortiz Suarez
* Katherin Sofia Cruz Diaz
* Maria Camila Prada Yepes
* Nathalia Romero Montealegre


## Estado del proyecto

En desarrollo 🚧