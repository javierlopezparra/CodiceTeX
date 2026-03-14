# 𓂀🪶 CodiceTeX

> **Editor LaTeX gratuito y open source para universidades públicas de México y Latinoamérica**

[![Licencia: AGPL v3](https://img.shields.io/badge/Licencia-AGPL%20v3-orange.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Basado en Overleaf](https://img.shields.io/badge/Basado%20en-Overleaf%20Community-green.svg)](https://github.com/overleaf/overleaf)
[![Contribuciones bienvenidas](https://img.shields.io/badge/Contribuciones-Bienvenidas-brightgreen.svg)](CONTRIBUTING.md)
[![Hecho en México](https://img.shields.io/badge/Hecho%20en-M%C3%A9xico%20🇲🇽-red.svg)]()

---

Como los antiguos códices que preservaron el conocimiento mesoamericano, **CodiceTeX** preserva y democratiza el acceso al conocimiento académico. Somos una alternativa gratuita a Overleaf construida para que ningún estudiante latinoamericano tenga que pagar para escribir su tesis.

---

## ¿Por qué CodiceTeX?

Overleaf es una herramienta excelente, pero su versión de pago es inaccesible para la mayoría de estudiantes de universidades públicas en México y Latinoamérica. CodiceTeX nació en la **Universidad Autónoma de Nuevo León** con una misión simple:

> **Que cualquier estudiante pueda escribir su tesis en LaTeX, gratis, sin límites.**

---

## ✨ Características

- 📄 **Editor LaTeX completo** — compilación rápida, autocompletado y resaltado de sintaxis
- 🎓 **Plantillas verificadas para universidades LATAM** — UNAM, IPN, UANL, UAM, UdeG, BUAP y más
- 📚 **Guías en español** — tutoriales paso a paso para tesistas que empiezan desde cero
- 🏛️ **Auto-hospedable** — cualquier universidad puede instalar su propio servidor en minutos
- 🤝 **Colaboración en tiempo real** — edición simultánea con tus compañeros
- 🆓 **Gratis para siempre** — sin límites de proyectos, sin límites de usuarios

---

## 🚀 Instalación rápida

### Requisitos
- Docker y Docker Compose instalados
- 4 GB de RAM mínimo recomendado

### Pasos

```bash
# 1. Clona este repositorio
git clone https://github.com/javierlopezparra/CodiceTeX.git
cd CodiceTeX

# 2. Inicializa la configuración
./bin/init

# 3. Levanta los servicios
./bin/up
```

Abre tu navegador en `http://localhost/launchpad` y crea tu cuenta de administrador.

> 📖 Consulta la [Guía de instalación completa](docs/instalacion.md) para configuración en servidores universitarios.

---

## 🎓 Plantillas disponibles

| Universidad | Estado | Archivo |
|-------------|--------|---------|
| UNAM | ✅ Disponible | `templates/unam/` |
| IPN | ✅ Disponible | `templates/ipn/` |
| UANL | ✅ Disponible | `templates/uanl/` |
| UAM | 🚧 En progreso | — |
| UdeG | 🚧 En progreso | — |
| BUAP | 🚧 En progreso | — |
| Tu universidad | ❓ ¡Contribuye! | — |

¿No está tu universidad? [Contribuye con tu plantilla](#-cómo-contribuir) y ayuda a más estudiantes.

---

## 📚 Guías para tesistas

- [Cómo instalar y configurar CodiceTeX](docs/instalacion.md)
- [Tu primera tesis en LaTeX desde cero](docs/primera-tesis.md)
- [Cómo usar la plantilla de tu universidad](docs/plantillas.md)
- [Preguntas frecuentes](docs/faq.md)

---

## 🤝 Cómo contribuir

¡Las contribuciones son el corazón de CodiceTeX! Puedes ayudar de muchas formas:

### Agregar la plantilla de tu universidad
1. Haz **fork** de este repositorio
2. Crea una carpeta `templates/nombre-universidad/`
3. Agrega tu plantilla `.tex` y un `README.md` explicando cómo usarla
4. Abre un **Pull Request**

### Mejorar la documentación
- Corrige errores en las guías existentes
- Escribe tutoriales nuevos en español
- Traduce contenido al portugués para Brasil

### Reportar errores
Abre un [Issue](https://github.com/javierlopezparra/CodiceTeX/issues) describiendo el problema.

Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para más detalles.

---

## 🗺️ Roadmap

- [x] Repositorio inicial y estructura del proyecto
- [x] Plantilla base UANL
- [ ] Plantillas para UNAM, IPN, UAM
- [ ] Guía de instalación en servidor universitario
- [ ] Documentación completa en español
- [ ] Demo en línea pública
- [ ] Asistente IA para redacción de tesis

---

## 📄 Licencia

CodiceTeX está publicado bajo la licencia **GNU Affero General Public License v3.0 (AGPL-3.0)**.

Está basado en [Overleaf Community Edition](https://github.com/overleaf/overleaf), también bajo licencia AGPL-3.0.

Esto significa que puedes usar, modificar y distribuir CodiceTeX libremente, siempre que mantengas el código abierto.

---

## 🙏 Reconocimientos

- [Overleaf](https://github.com/overleaf/overleaf) por crear y mantener el editor open source en el que se basa este proyecto
- A todos los estudiantes de universidades públicas de México y Latinoamérica que inspiran este proyecto

---

<p align="center">
  Hecho con 🪶 en México · <strong>Universidad Autónoma de Nuevo León</strong>
</p>
