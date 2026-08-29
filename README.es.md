<div align="center">

[简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [**Español**](README.es.md)

# 🎨 Cover Studio (Estudio Universal de Portadas)

### Flujo de Trabajo Todo en Uno para Portadas Virales · Integrado con 9 Motores de Código Abierto

Un Skill de IA de código abierto para creadores, desarrolladores y redactores. ¡Elimina la parálisis de elección! Consulta el modo de salida en la instalación, **propone simultáneamente 3 conceptos de diseño adaptados**, y **alinea obligatoriamente la jerarquía de texto (titular grande + subtítulo + etiquetas)** antes de generar. Soporta fijación de Sistema de Marca (Brand System), **generación directa en Codex** y **prompts optimizados para Nano Banana (Google Flow gratis)**.

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=flat-square)
![9 Motores](https://img.shields.io/badge/Motores-9%20Skills%20Top%20Open--Source-0066ff?style=flat-square)
![Formatos](https://img.shields.io/badge/Formatos-3%3A4%20%7C%202.35%3A1%20%7C%2016%3A9-f59e0b?style=flat-square)
![Generación Gratuita](https://img.shields.io/badge/Generación-Codex%20Directo%20%7C%20Nano%20Banana%20Gratis-8b5cf6?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)

<br/>

Ideal para: **Notas virales de Xiaohongshu, cabeceras de WeChat, artículos de X/Twitter, miniaturas de YouTube y vistas previas de GitHub**.

</div>

---

## ✨ Características Principales

- ⚙️ **Configuración Inicial de Preferencias**: Pregunta si se prefiere salida multiformato en lote (3:4, 2.35:1, 16:9, etc.) o diseño individual por tamaño.
- 🧠 **Propuesta Simultánea de 3 Estilos**: Analiza tu texto y genera 3 conceptos de diseño visual al mismo tiempo.
- ✍️ **Paso Obligatorio de Alineación de Texto**: Confirma el titular principal grande, subtítulo y etiquetas tipo píldora antes de generar la imagen.
- 🏷️ **Fijación de Sistema de Marca (Brand System)**: Guarda tu estilo elegido para mantener coherencia en todas las publicaciones.
- 📐 **Reorganización Inteligente según Formato**: Reconfigura elementos para `3:4`, `2.35:1` y `16:9` sin cortes arbitrarios.
- 🚀 **Generación Dual (Directa en Codex + Gratuita en Google Flow)**.
- 🔄 **Enrutamiento Inteligente entre 9 Motores de Portadas**.

---

## 📚 Matriz de 4 Corrientes y 9 Motores Integrados

| Corriente | Nombre del Motor | Repositorio GitHub | Características Visuales | Uso Recomendado |
|:---|:---|:---|:---|:---|
| **🌐 Multiplataforma** | `punk-cover` | [adrianpunk/Punk-Skill](https://github.com/adrianpunk/Punk-Skill) | Cyberpunk / Tecnología Moderna | Adaptable a 3:4, 2.35:1, 5:2 |
| **🌐 Multiplataforma** | `huashu-skills` | [alchaincyf/huashu-skills](https://github.com/alchaincyf/huashu-skills) | Lanzamiento Empresarial / Diseño Industrial | IA + Renderizado Vectorial HTML |
| **🌐 Multiplataforma** | `rn-cover-skill` | [Pluviobyte/rnskill](https://github.com/Pluviobyte/rnskill) | Infografía Editorial 5:2 | Análisis técnico, reportes de investigación |
| **📕 Vertical 3:4** | `atutun-xhs-cover` | [panggungunvibe/atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover) | Persona Real / Texto Amarillo Neón / Stickers | Marca personal, guías prácticas |
| **📕 Vertical 3:4** | `gbro-cover-design` | [pyang5166/gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) | Plano Limpio / Tarjetas UI / 10 Diseños | Reseñas de herramientas, software |
| **📕 Vertical 3:4** | `ponyo-cover-anchor-system` | [ponyodong2026/ponyo-cover-anchor-system](https://github.com/ponyodong2026/ponyo-cover-anchor-system) | Conflicto Emocional / Collage de Papel | Storytelling, ganchos de alto CTR |
| **🟢 Horizontal 2.35:1** | `knowledge-media-cover` | [aa1143/knowledge-media-cover](https://github.com/aa1143/knowledge-media-cover) | Papel Marfil / Metáfora Central | Artículos extensos (seguro para recorte 1:1) |
| **🟢 Horizontal 2.35:1** | `wechatcover` | [naplesblue/wechatcover](https://github.com/naplesblue/wechatcover) | Tipografía de Dirección de Arte | Boletines corporativos, identidad de marca |
| **🎬 Video y Tutoriales** | `oil-cover` | [oil-oil/oil-cover](https://github.com/oil-oil/oil-cover) | Minimalismo Apple / Ventana Mac | Grabaciones de código, tutoriales de IA |

---

## 🛠️ Flujo de Trabajo Estándar

```mermaid
flowchart LR
    A[Fase 0: Preferencia Inicial] --> B[Fase 1: Ingreso de Texto]
    B --> C[Fase 2: Propuesta de 3 Diseños]
    C --> D[Fase 3: Elección y Alineación de Texto]
    D --> E[Fase 4: Render Codex / Prompt Google Flow]
```

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
