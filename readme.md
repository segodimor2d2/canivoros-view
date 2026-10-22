# canivoros-view

## Principales sistemas empresariales

| Sigla | Nombre | Función principal |
| --- | --- | --- |
| ERP | Planificación de recursos empresariales | Gestión integrada de inventario, ventas, compras, finanzas y operaciones |
| CRM | Gestión de relaciones con los clientes | Gestión de clientes, contactos, oportunidades comerciales y relaciones |
| PDV / POS | Punto de venta | Registro de ventas, pagos y emisión de comprobantes |
| WMS | Sistema de gestión de almacenes | Gestión de almacenes, ubicación y movimientos del inventario |
| OMS | Sistema de gestión de pedidos | Gestión de pedidos, desde la compra hasta la entrega |
| PIM | Gestión de información de productos | Gestión centralizada de la información y los catálogos de productos |
| E-commerce | Comercio electrónico | Tienda online, carrito, proceso de pago y pedidos |

## ¿Cómo se relacionan estos sistemas?

### ERP — Gestión central de la empresa
Productos · Inventario · Ventas · Finanzas · Compras

### E-commerce
Tienda online

### CRM
Clientes

### PDV / POS
Tienda física

---

La principal diferencia es:

- CRM (Customer Relationship Management): gestiona la relación con los clientes, las oportunidades comerciales y las ventas.
- ERP (Enterprise Resource Planning): gestiona los recursos y procesos internos de la empresa, como inventario, compras, finanzas, producción y facturación.

## Comparación entre CRM y ERP

| Funcionalidad          | CRM                | ERP      |
| ---------------------- | ------------------ | -------- |
| Registro de clientes   | Sí                 | Sí       |
| Historial de contactos | Sí                 | Limitado |
| Embudo de ventas       | Sí                 | A veces  |
| Control de inventario  | Raramente          | Sí       |
| Compras y proveedores  | Raramente          | Sí       |
| Control financiero     | Limitado           | Sí       |
| Emisión de facturas    | Raramente          | Sí       |
| Gestión de producción  | No suele incluirse | Sí       |
| Marketing y campañas   | Sí                 | A veces  |

## ¿Cómo trabajan juntos CRM, ERP y comercio electrónico?


## Ejemplos de sistemas

| Sistema     | Tipo                             |
| ----------- | -------------------------------- |
| Odoo        | ERP + CRM + comercio electrónico |
| ERPNext     | ERP + CRM                        |
| HubSpot CRM | CRM                              |
| Salesforce  | CRM y soluciones empresariales   |
| Bling       | ERP                              |
| WooCommerce | Comercio electrónico             |

## ¿Cuál sería mejor para tu empresa?

Pensando en una empresa que comercializa alimentos para perros, podrías utilizar:

1. eCommerce: tienda virtual donde los clientes realizan sus compras.
2. ERP: controla el inventario, la compra de materias primas, la producción, los pedidos y la facturación.
3. CRM: administra clientes, distribuidores, negociaciones y oportunidades de venta.

---

## Alcance de la conversación

Las respuestas permiten describir cómo se compra, recibe y utiliza la materia prima, además de identificar problemas de inventario, devoluciones y mantenimiento. Todavía falta completar el recorrido hasta la venta, entrega y cobro al cliente.

El archivo reúne explicaciones del responsable y análisis elaborados posteriormente. Este documento distingue lo que se relató de lo que se propone incorporar al sistema. Las cantidades son aproximadas y los fragmentos confusos quedan pendientes de confirmación.

## Compras: el abastecimiento depende de lo que haya disponible

La fábrica utiliza cabezas de pollo, barriga de salmón, huesos de canilla de cerdo y vísceras de cerdo. Trabaja con varios proveedores y busca nuevas fuentes de suministro de forma permanente.

La aclaración más concreta sobre las compras es: «El acuerdo con los proveedores es: tráiganos lo que tengan». La disponibilidad de estos subproductos es limitada. Si la empresa necesita aumentar el abastecimiento, debe incorporar más proveedores; no puede dar por hecho que los actuales entregarán más cantidad.

Los proveedores habituales llegan principalmente los viernes. Antes coordinaban por WhatsApp; actualmente algunas entregas se reciben sin una confirmación previa de cantidad. Los empleados pesan el material y comunican el resultado para realizar el pago.

Las bolsas, los empaques y los materiales de limpieza se compran por otro procedimiento: el responsable revisa lo que hace falta y compra aproximadamente una vez por semana.

### Qué debe resolver el ERP

Registrar una recepción aunque no exista una orden de compra previa. La operación necesita conservar quién entregó, qué material llegó, cuánto se aceptó y cuánto se pagó. Las compras planificadas también deben poder registrarse, especialmente para empaques y otros insumos.

