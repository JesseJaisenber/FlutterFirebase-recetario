Los enlaces al respectivo código y video están en formato txt, ambos tienen un link que lo envían a una carpeta de Drive.

Si desea ejecutar la aplicación final desde su equipo, necesita instalar las dependencias de Firebase y FlutterFire en su equipo.

Debe abrir una terminal en la raíz del proyecto y ejecutar "flutter pub get" para instalar todas las dependencias necesarias que están especificadas en el archivo pubspec.yaml.

Si solamente quiere ver el funcionamiento general, sin que cargue los datos desde la BD, puede cambiar las líneas de código de lib/src/provider/recetas_provider.dart.

Solamente descomente las líneas que carga desde el JSON y quite lo relacionado con Firebase, de esta forma podrá ver el funcionamiento también, pero la data cargada en forma local.
