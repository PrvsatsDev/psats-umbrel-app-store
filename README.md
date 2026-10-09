# Psats App Store

Tienda comunitaria de [Umbrel](https://umbrel.com) con las apps de Psats.

## Apps

- **llave-inglesa** — simulador offline de esquemas de custodia Bitcoin: qué te pueden robar, qué te haría perder
  los fondos y si tus herederos llegarían a ellos. Código, verificación y guía en
  [PrvsatsDev/llave-inglesa](https://github.com/PrvsatsDev/llave-inglesa).

## Añadirla a tu Umbrel

En la App Store de umbrelOS, abre las tiendas comunitarias (*Community App Stores*), pega la URL de este repositorio
(`https://github.com/PrvsatsDev/psats-umbrel-app-store`) y añádela.

llave-inglesa necesita **umbrelOS 2.0 o posterior**: se abre por HTTPS (`https://umbrel.local:4580`), porque el
cifrado del navegador solo funciona en un contexto seguro.

La primera vez, el navegador avisará de que la conexión **no es segura**: no conoce el certificado de tu Umbrel. La
conexión sí va cifrada. Para pasar: en Chrome, Edge o Brave, *Configuración avanzada → Acceder a umbrel.local (sitio no
seguro)*; en Firefox, *Avanzado… → Aceptar el riesgo y continuar*. Para que no avise más, instala el certificado de tu
Umbrel como de confianza en tu equipo.

## Verificar la imagen

La imagen se construye en GitHub Actions desde el zip reproducible de la Release y sirve exactamente los ficheros de
su `SHA256SUMS`. Cómo comprobarlo, en
[umbrel/README.md](https://github.com/PrvsatsDev/llave-inglesa/blob/main/umbrel/README.md).