El catálogo de proveedores debe indicar qué materiales suministra cada uno y conservar el historial de cantidades y precios. Esto permitirá conocer la dependencia de cada proveedor y evaluar alternativas cuando falte un ingrediente.

**Falta confirmar:** nombres y datos de proveedores, responsable de compra, autorización, límites de recepción y especificación de cada materia prima. La frase «recibimos lo que tengan» no define qué hacer cuando no hay espacio o el material no cumple las condiciones de aceptación.

## Cantidades, precios y pago

Se mencionaron aproximadamente 300 kg de huesos, una tonelada de salmón y la intención de recibir una tonelada o más de pollo. Para los materiales de cerdo se señaló que se recibe lo disponible. Estas cifras no tienen una frecuencia suficientemente clara para convertirlas en una compra semanal estándar.

El relato sugiere mejores precios por volumen para pollo y salmón y un precio que no cambia con la cantidad para ciertos materiales de cerdo. No hay tarifas ni descuentos confirmados.

Los proveedores transportan la mercancía hasta la fábrica sin cobrar flete por separado, según las condiciones descritas. El pago se realiza inmediatamente después del pesaje y la recepción.

### Qué debe resolver el ERP

Cada compra debe conservar el precio aplicado en esa fecha, la cantidad aceptada, el importe, cualquier flete separado y el comprobante de pago. Actualizar el precio de un proveedor no debe modificar compras anteriores.

Recepción y pago deben quedar vinculados, aunque se registren el mismo día. Si existe diferencia entre lo informado por el proveedor y el peso aceptado, debe quedar visible.

**Falta confirmar:** precios por kilogramo, descuentos, documentos utilizados, medio de pago, responsable del pago y posibles excepciones al pago inmediato.

## Recepción: se pesa y se revisa el material

La materia prima se recibe en kilogramos. Los empleados revisan el peso, que el material esté frío, su coloración y su apariencia. La preocupación es evitar que se entregue material inadecuado como si fuera aprovechable.

Los ingresos se describen como congelados, aunque en algunas respuestas se utilizan las palabras «frío» y «fresco». No se informó una temperatura medida ni un criterio técnico por ingrediente. La referencia a un color rosado tampoco puede aplicarse a todos los materiales sin aclaración.

El material llega sin etiqueta. No quedó establecido si el proveedor entrega otra identificación o documentación.

### Qué debe resolver el ERP

La recepción debe registrar fecha, proveedor, material, peso recibido, peso aceptado, responsable y resultado de la revisión. Debe permitir documentar rechazos y diferencias.

Cada ingreso necesita una identificación interna que acompañe al material hasta producción. Si el proveedor informa un lote, se conserva por separado y se vincula con esa identificación. La falta de etiqueta no debe impedir reconstruir el origen de una entrada.

**Falta confirmar:** tara, peso neto, medición de temperatura, criterios de aceptación, documentos del proveedor y tratamiento de rechazos parciales o totales.

## Cuarto frío: mucha rotación y poco registro del saldo

La capacidad declarada es de seis toneladas y se reciben aproximadamente cuatro toneladas por semana. El material suele empezar a procesarse el mismo día o al siguiente. Aunque se describe un consumo rápido, también se mencionan permanencias de ocho a diez días.

La separación se realiza mediante canastillas: azules para pollo, verdes para cerdo y blancas para salmón. Antes se utilizaba primero lo que estaba más cerca de la puerta; no quedó definida una regla actual por fecha de ingreso o vencimiento.

El control se apoya en la entrada y salida frecuente de producto y en la relación entre compras y ventas. No se describió un registro físico detallado de existencias. También se relataron fallas del cuarto frío que ocasionaron descartes.

### Qué debe resolver el ERP

Mostrar cuánto queda de cada material y de cada ingreso. Registrar entradas, salidas hacia producción, transformaciones, ajustes y pérdidas. La molienda debe mantener la relación con los materiales de origen, incluso cuando se mezclen varios ingresos.

La ocupación debe calcularse con las existencias simultáneas. Recibir cuatro toneladas durante una semana no significa mantener cuatro toneladas almacenadas todo el tiempo.

Las fallas de refrigeración deben quedar asociadas a fechas, materiales afectados y cantidades descartadas. La afirmación de que el material puede durar un año congelado queda pendiente de soporte técnico; no se utilizará como vencimiento automático.

**Falta confirmar:** capacidad útil, temperaturas, ubicaciones, condiciones de conservación, regla de rotación y procedimiento de conteo físico.

## Producción: existe una merma estimada, falta medirla por lote

