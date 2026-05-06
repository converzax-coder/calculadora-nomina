# Calculadora de Nómina Colombia 2026

**Calculadora de Nómina Colombia 2026** es una página web sencilla, responsive e informativa que permite estimar el salario neto mensual de un trabajador en Colombia, las deducciones del empleado, los aportes del empleador, las prestaciones sociales y el costo mensual aproximado para la empresa.

La herramienta está pensada para trabajadores, empleadores, estudiantes, emprendedores y personas que quieran entender de forma rápida cómo se compone una nómina laboral en Colombia.

---

## Vista general

La calculadora permite ingresar datos básicos como salario mensual, horas extra, bonos o comisiones salariales, tipo de contrato y clase de riesgo ARL. Con esa información genera una estimación de:

* salario devengado;
* auxilio de transporte, cuando aplica;
* deducciones de salud y pensión;
* fondo de solidaridad pensional, cuando aplica;
* retención en la fuente estimada, cuando se activa;
* aportes del empleador;
* prestaciones sociales;
* costo mensual total para la empresa.

---

## Funcionalidades principales

* Cálculo de salario neto mensual estimado.
* Cálculo de salud del empleado al 4%.
* Cálculo de pensión del empleado al 4%.
* Auxilio de transporte automático si el salario básico no supera 2 SMMLV.
* Cálculo de horas extra diurnas con recargo del 25%.
* Inclusión de bonos o comisiones salariales.
* Selección de clase de riesgo ARL.
* Cálculo de aportes del empleador.
* Cálculo de cesantías, intereses sobre cesantías, prima y vacaciones.
* Opción para activar fondo de solidaridad pensional.
* Opción para activar retención en la fuente estimada.
* Opción para ingresar libranza o embargo.
* Botón para copiar resumen del cálculo.
* Diseño responsive para computador, tablet y celular.
* Página independiente de términos, condiciones y política de privacidad.

---

## Valores base utilizados

La calculadora está configurada con valores de referencia para Colombia 2026:

* **SMMLV 2026:** $1.750.905
* **Auxilio de transporte 2026:** $249.095
* **UVT 2026:** $52.374

> Estos valores pueden requerir actualización si cambia la normativa aplicable o si se usa la calculadora en años posteriores.

---

## Estructura del proyecto

```text
calculadora-nomina/
├── index.html
├── terminos.html
└── README.md
```

### `index.html`

Contiene la página principal de la calculadora, incluyendo:

* estructura HTML;
* estilos CSS;
* lógica JavaScript del cálculo;
* formulario de entrada;
* resultados;
* preguntas frecuentes;
* espacios preparados para publicidad.

### `terminos.html`

Contiene la página de:

* términos y condiciones;
* política de privacidad;
* tratamiento de datos personales;
* cookies;
* publicidad;
* limitación de responsabilidad.

### `README.md`

Documento de presentación del proyecto para GitHub.

---

## Cómo usar el proyecto

1. Descargar o clonar el repositorio.
2. Abrir el archivo `index.html` en el navegador.
3. Ingresar el salario mensual y los datos correspondientes.
4. Hacer clic en **Calcular nómina**.
5. Revisar el salario neto estimado, deducciones, prestaciones y costo empresa.

No se requiere instalación de dependencias, base de datos ni servidor backend. La calculadora funciona directamente en el navegador.

---

## Publicación con GitHub Pages

Para publicar el proyecto en GitHub Pages:

1. Crear un repositorio público en GitHub llamado `calculadora-nomina`.
2. Subir los archivos:

   * `index.html`
   * `terminos.html`
   * `README.md`
3. Ir a **Settings**.
4. Entrar a **Pages**.
5. En **Build and deployment**, seleccionar:

   * Source: `Deploy from a branch`
   * Branch: `main`
   * Folder: `/root`
6. Guardar los cambios.

La página quedará disponible en una URL similar a:

```text
https://TU-USUARIO.github.io/calculadora-nomina/
```

---

## Aviso importante

Esta calculadora es una herramienta de carácter **informativo y orientativo**. No reemplaza una liquidación oficial de nómina, una consulta jurídica, una asesoría contable, una asesoría tributaria ni la revisión de un profesional especializado.

Los resultados pueden variar según:

* tipo de contrato;
* jornada laboral;
* incapacidades;
* licencias;
* ausencias;
* recargos nocturnos, dominicales o festivos;
* beneficios extralegales;
* retención en la fuente;
* libranzas;
* embargos;
* acuerdos contractuales;
* cambios normativos.

Antes de tomar decisiones laborales, financieras, tributarias o empresariales con base en los resultados, se recomienda consultar con un contador, abogado laboralista, asesor tributario o área de nómina.

---

## Privacidad

La calculadora procesa los datos ingresados directamente en el navegador del usuario. En principio, no requiere registro ni almacena la información salarial ingresada en una base de datos propia.

Si el sitio integra herramientas de analítica, cookies o publicidad, estas pueden recopilar información técnica de navegación conforme a sus propias políticas.

Para más información, consultar el archivo:

```text
terminos.html
```

---

## Tecnologías utilizadas

* HTML5
* CSS3
* JavaScript
* Google Fonts
* GitHub Pages

---

## Estado del proyecto

Proyecto en desarrollo y mejora continua.

Próximas mejoras posibles:

* agregar más tipos de horas extra y recargos;
* incluir recargo nocturno;
* incluir dominicales y festivos;
* agregar exportación a PDF;
* agregar selector por año;
* mejorar cálculo de retención en la fuente con más variables tributarias;
* incluir modo claro / oscuro;
* integrar publicidad con Google AdSense.

---

## Licencia

Este proyecto puede usarse con fines educativos, personales e informativos. Si deseas reutilizarlo comercialmente, revisa primero los términos de uso definidos por el titular del proyecto.

---

## Autoría

Proyecto creado para una calculadora web de nómina en Colombia.

**Nombre del proyecto:** Calculadora de Nómina Colombia 2026
**Repositorio sugerido:** `calculadora-nomina`
