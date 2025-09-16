<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>    
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <br><strong>Arquitecturas de Software Emergentes - 7291</strong><br>
    <br><strong>Docente: Rojas Malasquez, Royer Edelwer</strong><br> 
    <br><strong>Informe de Trabajo</strong><br>
</p>

<p align="center">
    <strong>Startup: PCC Team</strong><br>
    <br><strong>Producto: Safe Vision</strong><br>
</p>

<div>
    <h3 align="center">Team Members:</h3>
</div>

<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Nombre</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td style="text-align:center;">Herrera Aguirre, Fabia Alejandra</td>
            <td style="text-align:center;">U202219422</td>
        </tr>
        <tr>
            <td style="text-align:center;">Linares Tejada, Leonardo Felix Jesus</td>
            <td style="text-align:center;">U202211168</td>
        </tr>
        <tr>
            <td style="text-align:center;">Oneglio De Paz, Beth Shantal</td>
            <td style="text-align:center;">U202213423</td>
        </tr>
        <tr>
            <td style="text-align:center;">Salgado Luna, Fernando Brian</td>
            <td style="text-align:center;">U202212023</td>
        </tr>
        <tr>
            <td style="text-align:center;">Sosa Colca, Angelo Rodolfo</td>
            <td style="text-align:center;">U202212077</td>
        </tr>
    </table>
    </div>
</body>

<p align="center">
<br><strong>2025-02</strong></p>
<br>

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
| Herrera Aguirre, Fabia Alejandra     | U202219422       | Ingeniería de Software | Soy Fabia Herrera, estudiante de 8vo ciclo, me considero una persona creativa y responsable, valores que considero serán útiles para garantizar entregas óptimas para este proyecto. Entre mis habilidades técnicas están los lenguajes de programación C#, Java, C++, Python y JavaScript principalmente, y el uso de los frameworks Angular y Vue. | <img src="assets/team-members/fabia-herrera.png" width="80"> |
| Linares Tejada, Leonardo Félix Jesús | U2022xxxxx       | Ingeniería de Software |  | <img src="" width="80"> |
| Oneglio De Paz, Beth Shantal         | U202213423       | Ingeniería de Software | Mi nombre es Beth Shantal Oneglio De Paz - u202213423, tengo 20 años y estudio Ingeniería de Software en la UPC. Disfruto trabajar en equipo y resolver problemas digitales. Estoy capacitada para enfrentar situaciones estresantes con responsabilidad y liderazgo. Poseo conocimientos avanzados en gestión y programación, adquiridos en ciclos anteriores. Manejo lenguajes y tecnologías como Python, C++, HTML5, CSS3, .NET, Vue.js, C#, JavaScript, PHP, MongoDB, MySQL, entre otras. | <img src="assets/team-members/beth-oneglio.jpg" width="80"> |
| Salgado Luna, Fernando Brian        | U202212023        | Ingeniería de Software | Soy Fernando Salgado, tengo 20 años y me apasiona la tecnología. Tengo experiencia en desarrollo frontend y backend, trabajando con lenguajes como C#, Java y otros. Disfruto resolviendo problemas y buscando soluciones prácticas que contribuyan a los proyectos en los que participo. | <img src="https://i.imgur.com/ZMT41YU.jpeg" width="80"> |
| Sosa Colca Angello Rodolfo          | U2022xxxxx       | Ingeniería de Software |  | <img src="" width="80"> |

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

**Segmento Objetivo 1: Conductores interprovinciales y de larga distancia**

| **Entrevista 1** |              |
|--------------|--------------|
| Edad         |              |
| Distrito     |              |
| **Imagen**   |              |
| Timing:      |              |
| **Entrevista 2** |              |
| Edad         |              |
| Distrito     |              |
| **Imagen**   |              |
| Timing:      |              |
| **Entrevista 3** |              |
| Edad         |              |
| Distrito     |              |
| **Imagen**   |              |
| Timing:      |              |

<br>

**Segmento 2: Gerenciales de empresas de transporte**

