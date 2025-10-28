# Día #1 Aprendiendo a Programar JavaScript
## Tema: Variables

Para crear variables tenemos ```let``` ```const``` y ```var```. 
Cada uno tiene una función y diferencias y sirve para crear variables pero como dije, no son lo mismo cada uno tiene una diferencia y su función específica.
Por ejemplo:
```
let saludo1 = "HOLA JAVASCRIPT"
let saludo2 = 'HOLA JAVASCRIPT'
let saludo3 = `HOLA JAVASCRIPT`

const saludo4 = "HOLA JAVASCRIPT"
const saludo5 = 'HOLA JAVASCRIPT'
const saludo6 = `HOLA JAVASCRIPT`

var saludo7 = "HOLA JAVASCRIPT"
var saludo8 = 'HOLA JAVASCRIPT'
var saludo9 = `HOLA JAVASCRIPT`
```

Como pueden ver también estoy usando 3 tipos de Comillas. Camillas dobles (" "), Comillas simples (' ') y Comillas invertidas(``).
Entonces si tu duca es si se pueden usar estas 3 Comillas si pero con cuidado porque no las puedes combinar.

Por ejemplo:
```
// Incorrecto
let saludo10 = "HOLA JAVASCRIPT'
const saludo11 = 'HOLA JAVASCRIPT"
var saludo3 = `HOLA JAVASCRIPT"

// Corrrecto
let saludo14 = "HOLA JAVASCRIPT"
const saludo15 = 'HOLA JAVASCRIPT'
var saludo16 = `HOLA JAVASCRIPT`
```
Como se muestra en el ejemplo así se deberán de úsar. Si los usas de manera incorrecta pude dar un error, es indispensable usar solo un tipo de Comillas para todo el código para ser mejor entendible y tener buenas prácticas.

### Funciones del `let`, `const` y `var`

| Variable | Función |
| --- | --- |
| ```const``` | Declara variables de manera constante e inmutable se puede usar para todo|
| ```let``` | Declara variables que solo se puede utilizar en bloques y sirve para evitar sobre escrituras |
| ```var```| Declara variables entre el ámbito global y/o entre bloques |

### Comparativa entre `let`, `const` y `var`
| Variable | Ventaja | Desventaja |
| :---: | :--- | :--- |
| `const` | **Valor fijo.** Evita reasignaciones accidentales. Ámbito de bloque. | **No se puede reasignar.** No sirve para valores cambiantes. |
| `let` | **Reasignable.** Ámbito de bloque (seguro y predecible). | Permite reasignación (menos control que `const`). |
| `var` | Compatibilidad con navegadores muy antiguos. | **Ámbito de función** (Causa errores inesperados). Permite redeclaración. |

Ya que sabemos lo que son variables ahora tenemos que llamarlos y como las llamamos.

esto se puede ejecutar con ```console.log([variable])```
