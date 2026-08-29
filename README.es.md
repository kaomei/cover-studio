<div align="center">

[简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [**Español**](README.es.md)

# 🎨 Skill Universal de Portadas (Cover Studio)

### Flujo de Trabajo Todo en Uno para Portadas Virales · Integrado con 9 Motores de Código Abierto

Un Skill de IA de código abierto para creadores, desarrolladores y redactores. ¡Elimina la parálisis de elección! Permite **seleccionar tu lista de tamaños individuales bien diferenciados** en la instalación del Skill Universal de Portadas, **primero alinea la jerarquía de texto (titular grande + subtítulo + etiquetas)** y luego **genera directamente 3 conceptos de diseño en imagen o prompts simultáneamente**. Soporta fijación de Sistema de Marca (Brand System), **generación directa en Codex** y **prompts optimizados para Nano Banana (Google Flow gratis)**.

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=flat-square)
![9 Motores](https://img.shields.io/badge/Motores-9%20Skills%20Top%20Open--Source-0066ff?style=flat-square)
![Formatos Claros](https://img.shields.io/badge/Tamaños%20Elegidos-3%3A4%20%7C%202.35%3A1%20%7C%2016%3A9%20%7C%205%3A2-f59e0b?style=flat-square)
![Generación Gratuita](https://img.shields.io/badge/Generación-Codex%20Directo%20%7C%20Nano%20Banana%20Gratis-8b5cf6?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)

<br/>

Ideal para: **Notas virales de Xiaohongshu, cabeceras de WeChat, artículos de X/Twitter, miniaturas de YouTube y vistas previas de GitHub**.

</div>

---

## ✨ Características Principales

- ⚙️ **Configuración Inicial de Tamaños Diferenciados**: Marca exactamente qué formatos de plataforma necesitas en lote por separado (Xiaohongshu `3:4`, WeChat `2.35:1`, X Post `16:9`, X Artículo `5:2`, Video `16:9`, GitHub `2:1`, Cuadrado `1:1`, etc.).
- ✍️ **Alineación Previa de Jerarquía de Texto**: Confirma el titular principal grande, subtítulo y etiquetas antes de generar las imágenes.
- 🖼️ **Generación Directa de 3 Estilos**: Produce 3 opciones completas con la tipografía alineada de forma simultánea.
- 🏷️ **Fijación de Sistema de Marca (Brand System)**: Guarda tu estilo elegido para mantener coherencia en todas las publicaciones.
- 📐 **Reorganización Inteligente según Formato**: Reconfigura elementos para los formatos elegidos sin cortes arbitrarios.
- 🚀 **Generación Dual (Directa en Codex + Gratuita en Google Flow)**.
- 🔄 **Enrutamiento Inteligente entre 9 Motores de Portadas**.

---

## 🛠️ Flujo de Trabajo Estándar

```mermaid
flowchart TD
    classDef setupBox fill:#f0f7ff,stroke:#0284c7,stroke-width:2px,color:#0f172a,rx:10px,ry:10px;
    classDef textBox fill:#ecfdf5,stroke:#059669,stroke-width:2px,color:#064e3b,rx:10px,ry:10px;
    classDef genBox fill:#fffbeb,stroke:#d97706,stroke-width:2px,color:#78350f,rx:10px,ry:10px;
    classDef deliverBox fill:#faf5ff,stroke:#9333ea,stroke-width:2px,color:#581c87,rx:10px,ry:10px;
    classDef decision fill:#fff1f2,stroke:#e11d48,stroke-width:2px,color:#881337,rx:6px,ry:6px;
    classDef action fill:#1e293b,stroke:#0f172a,stroke-width:2px,color:#ffffff,font-weight:bold,rx:20px,ry:20px;

    subgraph S0 ["⚙️ Fase 0 · Preferencia Inicial (Única vez)"]
        A0(["🚀 Iniciar Skill Universal de Portadas"]):::action
        A1{"Confirmar modo de salida"}:::decision
        A2["🌟 <b>Lote multiformato de marca unificada</b><br/>━━━━━━━━━━━━━━━━━━━━━<br/>Marcar combinación de tamaños deseados：<br/>• 📕 Xiaohongshu 3:4<br/>• 🟢 WeChat 2.35:1<br/>• 🐦 X Post 16:9 / 📰 X Art 5:2<br/>• 🎬 Video 16:9 / 💻 GitHub 2:1 / 🔲 1:1"]:::setupBox
        A3["🎯 <b>Personalización por tamaño individual</b><br/>Diseño individual para 1 formato"]:::setupBox
        A0 --> A1
        A1 -->|"Modo lote"| A2
        A1 -->|"Modo individual"| A3
    end

    subgraph S1 ["📝 Fase 1 · Texto y Alineación de Jerarquía"]
        B0["📋 Ingresar texto / guion / titular"]:::action
        B1["✍️ <b>Alinear 3 niveles de texto</b><br/>━━━━━━━━━━━━━━━━━━━━━<br/>1️⃣ 📌 <b>Titular grande de gancho</b> (≤6-8 palabras)<br/>2️⃣ 📝 <b>Subtítulo de valor</b> (10-15 palabras)<br/>3️⃣ 🏷️ <b>Etiquetas tipo píldora & checklist</b>"]:::textBox
        B0 --> B1
    end

    subgraph S2 ["🎨 Fase 2 · Generación Directa de 3 Diseños"]
        C0["✅ Confirmar configuración de texto"]:::action
        C1["🖼️ <b>Generar directamente 3 imágenes / prompts</b><br/>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br/>• <b>Estilo A · Cyber Tech</b> (punk-cover)<br/>• <b>Estilo B · Gancho gran texto</b> (atutun-xhs / ponyo)<br/>• <b>Estilo C · Editorial profundo</b> (knowledge-media)"]:::genBox
        C0 --> C1
    end

    subgraph S3 ["🚀 Fase 3 · Elección y Entrega Multiplataforma"]
        D0{"Usuario elige estilo (A / B / C)"}:::decision
        D1["📦 <b>Exportar lote de todos los formatos marcados</b><br/>(3:4 + 2.35:1 + 16:9 etc.)"]:::deliverBox
        D2["🖼️ <b>Exportar tamaño individual seleccionado</b>"]:::deliverBox
        D3["💻 <b>Render directo en Codex O Guía Google Flow</b>"]:::action

        D0 -->|"Modo multiformato"| D1
        D0 -->|"Modo individual"| D2
        D1 ==> D3
        D2 ==> D3
    end

    A2 ==> B0
    A3 ==> B0
    B1 ==> C0
    C1 ==> D0
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
| **🌐 Multiplataforma** | `rn-cover-skill` | [Pluviobyte/rnskill](https://github.com/Pluviobyte/rnskill) | Infografía Editorial 5:2 | Análisis técnico, reportes de investigación |
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

## ⚠️ Aviso Legal (Disclaimer)

1. **Atribución de Código Abierto**: Este proyecto es una habilidad de enrutamiento; todos los derechos de autor de los 9 motores pertenecen a sus respectivos autores originales.
2. **Proyecto No Oficial**: No existe afiliación comercial oficial con las plataformas de redes sociales mencionadas ni con Google.
3. **Uso Permitido**: Para fines educativos, de investigación y creación legítima de contenido.

---

## 🤝 Contribuciones

¡Las sugerencias de nuevos motores y recetas de prompts son bienvenidas!

Si este proyecto te ha sido útil, **¡dale una ⭐️ Star para apoyar a kaomei (烤妹儿)!**

## 📄 Licencia

[MIT License](LICENSE) © 2026 [kaomei](https://github.com/kaomei)