El ejemplo utilizado fue una entrada de 50 kg con una pérdida de entre 4 y 6 kg. Para sus cálculos, la empresa suele considerar 5 kg de pérdida y 45 kg de salida. Esto equivale a un rendimiento estimado del 90 % en ese ejemplo.

No se aclaró si aplica a todas las recetas, qué ingredientes incluye el peso inicial ni en qué momento se pesa el resultado. La explicación sobre empaques, hamburguesas y secado requiere revisión.

### Qué debe resolver el ERP

Registrar el consumo real de ingredientes y el peso obtenido en cada lote. Comparar el rendimiento esperado con el medido y separar pérdida de proceso, descarte y diferencia de pesaje.

El sistema puede utilizar el ejemplo como una estimación identificada, pero no descontar automáticamente un 10 % de toda la producción. También debe distinguir peso de producto y peso de empaque.

**Falta confirmar:** recetas, etapas, tiempos, equipos, puntos de pesaje y equivalencia en gramos de la «libra» utilizada en las ventas.

## Devoluciones y suministro al criadero

Las devoluciones se describen como poco frecuentes y se destinan a los perros del criadero. Su cantidad se descuenta del alimento que normalmente se retiraría de la fábrica.

Se mencionaron 130 kg mensuales como referencia. Por ejemplo, las devoluciones podrían reducir la entrega adicional a 120 kg o 115 kg. La cantidad de perros cambia y el control se vuelve menos preciso. También existe una mensualidad pagada por el criadero, pero no quedó claro cómo se relaciona con los descuentos.

### Qué debe resolver el ERP

Separar la devolución del cliente, la evaluación del producto, su destino y el suministro al criadero. Registrar cantidades físicas y ajustes monetarios de forma independiente, con una relación clara entre ellos.

El destino de una devolución debe quedar autorizado y registrado antes de liberar el producto. El saldo del criadero no debe modificarse automáticamente sin conocer la regla del descuento.

**Falta confirmar:** motivos de devolución, condiciones del producto, compensación al cliente, relación comercial con el criadero y cálculo de la mensualidad.

## Máquinas: la prioridad operativa

El funcionamiento de las máquinas fue señalado como el principal problema de la empresa y la causa que más afecta el ciclo de producción.

El ERP debe permitir registrar equipo, falla, inicio y fin de la parada, reparación, repuestos, costo y producción afectada. Con ese historial se podrá identificar dónde se concentran las interrupciones y organizar el mantenimiento.

**Falta confirmar:** equipos instalados, fallas frecuentes, responsables, asistencia técnica, repuestos críticos y mantenimiento que ya realizan.

## Control financiero

El responsable relaciona lo pagado por materia prima con las ventas cobradas durante la semana siguiente. Esto describe la circulación del dinero, pero no permite calcular el costo de fabricación ni el margen.

La frase sobre compras y ventas de nueve o diez millones contiene un error de transcripción. Debe aclararse antes de utilizarla en cualquier cálculo.

El ERP tendrá que distinguir compras, pagos, inventario, consumo de producción, ventas y cobros. Cada movimiento debe poder consultarse con su documento de origen. Para calcular costos completos faltan empaques, mano de obra, servicios, mantenimiento y otros gastos de operación.

## Alcance inicial propuesto

| Área | Resultado que se espera del sistema |
| --- | --- |
| Proveedores y compras | Saber a quién se compró, qué se recibió y a qué precio |
| Recepción | Conservar pesaje, revisión, responsable e identificación del ingreso |
| Inventario | Consultar saldo y movimientos por material e ingreso |
| Producción | Relacionar ingredientes consumidos, lote fabricado y rendimiento |
| Pagos | Reconstruir cuánto se pagó y a qué recepción corresponde |
| Devoluciones y criadero | Separar producto devuelto, destino y ajuste comercial |
| Mantenimiento | Conocer paradas, reparaciones, costos y equipos más afectados |

Este alcance todavía no cubre todo el ERP. Falta levantar pedidos, precios de venta, inventario terminado, despacho, distribuidores, facturación y cobro al cliente.

## Próximos pasos del levantamiento

La siguiente conversación debería centrarse en tres ejemplos reales: una entrega de materia prima, un lote fabricado y una devolución. Para cada uno conviene recoger fechas, pesos, personas, documentos y movimientos de dinero.

En paralelo, hace falta revisar las máquinas que más fallan y completar el proceso comercial hasta la entrega y el cobro. Con esa información se podrá acordar qué entra en la primera versión del ERP y qué queda para una etapa posterior.


---

```bash
cd /home/segodimo/10php/canivorosview/ | term
```
---
