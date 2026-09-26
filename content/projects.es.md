---
title: 'Proyectos'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

sections:
  - block: projects-timeline
    content:
      title: Proyectos
      items:
        - title: StudyBuddy, buscador de grupos de estudio
          org: Proyecto final de Ingeniería de Software
          date: octubre 2025 – diciembre 2025
          icon: hero/code-bracket
          summary: |-
            - Desarrollé StudyBuddy con un compañero: una aplicación web en Flask donde los estudiantes se registran, inician sesión y crean, se unen y administran grupos de estudio, con chat grupal para compartir mensajes y archivos, seguimiento de tareas y enlaces a videollamadas.
            - Migré la base de datos de la aplicación de SQLite a MongoDB Atlas con PyMongo, llevando a la nube los usuarios, grupos, mensajes y tareas.
            - Corregí un error de permisos que permitía a usuarios que no eran creadores editar grupos, limitando la edición y eliminación al creador de cada grupo.
            - Trabajé a lo largo de tres sprints ágiles con Git y GitHub, y me encargué de la depuración final antes de la presentación en clase.
          tools:
            - { name: Python, icon: devicon/python }
            - { name: Flask, icon: brands/flask }
            - { name: MongoDB, icon: devicon/mongodb }
            - { name: HTML, icon: devicon/html5 }
            - { name: Bootstrap, icon: devicon/bootstrap }
            - { name: Git, icon: devicon/git }
          links:
            - text: Repositorio en GitHub
              url: https://github.com/adanbarrera82/Final-Project
          figures:
            - src: uploads/projects/studybuddy-groups.png
              wide: true
              alt: Página principal de StudyBuddy en modo oscuro, con un filtro por materia y cuatro tarjetas de grupos de estudio que muestran el número de miembros, el creador, los miembros y los botones Unirse, Salir, Chat, Editar y Eliminar
              title: Panel de grupos de estudio
              caption: La página principal, donde los estudiantes filtran los grupos por materia y se unen, salen, chatean o administran cada grupo.

        - title: Aterrizajes del cohete Falcon 9 de SpaceX
          org: IBM Data Science Professional Certificate · Applied Data Science Capstone
          date: julio 2025
          summary: |-
            - Preparé y analicé datos de lanzamientos del Falcon 9 en Python para identificar los parámetros clave que predicen el éxito del aterrizaje de la primera etapa.
            - Creé visualizaciones interactivas con Plotly y Seaborn para explorar cómo se relacionan los parámetros de lanzamiento con los resultados del aterrizaje.
          tools:
            - { name: Python, icon: devicon/python }
            - { name: pandas, icon: devicon/pandas }
            - { name: Plotly, icon: devicon/plotly }
            - { name: Seaborn, icon: devicon/seaborn }
            - { name: Jupyter, icon: devicon/jupyter }
          links:
            - text: Insignia del proyecto final
              url: https://www.credly.com/badges/2fc745a1-b5d5-4582-9348-cdf134b4b7e8
            - text: Certificado
              url: https://www.credly.com/badges/5e80beff-1b1a-4e27-96fb-c8b249561024
          figures:
            - src: uploads/projects/spacex-success-rate-by-year.png
              alt: Gráfica de líneas en Seaborn de la tasa de éxito de aterrizaje de la primera etapa del Falcon 9 por año, en cero hasta 2013 y subiendo a cerca del 90% en 2019
              title: Tasa de éxito de los aterrizajes
              caption: Tasa anual de éxito en el aterrizaje de la primera etapa, que sube de cero antes de 2014 a cerca del 90% en 2019.
            - src: uploads/projects/spacex-success-rate-by-orbit.png
              alt: Gráfica de barras en Seaborn del éxito promedio de aterrizaje por tipo de órbita, con ES-L1, SSO, HEO y GEO al 100% y GTO como la más baja, con cerca del 52%
              title: Tasa de éxito por órbita
              caption: Éxito promedio de aterrizaje según la órbita de destino; las misiones a ES-L1, SSO, HEO y GEO aterrizaron siempre.

        - title: Análisis de datos web con los GRAMMYs
          org: The Global Career Accelerator
          date: julio 2024 – agosto 2024
          summary: |-
            - Identifiqué tendencias clave y comportamientos de los usuarios con Python para orientar la estrategia de contenido y las iniciativas promocionales, analizando e interpretando los datos de tráfico web de los GRAMMYs.
            - Analicé métricas de rendimiento clave con pandas, descubriendo patrones e identificando áreas de mejora que llevaron a una mayor participación de los usuarios y a la optimización del sitio.
            - Realicé un análisis comparativo y de la competencia, identificando oportunidades de crecimiento y ventajas estratégicas para posicionar a los GRAMMYs por delante de sus competidores.
            - Desarrollé visualizaciones de datos dinámicas e interactivas con Plotly, entregando información útil a los responsables de los GRAMMYs y facilitando la toma de decisiones basada en datos.
          tools:
            - { name: Python, icon: devicon/python }
            - { name: pandas, icon: devicon/pandas }
            - { name: Plotly, icon: devicon/plotly }
            - { name: NumPy, icon: devicon/numpy }
          links:
            - text: Certificado
              url: https://www.credential.net/8156ede7-dcc7-49e1-a57c-7ebcc27c035a
          figures:
            - src: uploads/projects/grammys-pages-per-session.png
              wide: true
              alt: Gráfica de líneas en Plotly del promedio diario de páginas por sesión de febrero de 2022 a junio de 2023; el sitio de la Recording Academy tiene una mediana de 2.9 páginas y un pico de 11.4 el 15 de junio de 2022, y grammy.com una mediana de 2.1 con un pico de 5.8 el 5 de febrero de 2023
              title: Páginas por sesión
              caption: Participación diaria en los sitios web de los GRAMMYs y de la Recording Academy. Los visitantes de la Recording Academy vieron más páginas por visita, mientras que el pico de los GRAMMYs coincidió con la ceremonia de premios de febrero de 2023.
            - src: uploads/projects/grammys-age-demographic.png
              wide: true
              alt: Gráfica de barras agrupadas en Plotly de los visitantes por grupo de edad en grammy.com y recordingacademy.com; los grupos de 18 a 24 y de 25 a 34 son los más grandes y el de 65 o más el más pequeño
              title: Demografía por edad
              caption: Proporción de visitantes por grupo de edad en los sitios web de los GRAMMYs y de la Recording Academy, creada con Plotly.

        - title: Proyecto de sostenibilidad de Intel
          org: The Global Career Accelerator
          date: junio 2024 – julio 2024
          summary: |-
            - Realicé una investigación a fondo con consultas SQL complejas para determinar las mejores ubicaciones para nuevos centros de datos, según la disponibilidad de energía y los requisitos de sostenibilidad.
            - Generé conclusiones y recomendaciones para guiar la selección de sitios sostenibles y energéticamente eficientes en la toma de decisiones.
            - Encontré formas de maximizar el uso de energía en la operación de los centros de datos y de aprovechar fuentes de energía renovable, lo que ayudó a Intel a cumplir su compromiso con sus metas de sostenibilidad.
            - Identifiqué lugares con excedente de producción de energía, lo que podría reducir los costos de adquisición de energía para centros de datos nuevos.
            - Contribuí de forma significativa a los esfuerzos de sostenibilidad de Intel con información basada en datos sobre estrategias de adopción de energía renovable, todo visualizado en Tableau.
          tools:
            - { name: SQL, icon: devicon/microsoftsqlserver }
            - { name: Tableau, icon: custom/tableau }
          links:
            - text: Certificado
              url: https://www.credential.net/70c06f22-64c1-4694-bcb4-2ff9ce7dde34
          figures:
            - src: uploads/projects/intel-renewable-share-by-region.jpg
              alt: Gráfica de barras en Tableau de la energía renovable como porcentaje de la generación total por región de EE. UU., encabezada por Northwest, Central y California, con Florida como la más baja
              title: Energía renovable (%) por región
              caption: Qué porcentaje de la energía de cada región proviene de fuentes renovables.
            - src: uploads/projects/intel-net-production-by-region.jpg
              alt: Gráfica de barras en Tableau de la producción neta de energía por región de EE. UU.; New England y Mid-Atlantic producen un excedente, mientras que California y New York muestran los mayores déficits
              title: Producción neta frente a demanda de energía
              caption: Producción neta de energía por región. Las regiones por debajo de cero no alcanzan a cubrir su demanda de energía.

        - title: Análisis de datos de una empresa
          date: mayo 2024
          summary: |-
            - Creé y administré una base de datos SQL de más de 15,000 filas para ofrecer un acceso estructurado y controlado a los datos, apoyando el análisis de ventas y rendimiento.
            - Desarrollé pipelines automatizados en Python para la limpieza, transformación y almacenamiento de datos, garantizando una calidad de datos consistente y trazable.
            - Creé reportes en Tableau sobre ventas, comportamiento de los clientes y tendencias de rendimiento, alineando las visualizaciones con las estrategias internas de datos del negocio.
          tools:
            - { name: SQL, icon: devicon/microsoftsqlserver }
            - { name: Python, icon: devicon/python }
            - { name: Tableau, icon: custom/tableau }
          figures:
            - src: uploads/projects/company-data-dashboard.jpg
              alt: "Dashboard de Tableau: ingresos anuales de 2019 a 2024 con un pico de unos $143K en 2022, ingresos por artículo y distribución por artículo, con las unidades de aire acondicionado en 72% y los muebles en 26%"
              title: Ingresos por año y por artículo
              caption: Los ingresos anuales alcanzaron su punto más alto, unos $143K, en 2022, y las unidades de aire acondicionado generaron el 72% de todas las ventas.
            - src: uploads/projects/company-data-sales-map.jpg
              alt: Mapa de Tableau de los ingresos por ciudad en el sur de Texas, con los totales más altos en Zapata y McAllen
              title: Ingresos por ciudad
              caption: Ventas en el mapa del sur de Texas, donde Zapata y McAllen generaron los mayores ingresos.
---
