# <center>Informe del Trabajo Final</center>

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>1ASI0728 - Arquitecturas de Software Emergentes - 7291</strong><br>
    <strong>Profesor: Royer Edelwer Rojas Malasquez </strong><br>
    <br>INFORME
</p>

<center>

#### Startup: **Actualizar**

#### Product: **Actualizar**

</center>

## Team  Members:

<div align="center">

|               Member                |    Code    |
| :---------------------------------: | :--------: |
| Herrera Aguirre, Fabia Alejandra  | U202219422 |
| Linares Tejada, Leonardo Felix Jesus | U202211168 |
| Oneglio de Paz, Beth Shantal  | U202213423 |
| Salgado Luna, Fernando Brian  | U202212023 |
| Sosa Colca, Angelo Rodolfo  | U202212077 |

</div>

<div style="page-break-after: always;"></div>

## Contenido

**Tabla de contenidos**

| Tabla de contenidos                                                                                                 |
| ------------------------------------------------------------------------------------------------------------------- |
| [Capítulo I: Introducción](#capítulo-i-introducción)                                                                |
| [1.1. Startup Profile](#11-startup-profile)                                                                         |
| [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)                                                  |
| [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)                                |
| [1.2. Solution Profile](#12-solution-profile)                                                                       |
| [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)                                              |
| [1.2.2. Lean UX Process](#122-lean-ux-process)                                                                      |
| [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)                                             |
| [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)                                                           |
| [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)                                       |
| [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)                                                                     |
| [1.3. Segmentos objetivo](#13-segmentos-objetivo)                                                                   |
| [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)                 |
| [2.1. Competidores](#21-competidores)                                                                               |
| [2.1.1. Análisis competitivo](#211-análisis-competitivo)                                                            |
| [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)            |
| [2.2. Entrevistas](#22-entrevistas)                                                                                 |
| [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)                                                          |
| [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)                                                      |
| [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)                                                      |
| [2.3. Needfinding](#23-needfinding)                                                                                 |
| [2.3.1. User Personas](#231-user-personas)                                                                          |
| [2.3.2. User Task Matrix](#232-user-task-matrix)                                                                    |
| [2.3.3. Empathy Mapping](#233-empathy-mapping)                                                                      |
| [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)                                                        |
| [2.4. Ubiquitous Language](#24-ubiquitous-language)                                                                 |
| [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)                                |
| [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)                                                            |
| [3.2. User Stories](#32-user-stories)                                                                               |
| [3.3. Impact Mapping](#33-impact-mapping)                                                                           |
| [3.4. Product Backlog](#34-product-backlog)                                                                         |
| [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)                        |
| [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)                         |
| [4.1.1. Design Purpose](#411-design-purpose)                                                                        |
| [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)                                        |
| [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)           |
| [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)                                           |
| [4.1.2.3. Constraints](#4123-constraints)                                                                           |
| [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)                                          |
| [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)                                        |
| [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)                        |
| [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)                               |
| [4.2.1. EventStorming](#421-eventstorming)                                                                          |
| [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)                                              |
| [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)                                          |
| [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)                                                    |
| [4.2.5. Context Mapping](#425-context-mapping)                                                                      |
| [4.3. Software Architecture](#43-software-architecture)                                                             |
| [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)        |
| [4.3.1. Software Architecture Context Level Diagrams](#431-software-architecture-context-level-diagrams)            |
| [4.3.2. Software Architecture Container Level Diagrams](#432-software-architecture-container-level-diagrams)        |
| [4.3.3. Software Architecture Deployment Diagrams](#433-software-architecture-deployment-diagrams)                  |









# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

SafeVision es una startup dedicada a mejorar la seguridad de los conductores en carretera mediante un sistema de inteligencia artificial que detecta en tiempo real signos de somnolencia. A través de una cámara en la cabina y una aplicación móvil, se emiten alertas inmediatas para prevenir accidentes. Además, los datos son procesados en la nube, lo que permite a las empresas de transporte acceder a reportes y monitorear el estado de sus conductores de forma continua.

###  Misión:
Contribuir a la reducción de accidentes de tránsito en carreteras mediante el desarrollo de soluciones tecnológicas basadas en inteligencia artificial que permitan monitorear el estado de los conductores en tiempo real, promoviendo la seguridad, el bienestar y la responsabilidad en la conducción.

### Visión:
Convertirnos en una startup líder en el Perú en soluciones inteligentes para la seguridad vial, reconocida por nuestra innovación tecnológica y por nuestro aporte en la creación de carreteras más seguras, donde la tecnología y la prevención trabajen juntas para salvar vidas.


### 1.1.2. Perfiles de integrantes del equipo

| Miembros del equipo                  | Código Estudiante | Carrera                | Acerca de | Foto |
|-------------------------------------|------------------|-----------------------|---------------------------------------------------------------|------|
| Herrera Aguirre Fabia Alejandra     | u2022xxxxx       | Ingeniería de Software |  | <img src="" width="80"> |
| Linares Tejada Leonardo Félix Jesús | u2022xxxxx       | Ingeniería de Software |  | <img src="" width="80"> |
| Oneglio De Paz Beth Shantal         | u2022xxxxx       | Ingeniería de Software |  | <img src="" width="80"> |
| Salgado Luna, Fernando Brian        | u202212023        | Ingeniería de Software | Soy Fernando Salgado, tengo 20 años y me apasiona la tecnología. Tengo experiencia en desarrollo frontend y backend, trabajando con lenguajes como C#, Java y otros. Disfruto resolviendo problemas y buscando soluciones prácticas que contribuyan a los proyectos en los que participo. | <img src="https://i.imgur.com/ZMT41YU.jpeg" width="80"> |
| Sosa Colca Angello Rodolfo          | u2022xxxxx       | Ingeniería de Software |  | <img src="" width="80"> |



## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
#### Uso de la técnica The 5'W's w Y 2'H's

| LAS 5W y 2H | Pregunta                                                | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ----------- | ------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| What?       | ¿Cuál es el problema?                                   | El problema se centra en la somnolencia al volante, que es una de las principales causas de accidentes de tránsito en el Perú, especialmente en viajes de larga distancia e interprovinciales. Los conductores presentan parpadeos frecuentes, bostezos o cabeceos debido al cansancio, lo que disminuye su capacidad de reacción. La falta de herramientas tecnológicas que detecten estos signos en tiempo real incrementa el riesgo de siniestros, con consecuencias humanas, económicas y legales. |
| When?       | ¿Cuándo ocurre el problema?                              | Se presenta principalmente durante trayectos prolongados, en horarios nocturnos o de madrugada, y en turnos extendidos de conducción donde la fatiga se acumula. También puede darse en cualquier momento en que el conductor haya tenido pocas horas de descanso previo. |
| Where?      | ¿Dónde ocurre el problema?                               | El problema se observa en carreteras nacionales e interprovinciales del Perú, donde se realizan viajes largos y de varias horas. Ocurre en la etapa de conducción, cuando el conductor debe mantener concentración constante para evitar accidentes. |
| Who?        | ¿A quién afecta el problema?                             | Afecta a conductores de transporte interprovincial, conductores particulares que viajan por carretera y a las empresas de transporte responsables de la seguridad de sus trabajadores y pasajeros. No necesariamente está relacionado con las habilidades, sino con la fatiga física y mental, incluso en conductores experimentados. |
| Why?        | ¿Por qué sucede el problema?                              | Ocurre porque los viajes prolongados y la falta de descanso adecuado generan cansancio extremo, disminuyendo reflejos, concentración y capacidad de reacción. La ausencia de sistemas de monitoreo en tiempo real impide alertar al conductor o a las empresas para tomar medidas preventivas. |
| How?        | ¿Cómo se diferencia el problema del estado normal?       | En un estado óptimo, el conductor se encuentra alerta y con plena capacidad de reacción. El problema aparece cuando, por cansancio, se reduce la atención, aumentando la probabilidad de accidentes. La situación se agrava por la falta de mecanismos automáticos que detecten señales de somnolencia y emitan alertas. |
| How Much?   | ¿Con qué frecuencia o en qué cantidad se utilizará nuestro producto? | SafeVision se usará constantemente en viajes interprovinciales y de larga distancia, donde la somnolencia es una de las principales causas de accidentes. Los incidentes por fatiga generan pérdidas económicas, legales y humanas. La inversión en cámaras, sensores y software se recupera mediante un modelo de suscripción mensual por flota o conductor, ofreciendo alertas y reportes en tiempo real para prevenir accidentes. |

                               
**Objetivos:**

- Identificar de manera oportuna señales de somnolencia en los conductores.  
- Emitir alertas inmediatas al conductor para prevenir accidentes.  
- Brindar a las empresas de transporte reportes detallados y métricas de seguridad sobre sus conductores.  

**Restricciones:**

- Se requiere conexión a internet para la transmisión y procesamiento de datos en la nube.  
- La efectividad del reconocimiento facial puede variar según la iluminación o la posición de la cámara.  
- El alcance inicial se limita a viajes interprovinciales y de larga distancia, sin considerar aún transporte urbano.  

### 1.2.2. Lean UX Process

El proceso Lean UX nos permite diseñar y validar soluciones centradas en el usuario, enfocándonos en crear valor de manera ágil y eficiente. En esta sección se describen los problemas principales que enfrentan los usuarios, las suposiciones de negocio y de usuario, así como las hipótesis que guiarán el desarrollo del sistema SafeVision. Este enfoque asegura que cada decisión de diseño esté basada en evidencia y en la validación temprana con los usuarios finales.

#### 1.2.2.1. Lean UX Problem Statements

En nuestro contexto, una gran parte de los accidentes en carretera está relacionada con la fatiga y la somnolencia de los conductores, especialmente en viajes nocturnos o de larga distancia. Estos accidentes generan pérdidas humanas y económicas significativas, además de afectar la seguridad vial en general.
En los últimos años, se ha identificado que los accidentes por somnolencia continúan siendo frecuentes en rutas interprovinciales, a pesar de campañas de concientización y regulaciones de descanso obligatorio, lo que evidencia la necesidad de herramientas tecnológicas que monitoreen el estado del conductor en tiempo real.
### **¿Cómo puede SafeVision, siendo utilizado por los conductores profesionales y supervisores de flotas, detectar señales de fatiga y somnolencia para prevenir accidentes y mejorar la seguridad vial de manera efectiva?**

**Problema:**
Los conductores presentan signos de cansancio como parpadeos frecuentes, cabeceos o bostezos, que muchas veces pasan desapercibidos hasta que ocurre un siniestro. Actualmente no existen soluciones accesibles y tecnológicas que puedan alertarlos a tiempo ni herramientas para que las empresas de transporte puedan supervisar de forma efectiva el estado de sus choferes.

**Impacto:**
Nuestra propuesta busca reducir los accidentes relacionados con la fatiga al detectar en tiempo real señales de somnolencia mediante visión artificial y alertar al conductor de manera inmediata. Además, proporcionará a las empresas reportes sobre la condición de sus choferes, lo que permitirá tomar medidas preventivas y fortalecer la seguridad en carretera.


#### 1.2.2.2. Lean UX Assumptions

#### Business Outcomes

- **Reducción de accidentes por fatiga:** 20% menos accidentes en empresas de transporte tras 6 meses de uso.  
- **Adopción de la solución:** Al menos el 60% de las flotas participantes en el piloto adoptarán la plataforma.  
- **Mejora en la percepción de seguridad:** Incremento del 40% en la sensación de seguridad por parte de los conductores.  
- **Fortalecimiento de la reputación empresarial:** Mejora en la confianza y reputación de las empresas de transporte que implementen el sistema.  

---

#### User Assumptions

**¿Quién es el usuario?**  
- Conductores profesionales de buses interprovinciales y camiones de carga.  
- Gerentes o supervisores de flotas responsables de la seguridad de los conductores.  

**¿Dónde entra nuestro producto en su trabajo o su vida?**  
- **Para los conductores:** como un asistente digital dentro de la cabina que monitorea su estado de alerta durante la conducción.  
- **Para los gerentes/supervisores:** como una herramienta de monitoreo y reporte en la nube que permite tomar decisiones preventivas y gestionar riesgos en tiempo real.  

**¿Cuál es el problema que nuestro producto soluciona?**  
- Detecta signos de fatiga y somnolencia que pueden pasar desapercibidos hasta que ocurren accidentes.  
- Previene accidentes, disminuye riesgos y ayuda a cumplir normas de seguridad vial.  

**¿Cómo y cuándo nuestro producto es usado?**  
- Durante la conducción, especialmente en viajes largos, nocturnos o interprovinciales.  
- El conductor recibe alertas inmediatas en la cabina; el supervisor revisa reportes periódicos o en tiempo real según sea necesario.  

**¿Qué características son importantes?**  
- Precisión en la detección de fatiga (parpadeos, bostezos, cabeceos).  
- Alertas claras y no invasivas para el conductor.  
- Reportes confiables y accesibles para los supervisores.  
- Interfaz sencilla, intuitiva y segura para todos los usuarios.  

---

#### User Outcomes & Benefits

**Para los conductores:**  
- Alertas oportunas que previenen accidentes y aumentan la confianza durante viajes largos.  
- Se espera que al menos el 70% de los conductores perciba mayor seguridad y mantenga el uso activo de la aplicación.  

**Para los gerentes o supervisores:**  
- Reportes confiables que facilitan la toma de decisiones y permiten reducir costos por accidentes.  
- Se proyecta que al menos el 60% de los supervisores use regularmente los reportes para gestionar riesgos.  

**Para la sociedad:**  
- Disminución de accidentes en carreteras y mayor seguridad vial.  
- Reducción estimada del 20% de los incidentes relacionados con fatiga en rutas monitoreadas tras los primeros 6 meses de implementación.  

---

#### Business Assumptions

- Las empresas de transporte buscan soluciones tecnológicas que reduzcan accidentes e indemnizaciones.  
- Los conductores aceptarán el uso de cámaras si se garantiza la privacidad de los datos.  
- El modelo de negocio basado en suscripción por flota es más atractivo que un pago único elevado.  

#### 1.2.2.3. Lean UX Hypothesis Statements

Para la elaboración de los Hypothesis Statements se utilizó el formato Lean UX: [We believe that], [This will achieve], [We will have demonstrated this when]. Este enfoque permite conectar directamente las funcionalidades del producto con los resultados esperados y definir cómo se validará cada hipótesis con evidencia concreta.

#### Hipótesis 1
Creemos que si el sistema detecta signos de somnolencia y distracción con al menos un 85 % de precisión, incluyendo parpadeos frecuentes, bostezos y cabeceos, esto logrará mejorar significativamente la seguridad de los conductores durante viajes largos y nocturnos, y lo sabremos cuando el número de incidentes por fatiga en rutas monitoreadas se reduzca en un 20 % y se registre una disminución de comportamientos de riesgo detectados por el sistema.

#### Hipótesis 2
Creemos que si los reportes en la nube ofrecen datos claros, gráficos de fácil interpretación y alertas organizadas por nivel de riesgo, esto logrará que los gerentes y supervisores confíen en la solución para tomar decisiones preventivas, y lo sabremos cuando al menos el 60 % de los gerentes de transporte revise semanalmente los reportes y actúe en base a ellos para reducir riesgos de fatiga.

#### Hipótesis 3
Creemos que si la aplicación móvil alerta al conductor con mensajes claros, auditivos y visuales, no invasivos pero efectivos, esto logrará que los conductores reaccionen oportunamente ante señales de somnolencia y mantengan niveles óptimos de atención, y lo sabremos cuando al menos el 70 % de los conductores mantenga el uso activo de la aplicación durante sus viajes nocturnos o de larga distancia.

#### Hipótesis 4
Creemos que si se implementan alertas personalizables según el nivel de fatiga y el comportamiento individual de cada conductor, esto logrará aumentar la efectividad de las notificaciones y la adherencia al sistema, y lo sabremos cuando los conductores respondan correctamente al 90 % de las alertas emitidas y se observe una disminución de episodios críticos de somnolencia.

#### Hipótesis 5
Creemos que si se generan patrones de riesgo agregados y se presentan visualmente en un panel centralizado para supervisores, esto logrará que los gerentes identifiquen proactivamente a los conductores en riesgo y puedan planificar medidas preventivas, y lo sabremos cuando se reduzcan los incidentes recurrentes por fatiga en rutas monitoreadas en al menos un 15 % adicionales y se mejore la eficiencia de las decisiones de supervisión.


#### 1.2.2.4. Lean UX Canvas

<div style="text-align: center;">
  <img src="https://i.imgur.com/QWUDlJj.jpeg" alt="Lean Ux Canva" width="100%" />
</div>

## 1.3. Segmentos objetivo

El sistema está enfocado en los principales actores que enfrentan directamente la problemática de la somnolencia y la fatiga en carretera:  

1. **Conductores profesionales (buses interprovinciales y camiones de carga)**  
   Este segmento está compuesto por personas de entre 25 y 55 años que realizan jornadas prolongadas, a menudo en horarios nocturnos o de madrugada, incrementando la probabilidad de somnolencia y distracción al volante. Su labor requiere mantener un nivel constante de concentración durante viajes largos e interprovinciales, y son directamente afectados por la fatiga, lo que hace necesario un sistema que les emita alertas oportunas para prevenir accidentes y mejorar su seguridad durante la conducción.  

2. **Gerentes o supervisores de flotas de transporte**  
   Este grupo incluye personas de entre 30 y 55 años responsables de la seguridad y operación de los conductores en viajes interprovinciales o de larga distancia. Su rol implica monitorear el estado de alerta de los conductores mediante reportes en tiempo real, tomar decisiones preventivas para reducir riesgos y garantizar el cumplimiento de normas de seguridad, con el objetivo de disminuir accidentes, mejorar la gestión de riesgos y optimizar la operación diaria de la flota.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

<table>
    <thead>
    <tr>
    <th colspan=6>Competitive Analysis Landscape</th>
    </tr>
        <tr>
    <th colspan=6>¿Por qué llevar a cabo este análisis?</th>
    </tr>
        <tr>
    <th colspan=6>Para dar a conocer a los competidores que se presentan en nuestra Startup.</th>
    </tr>
        <tr>
            <th colspan=2></th>
            <th>SafeVision<br><img src="https://i.imgur.com/Mw3mnly.png" alt="SafeVision" width="80"></th>
            <th>Anka Perú<br><img src="https://i.imgur.com/HAQb3D9.png" alt="Anka Perú" width="80"></th>
            <th>Bonitel<br><img src="https://i.imgur.com/qMp8njG.png" alt="Bonitel" width="80"></th>
            <th>Risk Control<br><img src="https://i.imgur.com/8gZv4IB.png" alt="Risk Control" width="80"></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=2 align="center">Perfil</td>
            <td align="center">Overview</td>
            <td align="center">Plataforma basada en IA que usa cámara en cabina para analizar en tiempo real signos de fatiga. Envía alertas inmediatas al conductor y genera reportes en la nube para las empresas.</td>
            <td  align="center">Solución que combina cámara en cabina con sensores de vibración en el asiento, GPS y monitoreo en la nube para detectar fatiga y distracción.</td>
            <td  align="center">Ofrece sensores DMS (Driver Monitoring System) y ADAS que identifican parpadeos, bostezos y distracciones. Se integra con sistemas GPS para control de flotas.</td>
            <td align="center">Sistema integral con cámaras 360° que detectan múltiples riesgos: fatiga, uso de celular, humo, distracciones. Envía alertas al conductor y a un centro de control.</td>
        </tr>
        <tr>
            <td align="center">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
            <td align="center">Solución accesible y adaptada al contexto peruano, bajo costo de implementación, integración con app móvil y reportes en la nube.</td>
            <td align="center">Alta precisión con hardware adicional (cámara + vibración + GPS), ideal para transporte formal.</td>
            <td align="center">Alta precisión en la detección gracias a sensores DMS (Driver Monitoring System) y la integración con GPS para rastreo en tiempo real. Es una solución tecnológica avanzada ya validada en el mercado.</td>
            <td align="center">Cobertura amplia que no solo mide fatiga, sino también otros riesgos dentro del vehículo, convirtiéndose en una solución integral de seguridad vehicular.</td>
        </tr>
        <tr>
            <td rowspan= 5 align="center">Perfil de Marketing</td>
            <td align="center">Mercado Objetivo</td>
            <td align="center">Empresas de transporte interprovincial y de carga en Perú, conductores de larga distancia.</td>
            <td align="center">Empresas de transporte formal con flotas medianas y grandes.</td>
            <td align="center">Empresas con flotas que ya cuentan con infraestructura GPS y buscan complementarla.</td>
            <td align="center">Empresas corporativas de transporte interprovincial, de carga y minería.</td>
        </tr>
        <tr>
            <td align="center">Estrategias de Marketing</td>
            <td align="center">Alianzas con transportistas locales, campañas de concientización sobre seguridad vial, pruebas piloto con empresas medianas.</td>
            <td align="center">Paquetes corporativos y convenios con empresas establecidas.</td>
            <td align="center">Venta directa de hardware a empresas formales y distribución a través de partners tecnológicos.</td>
            <td align="center">Ofertas premium dirigidas a contratos corporativos.</td>
        </tr>
        <tr>
            <td align="center">Productos & servicios</td>
            <td align="center">Cámara en cabina + aplicación móvil + plataforma en la nube.</td>
            <td align="center">Cámara + vibración en asiento + GPS + nube.</td>
            <td align="center">Sensor DMS + ADAS + integración GPS.</td>
            <td align="center">Cámaras 360° + alertas múltiples + monitoreo en la nube.</td>
        </tr>
        <tr>
            <td align="center">Precios & Costos</td>
            <td align="center">Modelo de suscripción accesible con baja inversión inicial.</td>
            <td align="center">Inversión inicial media-alta, dirigido a empresas con presupuesto.</td>
            <td align="center">Alto costo, ya que requiere hardware especializado y mantenimiento.</td>
            <td align="center">Costo elevado, con instalación especializada y planes corporativos.</td>
        </tr>
        <tr>
            <td align="center">Canales de distribución (Web y/o móvil)</td>
            <td align="center">Web y app móvil.</td>
            <td align="center">Plataforma web y equipos instalados en cabina.</td>
            <td align="center">Web, distribuidores especializados en transporte.</td>
            <td align="center">Web y ventas directas a empresas.</td>
        </tr>
        <tr>
            <td rowspan= 4 align="center">Análisis SWOT</td>
            <td align="center">Fortalezas</td>
            <td align="center">Accesible, adaptado al mercado local, integración móvil en tiempo real, reportes en la nube.</td>
            <td align="center">Solución robusta con integración de múltiples tecnologías.</td>
            <td align="center">Alta precisión, integración con sistemas existentes.</td>
            <td align="center">Amplio rango de detección de riesgos, alta confiabilidad.</td>
        </tr>
        <tr>
            <td align="center">Debilidades</td>
            <td align="center">Startup emergente con poco reconocimiento de marca.</td>
            <td align="center">Costoso para empresas pequeñas o informales.</td>
            <td align="center">Elevado costo y dependencia de infraestructura previa.</td>
            <td align="center">Alto costo y complejidad de implementación.</td>
        </tr>
        <tr>
            <td align="center">Oportunidades</td>
            <td align="center">Mayor necesidad de seguridad vial en Perú; formalización del transporte.</td>
            <td align="center">Expansión a transporte de carga pesada.</td>
            <td align="center">Mayor adopción en empresas que buscan profesionalizar sus flotas.</td>
            <td align="center">Creciente interés en sistemas integrales para seguridad vial.</td>
        </tr>
        <tr>
            <td align="center">Amenazas</td>
            <td align="center">Competidores con más capital; resistencia al cambio en transporte informal.</td>
            <td align="center">Nuevas startups con soluciones más accesibles y fáciles de implementar.</td>
            <td align="center">Soluciones más simples, móviles y baratas.</td>
            <td align="center">Startups con soluciones más específicas, rápidas y accesibles.</td>
        </tr>
    </tbody>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

#### Estrategias Competitivas de SafeVision

#### A) Diferenciación de Servicios

Para posicionarse como la solución más accesible y adaptada al contexto peruano, SafeVision utilizará cámaras convencionales y smartphones sin necesidad de hardware adicional costoso, lo que facilita su adopción. Además, se promocionará la facilidad de uso y la rápida implementación como principales ventajas competitivas frente a sistemas más complejos o importados.

#### B) Calidad Constante

La fiabilidad del sistema será el factor clave para generar confianza en transportistas y conductores. Para lograrlo, se realizarán pilotos con flotas interprovinciales recopilando métricas sobre la reducción de incidentes, y se implementarán actualizaciones periódicas basadas en el feedback real de los usuarios, asegurando un servicio confiable y en constante mejora.

#### C) Precios Competitivos

SafeVision se ofrecerá como una alternativa más económica frente a sistemas importados de alto costo. Se implementará un modelo de suscripción flexible orientado a empresas pequeñas y medianas, y se desarrollarán campañas de marketing que comparen precios mostrando los ahorros que las flotas pueden obtener al elegir SafeVision frente a la competencia.

#### D) Servicio al Cliente de Calidad

El soporte cercano marcará la diferencia frente a soluciones extranjeras. Para ello, SafeVision ofrecerá atención en español 24/7 y capacitación rápida tanto para choferes como para gerentes de transporte, asegurando que todos los usuarios puedan aprovechar al máximo el sistema desde el primer día.

#### E) Alianzas Estratégicas

Las colaboraciones serán clave para aumentar la credibilidad y la adopción del sistema. SafeVision firmará convenios con empresas de transporte interprovincial para pruebas piloto, y establecerá acuerdos con aseguradoras para que las flotas que implementen la solución obtengan beneficios o descuentos, incentivando su uso y generando confianza en el mercado.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Preguntas generales (para todos los segmentos)**

- ¿Cuál es tu nombre?
- ¿Qué edad tienes?
- ¿Dónde vives actualmente?
- ¿A qué te dedicas?

---

**Segmento 1: Conductores interprovinciales y de larga distancia**

- ¿Ha experimentado situaciones de somnolencia al volante? ¿Cómo las maneja?
- ¿Qué señales o síntomas nota primero cuando empieza a sentirse somnoliento mientras conduce?
-  ¿Cuánto cree que influye el cansancio acumulado de días anteriores en su nivel de alerta al conducir?
- ¿En qué momento del viaje considera más difícil mantenerse atento (madrugada, después de comer, largas rectas)?
- ¿Qué situaciones cree que generan mayor riesgo de somnolencia en la carretera?
- ¿Cómo percibe que la fatiga afecta su tiempo de reacción frente a situaciones de riesgo en la carretera?
- ¿Qué tipo de alertas le resultan más efectivas (sonoras, visuales, vibración en el móvil)?
- ¿Qué preocupaciones tendría sobre la privacidad al usar un sistema que monitorea su rostro y gestos?
- ¿Le parecería útil usar un sistema que lo alerte en tiempo real sobre su fatiga?
- ¿Qué tan dispuesto estaría a usar un sistema que registre datos sobre su conducción para reportarlos a la empresa?
- ¿Qué mejoras cree que un sistema de monitoreo podría aportar a su seguridad y desempeño al conducir?

---

**Segmento 2: Empresas de transporte y gerentes de flotas**

- ¿Cuántos conductores o vehículos administra en promedio su flota?
- ¿Cuáles son los principales riesgos que enfrentan en los viajes interprovinciales?
- ¿Cómo controlan actualmente la fatiga o estado de sus choferes?
- ¿Qué métricas utilizan para evaluar el desempeño y seguridad de sus conductores?
- ¿Qué indicadores priorizan al evaluar a sus conductores (accidentes, multas, horas de descanso)?
- ¿Qué valor tendría para su empresa contar con reportes en la nube sobre el estado de los conductores?
- ¿Qué factores considerarían más importantes para decidir adquirir un sistema como SafeVision (precio, efectividad, facilidad de uso)?
- ¿Qué tan confiables consideran los sistemas actuales para detectar fatiga y prevenir accidentes?
- ¿Estarían dispuestos a implementar un sistema que genere alertas automáticas a los conductores y reportes en tiempo real para supervisores?
- ¿Qué beneficios creen que obtendrían al usar un sistema que permita anticipar riesgos de somnolencia y distracción en sus conductores?

---

### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. Empathy Mapping
### 2.3.4. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose
### 4.1.2. Attribute-Driven Design Inputs

#### 4.1.2.1. Primary Functionality (Primary User Stories)
#### 4.1.2.2. Quality attribute Scenarios
#### 4.1.2.3. Constraints

### 4.1.3. Architectural Drivers Backlog
### 4.1.4. Architectural Design Decisions
### 4.1.5. Quality Attribute Scenario Refinements

## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming
### 4.2.2. Candidate Context Discovery
### 4.2.3. Domain Message Flows Modeling
### 4.2.4. Bounded Context Canvases
### 4.2.5. Context Mapping

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram
### 4.3.1. Software Architecture Context Level Diagrams
### 4.3.2. Software Architecture Container Level Diagrams
### 4.3.3. Software Architecture Deployment Diagrams
