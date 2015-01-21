# CicloviasDF
Trazo de la red de ciclovias y carriles con preferencia para ciclistas en el DF 

Para explicar el proceso realizado al crear este archivo se puede partir de dos escenarios iniciales posibles:

ESCENARIO 1.- La información base o inicial de la que se parte proviene de un trazado o dibujo en AutoCAD sin estar georreferenciado.
    Paso 1.- Primero debe descargarse un Sistema de Información Geográfica. Quantum GIS es un software de licencia libre que está disponible para Windows, Mac OS y Linux.
    Paso 2.- Si la información proviene de un CAD (Dibujo asistido por computadora), también es necesario instalar algún software CAD, el más común es AutoCAD pero no es software libre. También existen softwares libres de tipo CAD.
    Paso 3.- El archivo de CAD normalmente tiene una extensión (.dwg) si proviene de AutoCAD, este archivo debe ser guardado en .dxf (Drawing Extention Format). Para hacer esto, sólamente debe "guardarse como..." para cambiar la extensión. De preferencia, si se utiliza AutoCAD, debe guardarse en .dxf (R12) para aumentar su compatibilidad.
    Paso 4.- Una vez guardado en .dxf ya es posible ingrasarlo en un SIG, 
