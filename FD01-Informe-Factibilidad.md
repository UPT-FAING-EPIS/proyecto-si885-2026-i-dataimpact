<center>

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERÍA**

**Escuela Profesional de Ingeniería de Sistemas**

**Proyecto *Dashboard de empleabilidad de los egresados de Ingeniería de Sistemas de la Universidad Privada de Tacna***

Curso: *Inteligencia de Negocios*

Docente: *{Nombre de Docente}*

Integrantes:

***{Apellidos y nombres del estudiante (código universitario)}***

**Tacna – Perú**

***2026***

</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

Sistema *Dashboard de Empleabilidad de Egresados EPIS-UPT*

Informe de Factibilidad

Versión *1.0*

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1.0|Equipo de Proyecto|EPIS UPT|EPIS UPT|22/08/2026|Versión Original Completa|

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

# **ÍNDICE GENERAL**

[1. Descripción del Proyecto](#_Toc52661346)

[2. Riesgos](#_Toc52661347)

[3. Análisis de la Situación actual](#_Toc52661348)

[4. Estudio de Factibilidad](#_Toc52661349)

[4.1 Factibilidad Técnica](#_Toc52661350)

[4.2 Factibilidad económica](#_Toc52661351)

[4.3 Factibilidad Operativa](#_Toc52661352)

[4.4 Factibilidad Legal](#_Toc52661353)

[4.5 Factibilidad Social](#_Toc52661354)

[4.6 Factibilidad Ambiental](#_Toc52661355)

[5. Análisis Financiero](#_Toc52661356)

[6. Conclusiones](#_Toc52661357)

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

**<u>Informe de Factibilidad</u>**

1. <span id="_Toc52661346" class="anchor"></span>**Descripción del Proyecto**

    1.1. **Nombre del proyecto**
    
    *Dashboard de empleabilidad de los egresados de Ingeniería de Sistemas de la Universidad Privada de Tacna*.

    1.2. **Duración del proyecto**
    
    La duración estimada para el desarrollo e implementación del proyecto es de **16 semanas** (4 meses), abarcando desde la recolección inicial de requerimientos y datos hasta el despliegue del dashboard y la capacitación a los usuarios clave de la Escuela Profesional.

    1.3. **Descripción**
    
    La empleabilidad de los egresados constituye un indicador fundamental para medir la pertinencia de la oferta académica universitaria y su consonancia con las cambiantes demandas del mercado laboral tecnológico. La Universidad Privada de Tacna (UPT), a través de mecanismos institucionales como el programa GPS Alumni y las iniciativas propias de la Escuela Profesional de Ingeniería de Sistemas (EPIS), realiza un seguimiento periódico a sus egresados para conocer sus trayectorias profesionales, dificultades de inserción laboral y necesidades de actualización tecnológica.

    Actualmente, la información recolectada se encuentra dispersa en múltiples fuentes (hojas de cálculo, bases de datos independientes del sistema académico y formulaciones de encuestas aisladas). Esto dificulta la consolidación de métricas estratégicas en tiempo real. 

    El proyecto consiste en desarrollar una aplicación analítica de Inteligencia de Negocios (BI) centrada en la empleabilidad de los egresados de Ingeniería de Sistemas. El sistema integrará, limpiará y procesará datos históricos e institucionales, permitiendo visualizar indicadores clave (KPIs) mediante gráficos interactivos, mapas de ubicación laboral y filtros dinámicos por cohorte, área de desempeño y rango salarial. Esto proporcionará una herramienta confiable para fundamentar la toma de decisiones académicas, el rediseño curricular y la reacreditación de la carrera.

    1.4. **Objetivos**

        1.4.1 Objetivo general
        Desarrollar un dashboard de Inteligencia de Negocios que permita analizar la empleabilidad de los egresados de Ingeniería de Sistemas de la Universidad Privada de Tacna, mediante indicadores que faciliten la interpretación de su situación laboral y apoyen la toma de decisiones.

        1.4.2 Objetivos Específicos
        - **Recopilar y organizar** la información disponible sobre los egresados de Ingeniería de Sistemas y sus características laborales a partir de fuentes institucionales y encuestas directas.
        - **Integrar y procesar** los datos relacionados con situación laboral, año de egreso, área de desempeño, ubicación geográfica laboral y tiempo de inserción en el mercado de trabajo.
        - **Definir indicadores clave de empleabilidad (KPIs)** que permitan medir con precisión la situación laboral y evolución profesional de los egresados.
        - **Diseñar e implementar** un dashboard interactivo mediante tecnologías BI que permita la exploración visual de datos mediante filtros dinámicos, gráficos y tablas multidimensionales.
        - **Identificar tendencias y patrones** sobre la velocidad de contratación, coincidencia entre la formación académica y el puesto desempeñado, y sectores de mayor demanda.
        - **Generar información estratégica** para la toma de decisiones de la Dirección de la Escuela Profesional de Ingeniería de Sistemas respecto a la actualización de planes de estudio y programas de seguimiento a graduados.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

2. <span id="_Toc52661347" class="anchor"></span>**Riesgos**

    A continuación se señalan los principales riesgos identificados que podrían impactar el desarrollo y éxito del proyecto, acompañados de su estrategia de mitigación:

    - **Riesgo 1: Incompletitud y dispersión de la información de egresados (Técnico)**
      - *Descripción*: Los registros históricos de GPS Alumni o encuestas previas pueden presentar valores nulos, inconsistencias en cargos o formatos no estandarizados.
      - *Mitigación*: Diseñar un proceso riguroso de ETL (Extracción, Transformación y Carga) con algoritmos de limpieza de datos y estandarización de taxonomías de cargos informáticos.

    - **Riesgo 2: Baja tasa de respuesta en nuevas encuestas (Operativo)**
      - *Descripción*: La falta de actualización de datos de contacto de los egresados puede limitar la muestra recolectada.
      - *Mitigación*: Utilizar canales diversificados (LinkedIn, correo institucional, grupos de egresados en redes sociales) y encuestas cortas y optimizadas para dispositivos móviles.

    - **Riesgo 3: Restricciones de privacidad y protección de datos (Legal)**
      - *Descripción*: Manejo irresponsable de datos sensibles de los egresados (salarios, empresas) que viole la legislación vigente en el Perú.
      - *Mitigación*: Aplicar anonimización de datos y cumplir estrictamente con la Ley N° 29733 de Protección de Datos Personales, garantizando el uso exclusivo con fines estadísticos agregados.

    - **Riesgo 4: Subutilización del dashboard por los tomadores de decisiones (Adopción)**
      - *Descripción*: Que la Dirección o el comité de calidad de la EPIS no incorpore el dashboard en sus reuniones periódicas.
      - *Mitigación*: Involucrar a las autoridades académicas en la etapa de definición de KPIs y realizar talleres de capacitación orientados a la interpretación de los reportes.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

3. <span id="_Toc52661348" class="anchor"></span>**Análisis de la Situación actual**

    3.1. **Planteamiento del problema**
    
    En la actualidad, el análisis de la empleabilidad de los graduados de Ingeniería de Sistemas en la Universidad Privada de Tacna se realiza de forma manual y desarticulada. A pesar de contar con iniciativas como GPS Alumni y cuestionarios aplicados en coordinaciones académicas, la información se almacena en hojas de cálculo heterogéneas sin consolidación en una base de datos centralizada o Data Mart analítico.

    Esta carencia de visualización integrada impide responder con agilidad a interrogantes estratégicas como: ¿Qué porcentaje de egresados labora en su área de especialidad? ¿Cuál es el tiempo medio de inserción laboral tras la egresamiento? ¿Qué competencias o tecnologías son más requeridas en el mercado regional y nacional? La falta de visibilidad periódica condiciona las decisiones sobre la actualización de los planes de estudio y dificulta el sustento de evidencias durante los procesos de acreditación universitaria (ICACIT/SINEACE).

    3.2. **Consideraciones de hardware y software**
    
    Se evalúa la factibilidad tecnológica considerando la infraestructura actual de la UPT y los componentes recomendados para la solución BI:

    - **Hardware alcanzable y requerido**:
      - *Estación de desarrollo e integración*: Computadoras con procesador Intel Core i5/i7 o AMD Ryzen 5/7, mínimo 16 GB de RAM y almacenamiento SSD de 512 GB.
      - *Servidor de alojamiento / BI*: Servidor virtual local de la UPT o instancia cloud básica (AWS/Azure/Power BI Service) para despliegue web.

    - **Software evaluado e seleccionado**:
      - *Motor de Base de Datos / Data Warehouse*: PostgreSQL o Microsoft SQL Server (existente en laboratorios EPIS).
      - *Procesamiento ETL*: Lenguaje Python (Pandas/SQLAlchemy) o herramientas integradas como Power Query / SQL Server Integration Services (SSIS).
      - *Visualización y BI*: Microsoft Power BI Desktop / Service o Framework Web interactivo (Streamlit / React + Chart.js) por su flexibilidad, bajo costo de licenciamiento educativo y capacidad interactiva.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

4. <span id="_Toc52661349" class="anchor"></span>**Estudio de Factibilidad**

    El estudio de factibilidad evaluó la viabilidad del proyecto en seis dimensiones clave para asegurar el cumplimiento de los objetivos institucionales de la EPIS-UPT. El estudio fue coordinado con la Dirección de Escuela y contó con la revisión de especialistas del área de Ingeniería de Software e Inteligencia de Negocios.

    4.1. <span id="_Toc52661350" class="anchor"></span>**Factibilidad Técnica**
    
    El análisis técnico demuestra que la Escuela Profesional de Ingeniería de Sistemas dispone de la infraestructura de cómputo y el personal con las competencias requeridas en gestión de datos, bases de datos relacionales y herramientas BI. 

    Las tecnologías seleccionadas (Power BI / Python / PostgreSQL) son de amplio dominio en la carrera y no requieren la adquisición de hardware especializado complejo. La infraestructura de red y servidores de la UPT soporta la conectividad web requerida para publicar y consultar los dashboards interactivos en navegadores convencionales. Por lo tanto, el proyecto es **Técnicamente Factible**.

    4.2. <span id="_Toc52661351" class="anchor"></span>**Factibilidad Económica**
    
    El análisis económico demuestra que la inversión requerida es moderada y plenamente asumible en el marco de proyectos de desarrollo académico e institucional BI.

        4.2.1. Costos Generales
        Gastos en material de oficina, suministros de escritorio y depreciación de equipos existentes:
        
        | Concepto | Cantidad | Costo Unitario (S/) | Costo Total (S/) |
        | :--- | :-: | :-: | :-: |
        | Material de escritorio y papelería | 1 Lote | 150.00 | 150.00 |
        | Uservicios de impresión y empastado | 1 Lote | 100.00 | 100.00 |
        | Equipos de cómputo (Depreciación uso 4 meses) | 3 Unidades | 300.00 | 900.00 |
        | **Total Costos Generales** | | | **S/ 1,150.00** |

        4.2.2. Costos operativos durante el desarrollo
        Servicios básicos necesarios durante las 16 semanas del proyecto:

        | Servicio | Meses | Costo Mensual (S/) | Costo Total (S/) |
        | :--- | :-: | :-: | :-: |
        | Energía eléctrica proporcional | 4 | 120.00 | 480.00 |
        | Conexión a Internet dedicada | 4 | 150.00 | 600.00 |
        | Renta/Uso de espacio físico laboral | 4 | 200.00 | 800.00 |
        | **Total Costos Operativos** | | | **S/ 1,880.00** |

        4.2.3. Costos del ambiente
        Herramientas de software, licenciamiento y servidores de alojamiento:

        | Componente | Tipo de Licencia | Costo (S/) |
        | :--- | :--- | :-: |
        | PostgreSQL / Python | Open Source | 0.00 |
        | Power BI Desktop | Gratuito (Educativo) | 0.00 |
        | Servidor Web / Power BI Service (Licencia Pro 4 meses) | Suscripción | 240.00 |
        | Dominio e infraestructura institucional UPT | Existente | 0.00 |
        | **Total Costos de Ambiente** | | **S/ 240.00** |

        4.2.4. Costos de personal
        Gastos asociados al equipo de trabajo estimado para el desarrollo del proyecto (16 semanas, 10 hrs/semana por rol):

        | Rol | Horas Totales | Tarifa/Hora (S/) | Costo Total (S/) |
        | :--- | :-: | :-: | :-: |
        | Jefe de Proyecto / Arquitecto BI | 80 | 35.00 | 2,800.00 |
        | Ingeniero de Datos (ETL) | 120 | 25.00 | 3,000.00 |
        | Desarrollador BI / Dashboard | 120 | 25.00 | 3,000.00 |
        | Analista de Calidad / Pruebas | 60 | 20.00 | 1,200.00 |
        | **Total Costos de Personal** | **380** | | **S/ 10,000.00** |

        4.2.5. Costos totales del desarrollo del sistema
        Consolidación del presupuesto requerido:

        | Categoría de Costo | Monto (S/) | Porcentaje (%) |
        | :--- | :-: | :-: |
        | Costos Generales | 1,150.00 | 8.67% |
        | Costos Operativos | 1,880.00 | 14.17% |
        | Costos del Ambiente | 240.00 | 1.81% |
        | Costos de Personal | 10,000.00 | 75.35% |
        | **COSTO TOTAL DEL PROYECTO** | **S/ 13,270.00** | **100.00%** |

        *Forma de Pago / Financiamiento*: Asumido bajo el presupuesto de investigación y desarrollo de la Escuela Profesional / Fondo de Proyectos de la UPT, distribuido en 3 entregables clave (30% al aprobar la factibilidad, 40% al completar el ETL y 30% al desplegar el Dashboard final).

    4.3. <span id="_Toc52661352" class="anchor"></span>**Factibilidad Operativa**
    
    El proyecto cuenta con un alto grado de aceptabilidad por parte de las autoridades y miembros de la comunidad universitaria.
    - **Beneficios del producto**: Otorga visibilidad inmediata de la empleabilidad, optimiza el tiempo de generación de reportes institucionales de días a segundos y sustenta las evidencias requeridas por agencias acreditadoras (ICACIT).
    - **Interesados (Stakeholders)**:
      - *Dirección de la EPIS*: Usuario principal para la toma de decisiones y planeación estratégica.
      - *Comité de Acreditación*: Beneficiario de métricas confiables de egresados.
      - *Programa GPS Alumni UPT*: Entidad que alimentará y aprovechará la actualización de datos.
      - *Egresados y Estudiantes*: Beneficiados indirectos mediante la mejora continua de la calidad educativa.

    4.4. <span id="_Toc52661353" class="anchor"></span>**Factibilidad Legal**
    
    El proyecto no presenta conflicto con la legislación vigente en el Perú ni con normativas internas de la universidad. Cumple rigurosamente con la **Ley N° 29733 (Ley de Protección de Datos Personales)** y su reglamento, mediante la disociación y anonimización de la información de los egresados en las vistas públicas. Todo el software utilizado cuenta con licencias Open Source o educativas legítimas.

    4.5. <span id="_Toc52661354" class="anchor"></span>**Factibilidad Social**
    
    Socialmente, el dashboard contribuye a fortalecer el vínculo universidad-sociedad-empresa. Permite orientar a los futuros graduados sobre las áreas laborales con mayor demanda en la región de Tacna y el país, fomentando una inserción laboral más efectiva y ética.

    4.6. <span id="_Toc52661355" class="anchor"></span>**Factibilidad Ambiental**
    
    El proyecto impulsa una política de "Papel Cero" al sustituir informes impresos tradicionales por tableros digitales dinámicos. El consumo energético de la infraestructura cloud/local seleccionada cumple con estándares ecoeficientes de procesamiento informático.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

5. <span id="_Toc52661356" class="anchor"></span>**Análisis Financiero**

    El análisis financiero evalúa la viabilidad cualitativa y cuantitativa del proyecto a un horizonte de evaluación de 3 años, considerando el ahorro de costos operativos institucionales y el aporte de valor agregado.

    5.1. **Justificación de la Inversión**

        5.1.1. Beneficios del Proyecto
        - **Beneficios Tangibles**:
          - Reducción del tiempo de elaboración de reportes de seguimiento de egresados de 80 horas/año a 5 horas/año (Ahorro proyectado de S/ 4,500.00 anuales en horas de personal administrativo y docente).
          - Eliminación total de impresiones y papelería física en encuestas y reportes (Ahorro de S/ 1,200.00 anuales).
          - Evitación de costos por contratación de consultorías externas de evaluación de empleabilidad (Ahorro de S/ 8,000.00 bianuales).
          - *Total Beneficios Tangibles Anuales Estimados*: **S/ 9,700.00 / año**.

        - **Beneficios Intangibles**:
          - Mejora de la imagen institucional de la EPIS-UPT ante la comunidad académica y laboral.
          - Disponibilidad oportuna de información confiable para procesos de Reacreditación ICACIT.
          - Capacidad de adaptar oportunamente el plan de estudios a tendencias tecnológicas emergentes.

        5.1.2. Criterios de Inversión
        Para el flujo financiero se considera una Inversión Inicial de **S/ 13,270.00**, un costo de mantenimiento anual de **S/ 1,500.00**, y beneficios tangibles de **S/ 9,700.00** anuales durante 3 años, con un Costo de Oportunidad del Capital (COK) del **10%**.

        5.1.2.1. Relación Beneficio/Costo (B/C)
        - Valor Presente de los Beneficios (VPB): S/ 24,122.46
        - Valor Presente de los Costos (VPC): S/ 17,000.23
        - **Relación B/C = 24,122.46 / 17,000.23 = 1.42**
        *Criterio*: Al ser B/C > 1 (1.42), por cada sol invertido se generan S/ 1.42 en beneficios, por lo que el proyecto **es financieramente aceptable**.

        5.1.2.2. Valor Actual Neto (VAN)
        - **VAN = VPB - VPC = S/ 24,122.46 - S/ 17,000.23 = S/ 7,122.23**
        *Criterio*: Al ser el **VAN > 0** (S/ 7,122.23), el proyecto genera valor económico positivo para la institución y justifica plenamente la inversión.

        5.1.2.3 Tasa Interna de Retorno (TIR)
        - **TIR Calculada = 32.45%**
        - Costo de Oportunidad de Capital (COK) = 10.00%
        *Criterio*: Al ser la **TIR (32.45%) significativamente superior al COK (10.00%)**, se concluye que el proyecto posee una alta rentabilidad y eficiencia financiera.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

6. <span id="_Toc52661357" class="anchor"></span>**Conclusiones**

    - El proyecto **"Dashboard de empleabilidad de los egresados de Ingeniería de Sistemas de la UPT"** es **Técnica, Económica, Operativa, Legal, Social y Ambientalmente Factible**.
    - La factibilidad técnica se respalda en el uso de herramientas modernas de Business Intelligence (Power BI / Python / PostgreSQL) ampliamente soportadas en el entorno informático de la EPIS.
    - El análisis financiero demuestra la rentabilidad del proyecto con un **VAN de S/ 7,122.23**, una **TIR del 32.45%** y una relación **Beneficio/Costo de 1.42**, superando ampliamente las exigencias del costo de oportunidad.
    - Operativamente, el sistema proporcionará un valor estratégico inestimable para la Dirección de Escuela, facilitando la toma de decisiones informadas, la actualización curricular y la sustentación de evidencias de empleabilidad ante entidades acreditadoras.