| **Entrevista 1** | **Juan Jesús Calisaya Sánchez** |
|--------------|--------------|
| Edad         | 21           |
| Distrito     | Lima         |
| <img src="assets/juan-entrevista.jpg" width="80">  | Juan, gerente de transporte, comentó que administra unos 50 buses y que la fatiga de los conductores es el principal riesgo. Actualmente usan protocolos de descanso, pero no siempre resultan efectivos. Valora contar con reportes en la nube y prioriza efectividad y facilidad de uso por encima del precio. Estaría dispuesto a implementar SafeVision si es confiable, ya que le permitiría reducir accidentes, mejorar la seguridad y optimizar la gestión de su flota. |
| Timing:     |              |
| **Entrevista 2** |              |
| Edad         |              |
| Distrito     |              |
| **Imagen**   |              |
| Timing:      |              |
| Entrevista 3 |              |
| Edad         |              |
| Distrito     |              |
| **Imagen**   |              |
| Timing:      |              |

Enlace de las Entrevistas:

### 2.2.3. Análisis de entrevistas

Según las entrevistas realizadas y los resúmenes, hemos llevado a cabo un análisis de las entrevistas en el que destacamos las similitudes y hallazgos:

**Segmento Objetivo 1: Conductores interprovinciales y de larga distancia**

Durante las entrevistas con los conductores se identificó que la fatiga y la somnolencia son problemas frecuentes debido a las largas jornadas y a la presión por cumplir horarios. Ellos mencionaron que, aunque existen descansos programados, no siempre son respetados por la dinámica del trabajo. Coincidieron en que contar con alertas en tiempo real sería de gran ayuda para prevenir accidentes y mejorar su seguridad personal. Asimismo, valoran que la herramienta sea sencilla de usar y no interfiera en la conducción.

**Segmento 2: Gerenciales de empresas de transporte**

Las entrevistas con los gerentes revelaron que la principal preocupación está en la seguridad de los pasajeros y la reducción de accidentes. Señalaron que actualmente aplican protocolos de descanso y métricas de desempeño como accidentes y multas, aunque reconocen limitaciones en su efectividad. Consideran que un sistema como SafeVision tendría un alto valor si ofrece reportes en la nube y monitoreo en tiempo real, ya que permitiría tomar decisiones rápidas y optimizar la gestión de la flota. Además, priorizan la efectividad y la facilidad de uso por encima del precio, y estarían dispuestos a implementar la solución siempre que garantice confiabilidad y buena integración.

## 2.3. Needfinding

### 2.3.1. User Personas

<h2>User Persona Conductor profesional</h2>
<div style="text-align: center;">
  <img src="./assets/user-persona/Pablo Lozada.png" alt="User persona Owner" width="100%" />
</div>
<br>

El segmento de conductores profesionales de buses interprovinciales y camiones de carga está compuesto por personas de entre 25 y 55 años que realizan jornadas prolongadas, a menudo en horarios nocturnos o de madrugada, incrementando la probabilidad de somnolencia y distracción al volante. Su labor requiere mantener un nivel constante de concentración durante viajes largos e interprovinciales, y son directamente afectados por la fatiga, lo que hace necesario un sistema que les emita alertas oportunas para prevenir accidentes y mejorar su seguridad durante la conducción.

<br>
<h2>User Persona Gerente de flota</h2>
<div style="text-align: center;">
  <img src="./assets/user-persona/Carlos Gutierrez.png" alt="User persona Owner" width="100%" />
</div>
<br>

El segmento de gerentes o supervisores de flotas de transporte incluye personas de entre 30 y 55 años responsables de la seguridad y operación de los conductores en viajes interprovinciales o de larga distancia. Su rol implica monitorear el estado de alerta de los conductores mediante reportes en tiempo real, tomar decisiones preventivas para reducir riesgos y garantizar el cumplimiento de normas de seguridad, con el objetivo de disminuir accidentes, mejorar la gestión de riesgos y optimizar la operación diaria de la flota.

### 2.3.2. User Task Matrix

En esta parte se expone la User Task Matrix, la cual detalla las tareas que los usuarios deben realizar para alcanzar sus objetivos al interactuar con el sistema SafeVision. La matriz está organizada por segmentos de usuarios, objetivos y tareas específicas, proporcionando una visión clara de las funcionalidades necesarias para satisfacer las necesidades de los conductores profesionales y los gerentes de flotas.

