![Icono de Catastro Pro](assets/icon.png)

# Catastro Pro

## Una referencia. Una ficha clara.

Prepara una ficha de datos catastrales públicos con superficies, uso, construcción y coordenadas según la documentación disponible.

**Edición de instrucciones 0.5.0** · **Fuente: Dirección General del Catastro** · **MIT para las instrucciones**

Esta habilidad guía al asistente para leer fuentes oficiales y documentos del usuario. Usa las funciones nativas de navegación y archivos que su anfitrión ya tenga autorizadas. No añade herramientas de consulta propias, procesos ni servicios; no requiere código, dependencias, cuentas ni claves de API del editor.

## Cómo usarla

Carga o comparte [SKILL.md](skills/catastro-pro/SKILL.md) en un anfitrión que admita instrucciones o habilidades. No hace falta ejecutar ni instalar software adicional. El anfitrión decide cómo cargar instrucciones y qué funciones puede usar. La existencia de un paquete no acredita aceptación en su directorio.

Empieza con una pregunta concreta o aporta los documentos que quieras revisar:

> Consulta la referencia 2749704YJ0624N0001DI y separa superficie construida y de parcela.

> Explica qué comprueba esta ficha y qué requiere Registro o Urbanismo.

> Dame las coordenadas indicando longitud, latitud y sistema de referencia.

Si hay navegación autorizada, el asistente abre las [fuentes oficiales](skills/catastro-pro/references/sources.md). Si no la hay, trabaja con tus documentos y señala lo que no puede verificar actualmente. Nunca debe simular una búsqueda ni utilizar una captura como si fuera actual.

## Qué entrega

Referencia y distinción inmueble/parcela; dirección oficial, uso, superficies con unidades y año; enlace al mapa/ficha; coordenadas con ejes y sistema cuando consten; fecha y origen de cada dato; discrepancias y comprobaciones separadas de Registro o Urbanismo.

Consulta el [procedimiento detallado](skills/catastro-pro/references/workflow.md) y las [reglas de acceso](skills/catastro-pro/references/runtime.md). Separa hechos documentales e interpretación; incluye enlaces y fechas para las afirmaciones relevantes.

## Alcance

Solo datos públicos no protegidos. No acredita propiedad, habitabilidad, valor o licencia urbanística. Un punto no delimita la parcela. Navarra y País Vasco utilizan sistemas separados.

## Ejemplo histórico

La [captura JSON](skills/catastro-pro/references/demo.json), el [informe guardado](examples/demo.md) y la [vista documental](docs/mcp-preview.html) son material histórico de ediciones anteriores, con captura 2026-10-20T16:59:24.537780+00:00. Son ejemplos de presentación, no consultas actuales. Sus campos técnicos se conservan para procedencia y no describen dependencias de esta habilidad.

## Privacidad y permisos

Las búsquedas nativas pueden comunicar términos públicos mínimos y la dirección de red del anfitrión a los proveedores elegidos. No envíes historiales, documentos privados ni credenciales para una consulta pública. La conservación de respuestas y archivos depende del anfitrión. La habilidad no amplía permisos, tramita solicitudes ni activa seguimiento.

[Privacidad](PRIVACY.md) · [Seguridad](SECURITY.md) · [Condiciones](TERMS.md) · [Soporte](SUPPORT.md) · [Revisión editorial](DEVELOPMENT.md) · [Descripción para directorios](SUBMISSION.md).

**English:** An instruction-only skill for reviewing Spanish official sources and user-provided documents with authorized native browsing and file tools. No custom execution service or programming runtime is required. Historical examples remain explicitly dated.

Un símbolo sencillo identifica la función y una pequeña bandera española marca su borde; no es un sello oficial. Producto independiente de Sami Halawa, sin afiliación con ninguna autoridad pública.
