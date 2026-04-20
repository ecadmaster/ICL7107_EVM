# ICL7107 Evaluation Module (EVM)

![ecl7107-3d](_media/ICL7107_EVM.gif)

Este repositorio contiene el diseño de hardware de una tarjeta de evaluación para el ICL7107, un convertidor analógico-digital (ADC) de 3.5 dígitos diseñado para controlar displays LED. Este proyecto se desarrolla como material de práctica para la asignatura Laboratorio de Electrónica II de la Universidad de Los Andes (ULA).

## Descripción del Proyecto

El ICL7107 es un circuito integrado ampliamente utilizado en la instrumentación electrónica, específicamente en la construcción de voltímetros y multímetros digitales. Esta placa permite a los estudiantes y entusiastas experimentar con el acondicionamiento de señales y la visualización de datos sin necesidad de realizar el cableado complejo en protoboard.

## Características Técnicas

- Conversor: ICL7107 (ADC Dual-Slope).
- Visualización: 3.5 dígitos para displays de siete segmentos (ánodo común).
- Alimentación: +5V DC vía microUSB, internamente contiene circuito inversor para el -5V DC.
- Ajustes: Potenciómetro de precisión para calibración de voltaje de referencia.
- Software de Diseño: KiCad EDA 7.0 (o superior).

## Esquema del Circuito

A continuación, se presenta el diagrama esquemático del sistema:

![ecl7107-sch](_media/ICL7107_EVM_SCH.png)

## Lista de Materiales (BOM)

Para ensamblar este módulo, se requieren los siguientes componentes:

- pendient por colocar -

Nota: La lista completa detallada se encuentra en el archivo ICL7107_EVM_BOM.csv

## Instalación y Uso

Clona el repositorio:

```git clone https://github.com/ecadmaster/ICL7107_EVM.git```

Abre el archivo .kicad_pro con KiCad para revisar el PCB o generar los archivos Gerber para fabricación.

Consulta la carpeta datasheets para entender los límites operativos del integrado.

## Contribuciones y Licencia
Este proyecto está bajo la licencia MIT. Las sugerencias de mejora para el entorno académico de la Escuela de Ingeniería Eléctrica son bienvenidas.
