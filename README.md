# Psats App Store

Tienda comunitaria de [Umbrel](https://umbrel.com) con las apps de Psats.

## Apps

- **llave-inglesa** — simulador offline de esquemas de custodia Bitcoin: qué te pueden robar, qué te haría perder
  los fondos y si tus herederos llegarían a ellos. Código, verificación y guía en
  [PrvsatsDev/llave-inglesa](https://github.com/PrvsatsDev/llave-inglesa).

## Añadirla a tu Umbrel

En la App Store de umbrelOS, abre las tiendas comunitarias (*Community App Stores*), pega la URL de este repositorio
(`https://github.com/PrvsatsDev/psats-umbrel-app-store`) y añádela.

llave-inglesa necesita **umbrelOS 2.0 o posterior**: se abre por HTTPS con el certificado de tu Umbrel (el navegador
puede avisar la primera vez), porque el cifrado del navegador solo funciona en un contexto seguro.

## Verificar la imagen

La imagen se construye en GitHub Actions desde el zip reproducible de la Release y sirve exactamente los ficheros de
su `SHA256SUMS`. Cómo comprobarlo, en
[umbrel/README.md](https://github.com/PrvsatsDev/llave-inglesa/blob/main/umbrel/README.md).