| Task                                                   | Conductor profesional (Frecuencia / Importancia) | Gerente de flota (Frecuencia / Importancia) |
| ------------------------------------------------------ | ------------------------------------------------ | ---------------------- |
| Mantenerse alerta durante el viaje                     | Alta / Alta                                      | Baja / Alta            |
| Recibir alertas de somnolencia en tiempo real          | Alta / Alta                                      | Baja / Alta            |
| Revisar su propio historial de alertas                 | Media / Alta                                     | Baja / Media           |
| Tomar descansos cuando el sistema lo recomienda        | Media / Alta                                     | Baja / Media           |
| Monitorear en tiempo real el estado de los conductores | –                                                | Alta / Alta            |
| Recibir reportes automáticos de desempeño y fatiga     | Baja / Media                                     | Alta / Alta            |
| Analizar tendencias de fatiga para planificar turnos   | –                                                | Media / Alta           |
| Justificar decisiones de cambio de turnos o descansos  | –                                                | Media / Alta           |
| Garantizar la seguridad de los pasajeros               | Alta / Alta                                      | Alta / Alta            |
| Reducir accidentes por somnolencia                     | Alta / Alta                                      | Alta / Alta            |


### 2.3.3. Empathy Mapping

A continuación se presenta el Empathy Map que detalla las percepciones, pensamientos, sentimientos y comportamientos de los dos segmentos de usuarios principales: conductores profesionales y gerentes de flotas. Este mapa ayuda a comprender mejor sus necesidades y motivaciones al interactuar con el sistema SafeVision.

**Empathy Map Conductor profesional:**
<div style="text-align: center;">
  <img src="./assets/empathy-mapping/conductor-profesional.png" alt="Empathy Map Conductor profesional" width="100%" />
</div>


<br></br>

**Empathy Map Gerente de flota:**
<div style="text-align: center;">
  <img src="./assets/empathy-mapping/gerente-de-flota.png" alt="Empathy Map Gerente de flota" width="100%" />
</div>

### 2.3.4. As-is Scenario Mapping


**As-is Scenario Mapping Conductor Profesional:**


<div style="text-align: center;">
  <img src="./assets/as-is/as-is-conductor.jpg" alt="As-Is Conductor profesional" width="100%" />
</div>  

**As-Is Scenario Mapping Gerente de flota**

<div style="text-align: center;">
  <img src="./assets/as-is/as-is-gerente.jpg" alt="As-Is Gerente de flota" width="100%" />
</div>  
<br>
Enlace al tablero en Miro en donde fueron realizados los As-Is Scenario Mapping: <a href="https://miro.com/app/board/uXjVJI4Pgq0=/?share_link_id=121411571054">https://miro.com/app/board/uXjVJI4Pgq0=/?share_link_id=121411571054</a>
<br>

## 2.4. Ubiquitous Language

En esta sección se presenta el Ubiquitous Language, que define los términos clave utilizados en el contexto del sistema SafeVision. Este lenguaje común facilita la comunicación entre los diferentes actores involucrados, asegurando que todos comprendan claramente los conceptos y funcionalidades del producto.

| **Término (Inglés)**  | **Término (Español)**                  | **Definición**                                                                                                                        |
| ------------------- | -------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Professional Driver | Conductor profesional                  | Persona que opera vehículos de transporte interprovincial de pasajeros, cumpliendo con normas de seguridad y tiempos de ruta establecidos.      |
| Fleet Manager       | Jefe de operaciones / Gerente de flota | Responsable de coordinar, supervisar y evaluar el rendimiento de los conductores y vehículos dentro de una empresa de transporte.               |
| Passenger Safety    | Seguridad del pasajero                 | Condición de protección y cuidado de los pasajeros durante el viaje, evitando riesgos de accidentes por fatiga o negligencia.                   |
| Fatigue Detection   | Detección de fatiga                    | Proceso de identificar señales físicas o comportamentales que indican cansancio del conductor, como parpadeo excesivo o bostezos.               |
| Alert System        | Sistema de alertas                     | Mecanismo que notifica al conductor y/o al gerente de flota sobre riesgos inmediatos de fatiga o somnolencia para tomar acción preventiva.      |
| Driving Shift       | Turno de conducción                    | Período de tiempo en el que un conductor se encuentra asignado a manejar un vehículo dentro de una ruta o itinerario programado.                |
| Rest Stop           | Parada de descanso                     | Intervalo planificado o no planificado durante un viaje en el que el conductor puede recuperarse de la fatiga antes de continuar.               |
| Route Monitoring    | Monitoreo de ruta                      | Seguimiento en tiempo real del estado del viaje, incluyendo ubicación del vehículo, condiciones del conductor y cumplimiento de tiempos.        |
| Incident Prevention | Prevención de incidentes               | Acciones y medidas adoptadas para evitar accidentes en carretera, especialmente aquellos relacionados con somnolencia.                          |
| Compliance          | Cumplimiento normativo                 | Adherencia a las regulaciones legales y protocolos internos que garantizan la seguridad de los pasajeros y la salud del conductor.              |
| Performance Report  | Informe de desempeño                   | Documento generado que contiene métricas sobre la conducción, incidentes de fatiga y cumplimiento de rutas, utilizado para evaluación y mejora. |
| Safety Culture      | Cultura de seguridad                   | Conjunto de valores y prácticas dentro de la empresa de transporte que priorizan la seguridad del conductor y del pasajero en la operación.     |


# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**To-Be Scenario Mapping Conductor Profesional:**


<div style="text-align: center;">
  <img src="./assets/to-be/to-be-conductor.jpg" alt="To-Be Conductor profesional" width="100%" />
</div>  

<br></br>

**To-Ee Scenario Mapping Gerente de flota**

<div style="text-align: center;">
  <img src="./assets/to-be/to-be-gerente.jpg" alt="To-Be Gerente de flota" width="100%" />
</div>  

<br>
Enlace al tablero en Miro en donde fueron realizados los To-Be Scenario Mapping: <a href="https://miro.com/app/board/uXjVJI4Pgq0=/?share_link_id=121411571054">https://miro.com/app/board/uXjVJI4Pgq0=/?share_link_id=121411571054</a>
<br>

## 3.2. User Stories

En este apartado se presentan las historias de usuario.

# User Stories - SafeVision

| User Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---------------|--------|-------------|-------------------------|---------------------------|
| US01 | Detección de somnolencia en tiempo real | Como conductor, quiero que el sistema identifique signos de fatiga para recibir alertas inmediatas y evitar accidentes. | Dado que el conductor muestra parpadeos o cabeceos, cuando la cámara lo detecte, entonces se generará una alerta sonora y visual en cabina. | Epic 1 |
| US02 | Notificación inmediata al conductor | Como conductor, quiero recibir alertas preventivas en el momento adecuado para reaccionar y mantenerme seguro. | Dado que el sistema detecta señales de somnolencia, cuando supere el umbral definido, entonces me notificará con vibración o sonido. | Epic 1 |
| US03 | Alerta por micro-sueños | Como conductor, quiero que el sistema detecte cierres prolongados de ojos para evitar quedarme dormido al volante. | Dado que los ojos permanecen cerrados, cuando supere 2 segundos, entonces se generará una alerta crítica. | Epic 1 |
| US04 | Alerta sonora y visual configurable | Como conductor, quiero que las alertas tengan volumen y modo visual configurables para asegurar efectividad sin distracción. | Dado que se detecta fatiga, cuando se active la alerta, entonces sonará con la intensidad configurada y se mostrará en pantalla. | Epic 1 |
| US05 | Guía post-alerta | Como conductor, quiero que la app me dé instrucciones simples tras una alerta (ej. hidratarme, detenerme) para reaccionar mejor. | Dado que se genera una alerta crítica, cuando la reciba, entonces se mostrará una recomendación inmediata. | Epic 1 |
| US06 | Recordatorio de descanso obligatorio | Como conductor, quiero recibir notificaciones cuando supere cierto tiempo de conducción continua para poder tomar pausas. | Dado que el tiempo de conducción supera las 4 horas, cuando no haya descanso registrado, entonces el sistema enviará una alerta de pausa obligatoria. | Epic 1 |
| US07 | Historial personal de alertas y viajes | Como conductor, quiero consultar mi historial de alertas y viajes para conocer mis patrones de fatiga y mejorar mis hábitos. | Dado que el conductor inicia sesión en la app, cuando seleccione "Historial", entonces verá la lista de viajes previos y alertas registradas. | Epic 1 |
| US08 | Reporte resumido por viaje | Como conductor, quiero recibir un resumen al finalizar mi recorrido para entender cómo fue mi desempeño en cuanto a somnolencia. | Dado que el viaje finaliza, cuando cierre sesión, entonces recibirá un reporte con cantidad de alertas y nivel de riesgo. | Epic 1 |
| US09 | Reporte de viaje saludable | Como conductor, quiero visualizar recomendaciones personalizadas después de mi viaje para mejorar mi rendimiento futuro. | Dado que termina un viaje, cuando se genere el reporte, entonces incluirá sugerencias como horarios de descanso y hábitos recomendados. | Epic 1 |
| US10 | Feedback del sistema | Como conductor, quiero poder enviar comentarios o marcar falsas alarmas para mejorar la precisión del sistema. | Dado que el conductor recibe una alerta, cuando considere que fue incorrecta, entonces podrá marcarla como "falsa alarma" y enviar feedback. | Epic 1 |
| US11 | Integración cámara–app automática | Como conductor, quiero que la cámara se conecte automáticamente con la aplicación al iniciar el viaje sin configuración manual. | Dado que la cámara está encendida, cuando se abra la app, entonces se sincronizará automáticamente. | Epic 1 |
| US12 | Modo de prueba de alertas | Como conductor, quiero probar el sistema de alertas antes de iniciar el viaje para asegurarme de que funciona correctamente. | Dado que el conductor activa el "modo prueba", cuando ejecute la simulación, entonces el sistema generará una alerta sonora y visual de verificación. | Epic 1 |
| US13 | Acceso a reportes de seguridad | Como gerente, quiero visualizar reportes sobre el estado de los conductores para tomar decisiones preventivas. | Dado que los datos se guardan en la nube, cuando el gerente acceda a la plataforma, entonces podrá consultar reportes históricos. | Epic 2 |
| US14 | Notificación crítica al gerente | Como gerente, quiero recibir alertas en tiempo real de conductores en riesgo para intervenir rápidamente. | Dado que un conductor está en nivel crítico de fatiga, cuando el sistema lo detecte, entonces enviará un aviso inmediato al gerente. | Epic 2 |
| US15 | Dashboard general de flota | Como gerente, quiero un panel centralizado para ver el estado actual de todos los conductores y priorizar acciones. | Dado que hay varios conductores conectados, cuando el gerente ingrese al dashboard, entonces visualizará su estado en tiempo real. | Epic 2 |
| US16 | Detección de patrones de riesgo | Como gerente, quiero que el sistema identifique patrones recurrentes de somnolencia para tomar medidas preventivas. | Dado que el sistema analiza datos históricos, cuando un conductor acumule alertas en franjas repetidas, entonces notificará al gerente. | Epic 2 |
| US17 | Alertas agregadas por horas de viaje | Como gerente, quiero ver en qué franjas horarias se presentan más alertas para mejorar la planificación de turnos. | Dado que existen datos de viajes, cuando seleccione la opción, entonces se mostrarán las franjas horarias con mayor riesgo. | Epic 2 |
| US18 | Notificación de viaje seguro completado | Como gerente, quiero recibir un aviso cuando un conductor finaliza un recorrido sin alertas críticas. | Dado que el viaje termina, cuando no existan alertas críticas, entonces se enviará notificación de éxito. | Epic 2 |
| US19 | Exportación de métricas | Como gerente, quiero exportar reportes en distintos formatos (PDF, Excel) para auditorías internas. | Dado que existen datos de seguridad, cuando solicite exportar, entonces el sistema generará el archivo. | Epic 2 |
| US20 | Geolocalización en tiempo real | Como gerente, quiero ver en un mapa la ubicación de cada conductor en tiempo real. | Dado que el vehículo está en ruta, cuando el gerente acceda al dashboard, entonces visualizará la posición actual en el mapa. | Epic 2 |
| US21 | Comparación entre conductores | Como gerente, quiero comparar métricas de somnolencia entre conductores para identificar a los que requieren apoyo. | Dado que existen datos históricos, cuando seleccione "comparar", entonces se mostrarán gráficas comparativas. | Epic 2 |
| US22 | Panel de estadísticas generales de flota | Como gerente, quiero ver estadísticas globales de la flota (alertas totales, viajes seguros, descansos cumplidos). | Dado que accede el gerente al dashboard, cuando seleccione "estadísticas de flota", entonces se mostrarán métricas globales. | Epic 2 |
| US23 | Notificación de pérdida de conexión | Como gerente, quiero recibir notificación si el sistema pierde conexión con un conductor. | Dado que la cámara o app pierde señal, cuando ocurra la desconexión, entonces notificará automáticamente al gerente. | Epic 2 |
| US24 | Registro de mantenimiento del sistema | Como empresa, quiero registrar las fechas de mantenimiento de cámaras y dispositivos para asegurar su funcionamiento. | Dado que se realiza un mantenimiento, cuando se registre en la plataforma, entonces quedará almacenado con fecha y observaciones. | Epic 2 |
| US25 | Privacidad de datos personales | Como empresa, quiero que los datos de los conductores estén encriptados para proteger su información. | Dado que se almacenan datos, cuando se guarden en la nube, entonces estarán encriptados. | Epic 2 |
| US26 | Registro de conductores | Como gerente, quiero registrar a los conductores en la plataforma para tener un control organizado de la flota. | Dado que el gerente ingresa a administración, cuando complete los datos, entonces el sistema guardará la información. | Epic 3 |
| US27 | Registro de usuario | Como nuevo usuario, quiero registrarme en la plataforma para acceder al sistema SafeVision según mi rol. | Dado que soy un nuevo usuario, cuando complete el registro, entonces el sistema creará mi cuenta. | Epic 3 |
| US28 | Login de usuario | Como usuario registrado, quiero iniciar sesión para acceder a las funcionalidades de mi rol. | Dado que tengo cuenta activa, cuando ingrese email y contraseña correctos, entonces accederé al dashboard de mi rol. | Epic 3 |
| US29 | Validación de rol de usuario | Como sistema, quiero validar el rol del usuario para mostrar funcionalidades apropiadas. | Dado que un usuario inicia sesión, cuando se valide su rol, entonces será redirigido al dashboard correspondiente. | Epic 3 |
| US30 | Configuración de parámetros de seguridad | Como gerente, quiero ajustar umbrales de detección de fatiga según políticas internas. | Dado que accede a configuración, cuando modifique valores de umbral, entonces el sistema actualizará la detección. | Epic 3 |
| US31 | Gestión de roles de usuario | Como empresa, quiero asignar diferentes roles (gerente, supervisor, conductor) para controlar accesos. | Dado que se crea un nuevo usuario, cuando se asigne un rol, entonces se mostrarán permisos adecuados. | Epic 3 |

