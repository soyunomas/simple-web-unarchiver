# 📦 Descompresor Web Simple ✨

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Demo](https://img.shields.io/badge/Demo-Live!-brightgreen)](https://soyunomas.github.io/simple-web-unarchiver/index.html)

Una aplicación web simple, del lado del cliente, para extraer archivos de formatos ZIP, TAR y GZ directamente en tu navegador. No se necesita procesamiento en el servidor para estos formatos. Construido con HTML5, Bootstrap 5 y JavaScript Vanilla.

---

🚀 **Demo:** [**¡Pruébalo en vivo!**](https://soyunomas.github.io/simple-web-unarchiver/index.html)

---

## ✨ Características

*   📂 Soporta archivos `.zip`, `.tar`, `.gz`, `.tgz`, `.tar.gz`.
*   💻 Procesamiento puro en el lado del cliente usando JavaScript (los datos no se suben al servidor para la extracción).
*   🖱️ Selección de archivos mediante Arrastrar y Soltar (Drag & Drop) o botón de Examinar.
*   📄 Lista el contenido del archivo comprimido.
*   💾 Permite descargar archivos individuales del archivo comprimido.
*   📱 Diseño responsivo usando Bootstrap 5.
*   🚫 **Nota:** *No* soporta formatos como `.rar`, `.7z`, `.bz2` debido a limitaciones del navegador y la falta de librerías fiables y fácilmente disponibles para el lado del cliente.

## 🛠️ Cómo Usar

Dado que es un archivo HTML autocontenido:

1.  Clona o descarga este repositorio.
2.  Abre el archivo `index.html` directamente en tu navegador web moderno.
3.  Arrastra y suelta tu archivo comprimido en el área designada, o haz clic en el botón "Selecciona un archivo" para buscarlo.
4.  El contenido se listará debajo, permitiéndote descargar los archivos individualmente.

## 💻 Tecnologías Utilizadas

*   🌐 HTML5 (Semántico)
*   🎨 Bootstrap 5 (para estilos y maquetación)
*   ✨ JavaScript Vanilla (ES6+)
*   📚 [JSZip](https://stuk.github.io/jszip/) (para manejo de `.zip`)
*   📚 [Pako](https://github.com/nodeca/pako) (para manejo de `.gz`)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.

```text
MIT License

Copyright (c) 2025 soyunomas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
