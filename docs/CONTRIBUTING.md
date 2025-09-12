# Guía de contribuciones a HormigasAIS

¡Gracias por tu interés en contribuir al ecosistema HormigasAIS!

Este proyecto es colaborativo y abierto, pero sigue ciertas pautas para proteger los derechos de los autores y garantizar la calidad del trabajo conjunto.

## ¿Cómo contribuir?

1. **Forkea el repositorio** y crea tu propia rama para realizar cambios.
2. **Haz tus modificaciones** siguiendo las buenas prácticas de código y documentación.
3. **Asegúrate de que tus cambios no rompan la funcionalidad existente**.
4. **Agrega pruebas** si corresponde y actualiza la documentación técnica en la carpeta `docs/`.
5. **Realiza un Pull Request** detallando los cambios y el propósito de tu contribución.

## Código de conducta

- Sé respetuoso y profesional en todas las interacciones.
- Resuelve desacuerdos mediante el diálogo y la colaboración.
- Evita lenguaje ofensivo y conductas discriminatorias.

## Licencia y derechos de autor

- Todas las contribuciones se integran bajo la [Licencia MIT](LICENSE).
- Al enviar tu contribución principales y titulares de derechos.
- Los colaboradores serán reconocidos en la documentación y el historial del repositorio.

## Límites y uso estándar para desarrolladores

- responsables del proyecto.
- **Compatibilidad:** Las contribuciones deben ser compatibles con los estándares y dependencias definidos en la documentación técnica.
- **Seguridad:** No incluyas código malicioso, inseguro ni que comprometa la privacidad de los usuarios o la integridad del ecosistema.
- **Propiedad intelectual:** No subas material cuyo copyright no pertenezca a ti o cuya licencia sea incompatible con la MIT.
- **Desempeño:** Evita cambios que degraden el rendimiento general del sistema o introduzcan dependencias innecesarias.
- **Privacidad y datos:** No incluyas datos personales, credenciales, ni información sensible en el código ni en los archivos de configuración.
- **Automatización:** Los bots y scripts deben operar dentro de los límites definidos por la documentación y no deben realizar acciones abusivas dentro o fuera del ecosistema.

## Testing (pruebas)

- Todas las nuevas funcionalidades deben incluir pruebas unitarias y/o de integración.
- Utiliza los frameworks de testing recomendados en la documentación de `docs/`.
- Las pruebas deben ser automáticas y ejecutarse correctamente en el entorno de integración continua (CI).
- No aceptaremos código sin pruebas para funcionalidades críticas.

## Integración continua (CI)

- Todos los cambios deben pasar por los flujos de integración continua definidos en este repositorio (por ejemplo, GitHub Actions).
- El código debe superar todos los tests y análisis estáticos antes de ser fusionado.
- Si tu contribución requiere nuevas configuraciones de CI, documenta los cambios en `docs/ci.md`.

## Revisiones de seguridad

- Toda contribución debe ser revisada para evitar vulnerabilidades conocidas (inyección, XSS, CSRF, etc.).
- Si tu código interactúa con datos sensibles o usuarios finales, realiza una revisión de seguridad adicional.
- Informa cualquier vulnerabilidad encontrada a través de issues o por correo.

## Aspectos legales

- No incluyas software de terceros sin verificar compatibilidad de licencias.
- Todo el código propuesto debe ser original, o tener los permisos legales para integrarse bajo la Licencia MIT.
- Si usas código externo, cítalo y documenta la fuente en comentarios y en la documentación.

## Reporte de errores y sugerencias

- Usa la sección de [issues](../../issues) para reportar problemas, proponer mejoras o solicitar nuevas funcionalidades.
- Describe claramente el contexto, los pasos para reproducir el problema y adjunta evidencia si es posible.

## Preguntas y contacto

Si tienes dudas o deseas discutir ideas antes de contribuir, escribe a alguno de los correos vinculados en el archivo de configuración (`config/config.yaml`) o utiliza los canales oficiales de la organización.

---

¡Esperamos tus contribuciones para seguir mejorando HormigasAIS!