## 3.3. Impact Mapping

Para el desarrollo de SafeVision, se ha elaborado un Impact Mapping que detalla los objetivos del negocio, los actores involucrados, los impactos esperados y las funcionalidades clave del sistema. Este mapa estratégico ayuda a alinear las acciones del equipo con los resultados deseados, asegurando que cada característica desarrollada contribuya directamente a los objetivos de seguridad vial y satisfacción del cliente.

**Business goals:**
- Reducir en un 30% los incidentes de somnolencia en conductores en un periodo de 12 meses.
- Aumentar en 50% el cumplimiento de descansos programados en turnos nocturnos en 8 meses.
- Lograr que el 80% de los conductores adopten el sistema en sus primeros 6 meses de implementación.

<div style="text-align: center;">
  <img src="./assets/impact-mapping/conductor-impact.png" alt="Impact Mapping Conductor profesional" width="100%" />
</div>


<br></br>

**Business goals:**
- Disminuir en 40% la tasa de accidentes relacionados con la fatiga en la empresa en un año.
- Garantizar que el 90% de los conductores cumpla con las políticas de descanso en un periodo de 6 meses.
- Reducir en 25% los costos asociados a incidentes por fatiga en 10 meses.

<div style="text-align: center;">
  <img src="./assets/impact-mapping/gerente-impact.png" alt="Impact Mapping Conductor profesional" width="100%" />
