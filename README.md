# 🕳️ VíaSmart Quito — Nodo de Innovación y Priorización Vial (UIO)

> **Avance de Proyecto [APEB1-20%] AC2 — Introducción a la Administración Pública**  
> **Tema:** Identifique y desarrolle un nodo de innovación para un Municipio (Distrito Metropolitano de Quito).  
> **Autores:** Marilyn Boza / Deejay17  
> **Web App en vivo:** [https://deejay17.github.io/BachesUIO/](https://deejay17.github.io/BachesUIO/)

---

## 🌟 Visión del Proyecto
**VíaSmart** es una aplicación web cívica diseñada para transformar el modelo tradicional y discrecional de atención de baches en el Distrito Metropolitano de Quito hacia un **modelo de gobernanza interactiva y priorización algorítmica orientada a datos**.

En lugar de depender de llamadas telefónicas dispersas, inspecciones manuales y asignación política de asfalto, la plataforma permite que los ciudadanos:
1. Registren evidencia fotográfica y coordenadas GPS en tiempo real.
2. Respalden baches comunitarios (votos y réplicas) para evitar duplicados y aumentar la prioridad objetiva.
3. Alimenten un panel georreferenciado con Leaflet / OpenStreetMap para optimizar las rutas de las cuadrillas de la Empresa Pública Metropolitana de Movilidad y Obras Públicas (EPMMOP).

---

## 📊 Casos Reales Integrados en el Sistema
| Caso | Ubicación | Severidad | Impacto Comunitario |
| :--- | :--- | :--- | :--- |
| **Bache Crítico con Llanta de Advertencia** | Av. Simón Bolívar (Guápulo) | ⚠️ Alta | 68 votos / 3 réplicas · Advertencia vecinal tras despistes nocturnos |
| **Trinchera de Baches Consecutivos** | Av. Mariscal Sucre (El Pintado) | ⚠️ Alta | 54 votos / 2 réplicas · Carril de transporte público y articulados |
| **Cráter en Zona Comercial** | La Carolina (Av. Shyris y República) | ⚠️ Alta | 41 votos / 2 réplicas · Alto flujo vehicular y riesgo a motociclistas |
| **Pozo Inundado en Asfalto** | Cotocollao (Av. Galo Plaza Lasso) | ⚡ Media | 29 votos / 1 réplica · Daño oculto por aguas lluvias |
| **Desprendimiento Asfáltico** | Guápulo (De los Conquistadores) | ⚡ Media | 22 votos / 1 réplica · Grava suelta hacia parabrisas |

---

## 📐 Fundamento Teórico y Académico
- **B. Guy Peters:** Superación de la burocracia jerárquica vertical mediante la gobernanza colaborativa.
- **Laurence E. Lynn, Jr. & María del Carmen Pardo:** Nueva Gestión Pública (NGP), reducción del tiempo medio de resolución (MTTR) y valor público.
- **Carta Iberoamericana de Innovación en la Gestión Pública (CLAD):** Trazabilidad, transparencia y datos abiertos para la toma de decisiones.

---

## 💻 Arquitectura Tecnológica
- **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript.
- **Mapeo:** Leaflet.js con CartoDB Dark Tiles & OpenStreetMap.
- **Persistencia:** LocalStorage API del navegador.
- **Geolocalización:** HTML5 Geolocation API nativa + Coordenadas de calibración para Quito.
- **Despliegue:** GitHub Pages (HTTPS, 100% gratuito).
