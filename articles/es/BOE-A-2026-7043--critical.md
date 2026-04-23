---
image_keywords: "sms, registry, fraud, telecommunications, security"
identifier: BOE-A-2026-7043--critical
original_article: BOE-A-2026-7043
last_updated: 2026-03-27
publication_date: 2026-03-27
---

# El nuevo Registro de Alias: ¿un escudo eficaz contra el fraude o un sistema con fisuras técnicas?

**La nueva normativa busca frenar las estafas por SMS y RCS mediante un registro centralizado, pero la facilidad para inscribirse mediante declaraciones responsables y el tratamiento especial de los mensajes internacionales podrían limitar su capacidad de protección real frente a estafadores profesionales.**

## El riesgo de la "buena fe" en la inscripción de alias

La Circular 1/2026 establece que, para usar un alias (el nombre que aparece como remitente en un mensaje), las empresas deben acreditar una vinculación legítima con su marca o nombre. Sin embargo, el apartado 5 del artículo quinto introduce una vía de entrada que merece atención: la posibilidad de acreditar la vinculación mediante una **declaración responsable** si el titular no posee una marca registrada o un dominio de internet a su nombre.

Esto puede facilitar que entidades que no tienen una presencia digital o legal robusta (como marcas nuevas o poco conocidas) obtengan un alias rápidamente. El riesgo práctico es que un actor malintencionado podría intentar registrar un alias que suene oficial o legítimo basándose únicamente en esta declaración de "uso habitual". 

Es importante matizar: la CNMC tiene la potestad de requerir documentación adicional en cualquier momento y de rechazar alias que causen confusión. Por tanto, **no se puede afirmar que el registro sea una puerta abierta al fraude**, pero sí que el sistema de validación inicial no es puramente documental, sino que permite una lectura más laxa de la legitimidad en favor de la agilidad administrativa.

## El desafío de los mensajes internacionales y el roaming

Uno de los puntos más complejos de la norma se encuentra en el tratamiento de los mensajes que llegan desde el extranjero. La circular obliga a bloquear mensajes con alias no registrados que lleguen a través de interfaces internacionales. No obstante, existe una excepción crítica: los usuarios que se encuentren en **itinerancia (roaming)**.

En estos casos, la norma no exige el bloqueo automático, sino que la CNMC establecerá la "actuación más adecuada". El texto prevé que, en lugar de bloquear el mensaje, el operador sustituya el alias por la etiqueta «NO VALIDADO». 

Este escenario abre un margen para la complejidad técnica. El riesgo práctico reside en que los estafadores suelen utilizar infraestructuras internacionales para ocultar su origen. Si un atacante logra identificar patrones de tráfico que aprovechen la excepción del roaming o la gestión de interfaces internacionales, podría encontrar una vía para que sus mensajes lleguen al destinatario, aunque sea con un identificador modificado. **No demuestra automáticamente que la norma sea ineficaz para el tráfico transfronterizo**, pero sí que la protección no es absoluta y depende de la capacidad de los operadores para distinguir el estado de itinerancia del usuario en tiempo real.

## La fragmentación de la responsabilidad en la cadena de envío

La norma describe una cadena de transmisión muy larga, con distintos roles: proveedores de origen (PRO), proveedores de tránsito y proveedores de terminación (operadores móviles). Cada uno tiene obligaciones de bloqueo específicas.

El riesgo práctico de este diseño es la posible dispersión de la responsabilidad. Si un mensaje fraudulento logra superar los filtros de un proveedor de origen o de tránsito, la carga de detección recae finalmente en el proveedor de terminación. Aunque la circular es muy precisa al definir qué debe bloquear cada actor, la existencia de tantos intermediarios (incluyendo "revendedores" y "agregadores") crea un ecosistema donde la supervisión de la trazabilidad total de un mensaje puede volverse compleja.

**No equivale por sí solo a que el sistema sea vulnerable**, ya que la circular obliga a guardar historiales de bloqueos y a remitir estadísticas a la CNMC. Sin embargo, la eficacia del control dependerá de que la CNMC pueda cruzar correctamente la información de todos estos eslabones para detectar patrones de fraude que no sean visibles para un solo operador.

## Conclusión: ¿qué vigilar?

Para que este Registro de Alias cumpla su objetivo de proteger al consumidor, la vigilancia ciudadana y experta debería centrarse en tres puntos:

1.  **La calidad de la validación:** Observar si la CNMC actúa de oficio para cancelar alias que, tras haber sido inscritos mediante declaración responsable, resultan ser fraudulentos.
2.  **La efectividad del etiquetado en roaming:** Vigilar si la sustitución por «NO VALIDADO» es suficiente para disuadir el fraude o si se convierte en un canal aprovechable.
3.  **La integridad de las estadísticas:** La utilidad de la norma dependerá de que los datos de mensajes bloqueados que remitan los operadores sean transparentes y permitan identificar si el fraude se está desplazando hacia los huecos que la ley no cubre.