</div>



## 3.4. Product Backlog

# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose

El objetivo de diseño de SafeVision es aumentar la seguridad vial de los conductores mediante un sistema de inteligencia artificial capaz de identificar en tiempo real señales de fatiga o somnolencia. Con el apoyo de una cámara instalada en la cabina y una aplicación móvil, se generan alertas inmediatas para reducir el riesgo de accidentes. Asimismo, la información se procesa en la nube, brindando a las empresas de transporte la posibilidad de acceder a reportes y supervisar de manera constante el estado de sus choferes.

### 4.1.2. Attribute-Driven Design Inputs

En esta sección se presentarán las Epics y User Stories clave, enfocadas en los requisitos funcionales que influyen directamente en la arquitectura de la solución propuesta para garantizar su correcto diseño, implementación y escalabilidad. Estas historias de usuario permitirán definir las capacidades esenciales del sistema, alineando las necesidades de los usuarios finales con los objetivos del proyecto.

| User Story ID | Título                               | Descripción                                                                                   | Criterios de Aceptación                                                                                                    | Relacionado con (Epic ID) |
|---------------|--------------------------------------|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|---------------------------|
| EP01/US01     | Detección de signos de somnolencia   | Como **conductor**, quiero que el sistema detecte signos de somnolencia para recibir alertas y prevenir accidentes. | **Dado que** el conductor está siendo monitoreado, **cuando** se detecten ojos cerrados, bostezos o movimientos de cabeza, **entonces** el sistema debe generar una alerta visual y auditiva en la cabina. | EP01 |
| EP01/US02     | Envío de alertas a la app móvil      | Como **conductor**, quiero recibir notificaciones inmediatas en mi aplicación móvil para reaccionar a tiempo. | **Dado que** el sistema detecta somnolencia, **cuando** se genere la alerta, **entonces** la app debe mostrar una notificación con sonido y vibración en menos de 2 segundos. | EP01 |
| EP01/US03     | Reportes en la nube                  | Como **gerente**, quiero acceder a reportes con historial de alertas de cada conductor para supervisar su estado. | **Dado que** el sistema registra eventos de somnolencia, **cuando** el gerente consulte el portal, **entonces** podrá ver reportes con fecha, hora, tipo de evento y estadísticas por conductor/vehículo. | EP01 |
| EP02/US04     | Registro de conductores              | Como **gerente**, quiero registrar la información de los conductores para tener control de su desempeño. | **Dado que** el gerente tiene acceso al sistema, **cuando** registre a un nuevo conductor, **entonces** deberá completar los campos obligatorios (nombre, licencia, horarios) y recibir confirmación del registro exitoso. | EP02 |
| EP02/US05     | Registro de vehículos                | Como **gerente**, quiero registrar los vehículos de la empresa para asociarlos a los conductores. | **Dado que** el gerente ingresa un vehículo, **cuando** complete los campos requeridos (placa, modelo, año), **entonces** el sistema debe validar duplicados y confirmar el registro. | EP02 |
| EP02/US06     | Asociación conductor-vehículo        | Como **gerente**, quiero asociar conductores a vehículos específicos para llevar control de la flota. | **Dado que** existen conductores y vehículos registrados, **cuando** el gerente los vincule, **entonces** el sistema debe guardar la asociación con fecha y mostrarla en los reportes. | EP02 |
| EP03/US07     | Ajuste de sensibilidad de alertas    | Como **gerente**, quiero definir la sensibilidad del sistema para reducir falsos positivos o negativos. | **Dado que** el gerente accede a la configuración, **cuando** seleccione un nivel de sensibilidad (baja, media, alta), **entonces** el sistema debe aplicar el cambio en tiempo real y registrarlo. | EP03 |
| EP03/US08     | Configuración de notificaciones      | Como **conductor**, quiero configurar el tipo de notificación (sonido, vibración, visual) para adaptarlas a mis preferencias. | **Dado que** el conductor ingresa a la configuración, **cuando** active o desactive un tipo de notificación, **entonces** el sistema debe guardar los cambios y aplicarlos de inmediato. | EP03 |
| EP03/US09     | Idioma de la aplicación              | Como **conductor**, quiero cambiar el idioma de la app para usarla en mi lengua preferida. | **Dado que** el conductor accede a la configuración, **cuando** seleccione un idioma, **entonces** la aplicación debe actualizarse automáticamente y guardar la preferencia en su perfil. | EP03 |

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
