```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title Cronograma de Actividades

    section Hito 1
    Búsqueda de información sobre el problema         :a1, 2026-08-21, 3d
    Definición del marco teórico                      :a2, after a1, 2d
    Lista de exigencias                               :a3, after a2, 5d
    Estructura de funciones                           :a4, after a3, 7d
    Matriz morfológica                                :a5, after a4, 7d
    Evaluación H1                                     :milestone, h1, 2026-09-19, 0d

    section Hito 2
    Concepto básicos del diseño enfocados al usuario  :b1, 2026-09-23, 5d
    Conceptos de solución óptimo                      :b2, after b1, 7d
    Entrevista del usuario y feedback                 :b3, after b2, 4d
    Proyecto preliminar                               :b4, after b3, 2d
    Evaluación H2                                     :milestone, h2, 2026-10-10, 0d

    section Hito 3
    Pruebas en simuladores del proyecto               :c1, 2026-10-21, 7d
    Pruebas de tarjetas de prototipado electrónico    :c2, after c1, 12d
    Visión del prototipado en CAD                     :c3, after c2, 3d
    Evaluación H3                                     :milestone, h3, 2026-11-14, 0d

    section Hito 4
    Validación del prototipo funcional 1              :d1, 2026-11-18, 2d
    Construcción del prototipo funcional              :d2, after d1, 3d
    Entrevista de solución                            :d3, after d2, 2d
    Validación del prototipo funcional 2              :d4, after d3, 5d
    Evaluación H4                                     :milestone, h4, 2026-12-05, 0d
