# Remix

Remix (también conocido como Browser-Solidity) es un compilador de Solidity basado en navegador e IDE.

Visite https://remix.ethereum.org para usar; siempre entregará la última versión.

# Uso offline
La rama de paginas-gh siempre tiene la ultima version de Remix. Tambien contien un archivo ZIP con toda la compilacion. Descarguelo para usarlo sin conexion.
Nota: contiene la ultima version de solidez disponible en el momento del empaquetado. No se admiten otras versiones de compilador
# Instalación
Instala npm y node.js (mira https://docs.npmjs.com/getting-started/installing-node), entonces hacer:

* Clonar git https://github.com/ethereum/browser-solidity
* cd browser-solidity

# Desarrollo
Ejecute nps start y abra http://127.0.0.1:8080 en su navegador. Luego abre tu editor de texto y comienza a desarrolar. El navegador se actualizara automaticamente cuando se guarden los archivos.
## Resolucion de problemas de construccion

Aqui hay algunas cosas a considerar si tiene problemas para contruir el paquete.
  * Asegúrese de tener la version correcta de node, npm y nvm. Puede buscar la version que se prueba en Travis CI.

`nodo --versión`  
`npm --versión`

  * En sistemas operativos basados en Debian como Ubuntu 14.94LTS, puede que necesite ejecutar apt-get install build-essential. Después de instalar build

# Test Unidad
Registre nuevos archivos de prueba unitaria en test / index.js. Las pruebas están escritas usando __cinta__.  
Ejecute las pruebas unitarias a través de: npm test  
Para pruebas locales de explorador sin cabezera ejecute npm run test-browser (Requiere selenium para instalarse - se puede hacer con npm run selenium-install)  
Ejecutar las pruebas unitarias a través de la prueba npm requiere al menos el nodo v7.0.0

# Pueba de navegador
Para iniciar las pruebas Selenium por el servicio Nightwatch la aplicación a través de un servicio local web
