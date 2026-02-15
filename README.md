# LiquidPyServer

Einfacher HTTP-Server, der die [liquidctl](https://github.com/liquidctl/liquidctl)-CLI als API bereitstellt.

## Zweck

Dient als Backend für [Kraken](https://github.com/ben-dev-su/Kraken), um NZXT-Wasserkühlungen aus einer C#-Anwendung heraus anzusteuern.

## Status

Abgelöst durch [FNCRS](https://github.com/ben-dev-su/FNCRS), welches direkt über USB-HID kommuniziert und keinen separaten Server benötigt.

## Technologie

- **Sprache:** Python
- **Abhängigkeit:** liquidctl

## Verwandte Projekte

- [Kraken](https://github.com/ben-dev-su/Kraken) – C#-Frontend, das diesen Server nutzt
- [FNCRS](https://github.com/ben-dev-su/FNCRS) – Nachfolgeprojekt
