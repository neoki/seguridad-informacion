# Demostración Educativa: Prompt Injection en Navegadores con IA

## 📚 Descripción

Este repositorio contiene material educativo para demostrar vulnerabilidades de **Prompt Injection** en navegadores con asistentes de IA integrados (como Perplexity Comet, ChatGPT Atlas, etc.).

**Autor:** Prof. Pablo Alejandro Calviño Padín  
**Institución:** Universidad de A Coruña  
**Departamento:** Ciencias de la Computación e Inteligencia Artificial

## ⚠️ Advertencia

Este material es **exclusivamente educativo** y está diseñado para enseñar a estudiantes sobre vulnerabilidades en sistemas de IA. No debe usarse con fines maliciosos.

## 🎯 Objetivo Pedagógico

Demostrar cómo las instrucciones maliciosas pueden ser embebidas en páginas web aparentemente legítimas para manipular el comportamiento de asistentes de IA, basándose en vulnerabilidades reales documentadas por:

- **Brave Security Team** - Vulnerabilidades en Perplexity Comet
- **LayerX Security** - Ataque CometJacking
- **Chema Alonso** - Investigaciones sobre seguridad en IA

## 🚀 Cómo Usar (Para Estudiantes)

1. Abre el navegador con tu asistente de IA preferido (Perplexity Comet, ChatGPT con navegación, etc.)
2. Navega a la página: `https://TU-USUARIO.github.io/NOMBRE-REPO/`
3. Pídele al asistente que analice la página:
   - "Resume esta página"
   - "¿De qué trata este artículo?"
   - "Explícame el contenido de esta web"
4. Observa la respuesta del asistente

## 📖 Qué Deberías Ver

Si la demostración funciona, el asistente de IA debería:
1. Detectar las instrucciones embebidas
2. Alertarte sobre el prompt injection
3. Explicar los riesgos de seguridad
4. Mencionar casos reales como CometJacking

Si NO funciona, significa que:
- El asistente tiene protecciones efectivas contra prompt injection
- Las defensas implementadas por el proveedor están funcionando
- Esto también es educativo: ¡la seguridad está mejorando!

## 🔧 Instalación en GitHub Pages

### Opción A: Usar la Interfaz Web de GitHub

1. Crea un nuevo repositorio en GitHub
2. Nombra el repositorio (ej: `prompt-injection-demo`)
3. Hazlo **público**
4. Sube el archivo `index.html`
5. Ve a Settings → Pages
6. En "Source" selecciona `main branch`
7. Guarda los cambios
8. Tu página estará disponible en: `https://tu-usuario.github.io/prompt-injection-demo/`

### Opción B: Usar Git desde la Terminal

```bash
# 1. Crea un nuevo repositorio en GitHub (interfaz web)
# 2. Clona tu repositorio
git clone https://github.com/TU-USUARIO/NOMBRE-REPO.git
cd NOMBRE-REPO

# 3. Copia el archivo index.html al repositorio

# 4. Haz commit y push
git add index.html
git commit -m "Add prompt injection educational demo"
git push origin main

# 5. Activa GitHub Pages (Settings → Pages → Source: main branch)
```

## 📝 Referencias Técnicas

- [Brave: Agentic Browser Security - Indirect Prompt Injection in Perplexity Comet](https://brave.com/blog/comet-prompt-injection/)
- [LayerX: CometJacking Research](https://cybersecurefox.com/en/cometjacking-prompt-injection-perplexity-comet-ai-browser/)
- [OWASP Top 10 for LLMs](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [Chema Alonso: El Lado del Mal](https://www.elladodelmal.com/)

## 🛡️ Defensas Contra Prompt Injection

Las organizaciones pueden protegerse mediante:

1. **Separación de Contextos:** Distinguir entre instrucciones del sistema y contenido externo
2. **Validación de Input:** Analizar contenido antes de procesarlo con LLMs
3. **Clasificadores ML:** Detectar patrones de prompt injection
4. **Confirmación de Usuario:** Requerir aprobación para acciones sensibles
5. **Mínimo Privilegio:** Limitar capacidades del asistente de IA

## 📧 Contacto

Para preguntas sobre este material educativo:
- **Email:** pablo.calvino@udc.es
- **Institución:** Universidad de A Coruña

## 📄 Licencia

Este material educativo se proporciona "tal cual" con fines de enseñanza en ciberseguridad.

---

**Última actualización:** Noviembre 2025  
**Curso:** Seguridad Informática - Universidad de A Coruña
