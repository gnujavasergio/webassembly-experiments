## Que es WebAssembly
- Es el nuevo codigo que se puede ejecutar en navegadores web modernos y proporciona nueva funciones y mejoras importantes en el rendimiento. 
[https://developer.mozilla.org/en-US/docs/WebAssembly](https://developer.mozilla.org/en-US/docs/WebAssembly)
- WebAsembly es una formato de instrucciones binarias para una maquina virtual basada en pilas.
- Wasm esta diseñado para que sea portable para la compilacion de lenguajes de alto nivel como C/C++, Rust que permite la implementacion en la web  para aplicaciones de cliente y servidor.

## Historia
- Comienza en abril 2015: WebAssembly Community Group
- Junio 2015: El grupo anuncia publicamente que estaban trabajando en un nuevo estandar llamado WebAssembly.
- Marzo 2016: El grupo anuncio su primera definicion de las caracteristicas principales que estaran en WASM
- Los navegadores principales empezaron a experimentar con el estandar.
- Octuber 2016 se lanzo el minimo producto viable para que la comunidad lo probara.
- MVP fue implementado por los principales navegadores.
- Enero 2017 la WCG eligio un logo.
![logo](images/image3.jpeg)
- Marzo 2017: Los principales navegadores Chrome, Edge, Firefox y Webkit llegaron a un consenso del Minimo Producto Viable para que no se realize mas funcionalidades sin tener experiencia en la implementacion.
- Agosto 2017 W3C WebAssembly Working Group grupo creado para poder desarrollar el estandar oficial de WASM. Su tarea fue crear los nuevos estandares de wasm para que puedan ser implementados por los proveedoes de navegadores web.
- Febrero 2018: Grupo presento las primeras especificaciones preliminares

## Quien esta desarrollando WASM
- 2015: WebAssembly Community Group
    - Representantes de los princiaples proveedores de navegadores y comunidad (900+ miembros) 
    - Fueron quienes impulsaron su evolución a implementar las versiones tempranas en los principales navegadores tambien fueron quienes implementaron los primeros estandares
- 2017: W3C WebAssembly Working Group
    - Contiene personas de Google, Apple, Facebook, Tencent, W3C, Mozilla, LG Electronics y mas.
    - Su tarea es crear estandares para WebAssembly que puedan ser utilizados por los principales navegadores.

## Porque WebAssembly
- Ejecutar codigo a una velicidad casi nativa.
    - Nota: Algunos test indican que es 20 veces mas rapido que javascript.
- Otros lenguajes como C/C++, C# se pueden compilar en WebAssembly
- Soporte nativo con los navegadores web y no se necesita de ningun plugin para su funcionamiento.
- Las aplicaciones wasm se ejecutan en un etorno seguro como javascript.
- El codigo de javascript puede ejecutar los modulos de wasm.

### WebAssembly es rapido
- WebAssembly es rapido puede ejecutar codigo mas rapido que javascript en la mayoria de los casos.
- WebAssembly ocila entre 6 a 20 veces en velocidad a Javascript no en todo los casos.
- Javascript puede ser muy rapido y tiene otros beneficios 
- Produce aplicaciones mas rapidas en general ṕorque el codigo de WebAssembly esta optimizado.
- Los archivos de WebAssembly son mas pequeños que los archivos javascript incluso mas pequeños que los archivos minificados de javascript. Esto es importante en la web porque los archivos tienen que descargarse al cliente.

### Compilar a WebAssembly con otros lenguajes de programación
- Hay una gran ventaja de que WebAssembly se puede ejecutar en el navegador ya que los navegadores se pueden ejectuar en cualquier plataforma y en cualquier dispositivo.
- No es necesario instalar un rutine en los navegadores para ejecutar WebAssembly.
- Habia un incoveniente de que solo se puede hacer aplicaciones con Javascript porque solo lo que sabian javascript podian hacer aplicaciones.
- Ahora con WebAssembly se puede utilizar otros lenguajes de programación como C/C++, Rust, Java, C#, etc.
- Un gran ventaja porque ahora hay mas desarrolladores para crear aplicaciones web. Esto es una revolucion para la werb.

### WebAssembly es parte del Navegador
- JavaScriot estaba limitado para editar Audio y Video o crear o ejecutar video juegos.
- Estas funcionalidades de editar Audio y Video, Juegos se podian implementar con plugins como Flash o Silverlight.
- El problema de utilizar plugins era que se tenia que actualizar la versiones de los plugins por problema de seguridad y esto hacia que los usuarios puedan problemas.
- La ventaja de WebAssenbly es que no se necesita instalar ningun plugins al navegador y se puede crear aplicaciones que antes con javascript no se podia como editar audio y video, crear video juegos y esta aplicaciones se podran en todos los navegadores y dispositivos que tengan el soporte de WebAssembly.

## Casos de uso de WebAssembly
- Para reautilizar cosas echas en C:
    - tesseract ocr
    - OpenCV
- - Cuando no quiero hacer algo en javascript.
    - C
    - C++
    - Rust
- Editar Video y Audio.
- Streaming de Video y Audio
- Juegos
- Conferencias de Video y Audi
- Realidad Aumentada y Realidad Virtual
- Inteligencia Artificial 
- [https://dev.to/yashints/tensorflow-js-available-on-webassembly-backend-53e4](https://dev.to/yashints/tensorflow-js-available-on-webassembly-backend-53e4)

## Seguridad de WebAssembly
- WebAssembly se ejecuta en un entorno encapsulado
- Se ejecuta con estrictas normas de ejecución
- Se protege al usuario de codigo malisioso

## Herramientas
- [https://webassembly.studio/](https://webassembly.studio/): Entorno de desarrollo online que permite crear aplicaciones con WebAssembly.
- [https://wasdk.github.io/wasmcodeexplorer/](https://wasdk.github.io/wasmcodeexplorer/)
- [https://github.com/dotnet/blazor](https://github.com/dotnet/blazor): Ejecutar C# en el navegador con WebAssembly

## Soporte navegadores
- [https://caniuse.com/#feat=wasm](https://caniuse.com/#feat=wasm)
![support](images/image2.png)

## Como usar WebAssembly
- Escribir WebAssemlby tu mismo
- Compilar codigo en WebAssembly como C/C++, Rust, C# 
- Utilizar los modulos de WebAssembly ya existentes en javascript

### Escribir WebAssembly tu mismo
![yourselft](images/image4.png)

### Compilar codigo en WebAssembly
![cplus](images/image5.png)

![cshap](images/image6.png)

### Utilizar los modulos de WebAssembly ya existentes en javascript 
![modules](images/image7.png)

### JavaScript trabaja con WebAssembly
- WebAssembly no es un remplazo es un complemento para JavaScript.
. WebAssembly no solo esta en el cliente puede estar en el servidor con Nodejs
![javascript-wasm](images/image8.png)

## Ejemplos
- Adobe PhotoShop
- Autodesk Autocad
- Google con Google Earth
- web-dsp
- [Figma](https://www.figma.com/blog/
- [Funkykarts](https://www.funkykarts.rocks/demo.html)

## Recursos
- [https://webassembly.org/](https://webassembly.org/): El recurso Oficial de WebAssembly
- [https://developer.mozilla.org/en-US/docs/WebAssembly](https://developer.mozilla.org/en-US/docs/WebAssembly): La documentacion de Mozilla para desarrolladores donde te muestra como comenzar.
- [http://wasmrocks.com/](http://wasmrocks.com/): Tutoriales y articulos utiles de WebAssembly.
- [https://codelabs.developers.google.com/codelabs/web-assembly-intro/index.html#0](https://codelabs.developers.google.com/codelabs/web-assembly-intro/index.html#0): Un codelab de WebAssembly con C.
- [https://github.com/appcypher/awesome-wasm-langs](https://github.com/appcypher/awesome-wasm-langs): Implementación de WebAssembly en los diferentes lenguajes.
- [https://www.youtube.com/watch?v=VS4uhnKd67Y](https://www.youtube.com/watch?v=VS4uhnKd67Y): Video tutorial muy bueno de WebAssembly