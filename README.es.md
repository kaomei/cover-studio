<div align="center">

[简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [**Español**](README.es.md)

# 🎨 Skill Universal de Portadas (Cover Studio)

### Flujo de Trabajo Todo en Uno para Portadas Virales · Integrado con 9 Motores de Código Abierto

Un Skill de IA de código abierto para creadores, desarrolladores y redactores. ¡Elimina la parálisis de elección! Al ingresar un artículo, **primero alinea la jerarquía de texto (titular grande + subtítulo + etiquetas)** y luego **genera directamente 3 conceptos de diseño en imagen o prompts simultáneamente**. Una vez que eliges tu estilo favorito, **selecciona libremente los formatos de plataforma para exportar en lote** y fijar tu Sistema de Marca (Brand System). Soporta **generación directa en Codex** y **prompts optimizados para Nano Banana (Google Flow gratis)**.

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=flat-square)
![9 Motores](https://img.shields.io/badge/Motores-9%20Skills%20Top%20Open--Source-0066ff?style=flat-square)
![Formatos en Lote](https://img.shields.io/badge/Formatos-3%3A4%20%7C%202.35%3A1%20%7C%2016%3A9%20%7C%205%3A2-f59e0b?style=flat-square)
![Generación Gratuita](https://img.shields.io/badge/Generación-Codex%20Directo%20%7C%20Nano%20Banana%20Gratis-8b5cf6?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)

<br/>

Ideal para: **Notas virales de Xiaohongshu, cabeceras de WeChat, artículos de X/Twitter, miniaturas de YouTube y vistas previas de GitHub**.

</div>

---

## 💡 ¿Por qué creamos el "Skill Universal de Portadas"?

Como creador de contenido, desarrollador independiente o redactor técnico, seguro has vivido estos **dolores de cabeza al diseñar portadas**:

1. **🤯 Fatiga de herramientas y parálisis de elección**: Existen decenas de excelentes skills en GitHub (estilo Cyberpunk, Xiaohongshu, WeChat, Corporativo...). Cada vez que terminas un artículo, pierdes tiempo cambiando de herramienta y adivinando cuál funcionará mejor.
2. **📐 El "infierno de formatos" multiplataforma**: Deseas publicar en Xiaohongshu (3:4 vertical), WeChat (2.35:1 panorámico), X/Twitter (16:9 post / 5:2 artículo) y YouTube (16:9). El recorte mecánico tradicional corta textos y arruina la composición visual.
3. **✍️ Caos tipográfico y falta de jerarquía**: Muchas herramientas generan imágenes a ciegas, con textos confusos o titulares sin suficiente impacto visual.
4. **🎨 Falta de coherencia de marca**: Cambiar de estilo en cada publicación impide que la audiencia reconozca tu identidad de creador.

### 🎯 Nuestra Solución: ¡No reinventar la rueda, sino crear el director de orquesta definitivo!
> **En lugar de obligarte a instalar y alternar 10 skills fragmentados, Cover Studio actúa como un centro de control inteligente para todas tus portadas.**

- **Integración de 9 motores Open Source top**: Produce simultáneamente 3 opciones de estilos visuales diferenciados según tu contenido.
- **Alineación previa de jerarquía de texto**: Valida titular grande + subtítulo + etiquetas antes de generar.
- **3 estilos primero, luego exportación multiformato en lote**: Mira el resultado real, elige el ganador y exporta todas las plataformas.
- **Fijación del Sistema de Marca (Brand System)**: Guarda tu fórmula visual preferida para mantener consistencia a largo plazo.

---

## ✨ Características Principales

- ✍️ **Alineación Previa de Jerarquía de Texto**: Confirma el titular principal grande, subtítulo y etiquetas antes de generar las imágenes.
- 🖼️ **Generación Directa de 3 Estilos**: Produce 3 opciones completas con la tipografía alineada de forma simultánea.
- 📐 **Elegir Estilo y luego Expandir a Múltiples Formatos**: Selecciona tu estilo preferido y marca las plataformas deseadas (Xiaohongshu `3:4`, WeChat `2.35:1`, X Post `16:9`, X Artículo `5:2`, Video `16:9`, etc.) para entrega en lote.
- 🏷️ **Fijación de Sistema de Marca (Brand System)**: Guarda tu estilo elegido para mantener coherencia en todas las publicaciones.
- 🚀 **Generación Dual (Directa en Codex + Gratuita en Google Flow)**.
- 🔄 **Enrutamiento Inteligente entre 9 Motores de Portadas**.

---

## 🛠️ Flujo de Trabajo Estándar

```mermaid
flowchart TD
    classDef default fill:#ffffff,stroke:#e2e8f0,stroke-width:1.5px,color:#1e293b,rx:8px,ry:8px;
    classDef startNode fill:#0f172a,stroke:#0f172a,stroke-width:2px,color:#ffffff,font-weight:bold,rx:20px,ry:20px;
    classDef stepNode fill:#ffffff,stroke:#cbd5e1,stroke-width:1.5px,color:#0f172a,rx:8px,ry:8px;
    classDef highlightNode fill:#eff6ff,stroke:#2563eb,stroke-width:2px,color:#1e40af,font-weight:bold,rx:8px,ry:8px;

    A0(["🚀 Iniciar Skill Universal de Portadas"]):::startNode
    --> A1["<b>1. Texto y Jerarquía</b> ： Alinear 📌 Titular grande (≤8 palabras) ＋ 📝 Subtítulo ＋ 🏷️ Etiquetas píldora"]:::highlightNode
    --> A2["<b>2. Generación Directa de 3 Diseños</b> ： Producción simultánea de 【Cyber Tech】·【Gancho Gran Texto】·【Editorial】"]:::stepNode
    --> A3["<b>3. Elegir Estilo ➔ Marcar Formatos</b> ： Confirmar diseño (A/B/C) ➔ Marcar formatos para generar en lote"]:::highlightNode
    --> A4["<b>4. Entrega en Lote ＋ Fijar Marca</b> ： Render directo en Codex O Guía gratuita en Google Flow"]:::stepNode
```

---

## 📚 Matriz de 4 Corrientes y 9 Motores Integrados

```mermaid
flowchart LR
    classDef rootBox fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#ffffff,font-weight:bold,rx:8px,ry:8px;
    classDef cat1 fill:#eff6ff,stroke:#2563eb,stroke-width:2px,color:#1e3a8a,font-weight:bold,rx:6px,ry:6px;
    classDef cat2 fill:#fff1f2,stroke:#e11d48,stroke-width:2px,color:#881337,font-weight:bold,rx:6px,ry:6px;
    classDef cat3 fill:#ecfdf5,stroke:#059669,stroke-width:2px,color:#064e3b,font-weight:bold,rx:6px,ry:6px;
    classDef cat4 fill:#faf5ff,stroke:#9333ea,stroke-width:2px,color:#581c87,font-weight:bold,rx:6px,ry:6px;
    classDef leaf fill:#ffffff,stroke:#cbd5e1,stroke-width:1px,color:#334155,rx:4px,ry:4px;

    CS["🎨 Cover Studio<br/>Estudio Universal de Portadas"]:::rootBox

    CS --> S1["🌐 Multiplataforma Universal"]:::cat1
    S1 --> E1["punk-cover<br/><i>Cyberpunk · Multiformato</i>"]:::leaf
    S1 --> E2["huashu-skills<br/><i>Lanzamiento · IA+HTML</i>"]:::leaf
    S1 --> E3["rn-cover-skill<br/><i>5:2 Infografía Editorial</i>"]:::leaf

    CS --> S2["📕 Xiaohongshu 3:4 Viral"]:::cat2
    S2 --> E4["atutun-xhs-cover<br/><i>Persona Real · Texto Neón · Emoji</i>"]:::leaf
    S2 --> E5["gbro-cover-design<br/><i>Plano Limpio · UI · 10 Diseños</i>"]:::leaf
    S2 --> E6["ponyo-cover-anchor-system<br/><i>Anclaje Emocional · Collage</i>"]:::leaf

    CS --> S3["🟢 WeChat 2.35:1 Exclusivo"]:::cat3
    S3 --> E7["knowledge-media-cover<br/><i>Papel Marfil · 1:1 Seguro</i>"]:::leaf
    S3 --> E8["wechatcover<br/><i>Tipografía Art Director</i>"]:::leaf

    CS --> S4["🎬 Video y Tutoriales"]:::cat4
    S4 --> E9["oil-cover<br/><i>Apple Minimal · Mac · Keyframes</i>"]:::leaf
```

| Corriente | Nombre del Motor | Repositorio GitHub | Características Visuales | Uso Recomendado |
|:---|:---|:---|:---|:---|
| **🌐 Multiplataforma** | `punk-cover` | [adrianpunk/Punk-Skill](https://github.com/adrianpunk/Punk-Skill) | Cyberpunk / Tecnología Moderna | Adaptable a 3:4, 2.35:1, 16:9, 5:2 |
| **🌐 Multiplataforma** | `huashu-skills` | [alchaincyf/huashu-skills](https://github.com/alchaincyf/huashu-skills) | Lanzamiento Empresarial / Diseño Industrial | IA + Renderizado Vectorial HTML |
| **🌐 Multiplataforma** | `rn-cover-skill` | [Pluviobyte/rnskill](https://github.com/Pluviobyte/rnskill) | 5:2 Infografía Editorial | Análisis técnico, reportes de investigación |
| **📕 Vertical 3:4** | `atutun-xhs-cover` | [panggungunvibe/atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover) | Persona Real / Texto Amarillo Neón / Stickers | Marca personal, guías prácticas |
| **📕 Vertical 3:4** | `gbro-cover-design` | [pyang5166/gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) | Plano Limpio / Tarjetas UI / 10 Diseños | Reseñas de herramientas, software |
| **📕 Vertical 3:4** | `ponyo-cover-anchor-system` | [ponyodong2026/ponyo-cover-anchor-system](https://github.com/ponyodong2026/ponyo-cover-anchor-system) | Conflicto Emocional / Collage de Papel | Storytelling, ganchos de alto CTR |
| **🟢 Horizontal 2.35:1** | `knowledge-media-cover` | [aa1143/knowledge-media-cover](https://github.com/aa1143/knowledge-media-cover) | Papel Marfil / Metáfora Central | Artículos extensos (seguro para recorte 1:1) |
| **🟢 Horizontal 2.35:1** | `wechatcover` | [naplesblue/wechatcover](https://github.com/naplesblue/wechatcover) | Tipografía de Dirección de Arte | Boletines corporativos, identidad de marca |
| **🎬 Video y Tutoriales** | `oil-cover` | [oil-oil/oil-cover](https://github.com/oil-oil/oil-cover) | Minimalismo Apple / Ventana Mac | Grabaciones de código, tutoriales de IA |

---

## 📦 Instalación y Uso

```bash
git clone https://github.com/kaomei/cover-studio.git
cd cover-studio

# Codex CLI
cp -R skills/cover-studio "${CODEX_HOME:-$HOME/.codex}/skills/cover-studio"

# Antigravity / Gemini CLI
cp -R skills/cover-studio ~/.gemini/config/skills/cover_studio
```

---

## ⚠️ Aviso Legal

1. **Atribución de Código Abierto**: Este proyecto es una habilidad de enrutamiento; todos los derechos de autor de los 9 motores pertenecen a sus respectivos autores originales.
2. **Proyecto No Oficial**: No existe afiliación comercial oficial con las plataformas de redes sociales mencionadas ni con Google.
3. **Uso Permitido**: Para fines educativos, de investigación y creación legítima de contenido.

---

## 🤝 Contribuciones

¡Las sugerencias de nuevos motores y recetas de prompts son bienvenidas!

Si este proyecto te ha sido útil, **¡dale una ⭐️ Star para apoyar a kaomei (烤妹儿)!**

## 📄 Licencia

[MIT License](LICENSE) © 2026 [kaomei](https://github.com/kaomei)
