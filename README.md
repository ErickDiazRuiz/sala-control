# Sala de control · Alemania

Simulador interactivo para operar una red de transmisión alemana simplificada en tiempo real, desde el navegador.

**Abrir:** https://erickdiazruiz.github.io/sala-control/

## Qué incluye
- 56 subestaciones en 380, 220 y 110 kV, agrupadas en las cuatro zonas de control: Amprion, TenneT, 50Hertz y TransnetBW.
- Dobles ternas operables circuito por circuito, transformadores con cambiador de tomas y desfasadores (PST) en las fronteras con Países Bajos y Polonia.
- Enlaces HVDC: SuedLink (DC4 y DC5), SuedOstLink, Ultranet, A-Nord, NordLink, Baltic Cable, Kontek, ALEGrO y la exportación de la eólica marina del Mar del Norte.
- Interconexiones AC con siete países. El resto de Europa continental se representa como un equivalente con su propia inercia y reserva primaria.
- Flujo de potencia AC Newton-Raphson resuelto 10 veces por segundo, con límites de reactiva e islas eléctricas independientes (cada isla tiene su frecuencia y su fase; el cierre entre islas pasa por un sincro-check).
- Flexibilidad: baterías, bombeo, vehículos eléctricos V2G, electrolizadores, power-to-heat, demanda industrial flexible, curtailment de renovables, STATCOM, compensador síncrono, reactores y capacitores.
- Perfiles diarios de demanda (residencial, comercial e industrial), sol según la estación y viento por región.
- Perturbaciones aleatorias o programadas: descargas atmosféricas con reenganche, disparo de bloques, bloqueo de polos HVDC, frentes de viento y nubes, saltos de carga y cambios de programa.
- Protecciones: sobrecarga de tiempo inverso, deslastre por subfrecuencia, LFSM-O y disparo por frecuencia.

## Cómo se usa
Toca cualquier elemento para abrir su ventana de control. Haz doble clic sobre un interruptor (■) para abrirlo o cerrarlo. Arrastra para mover el plano y usa la rueda o los botones para el zoom.

El modelo está inspirado en la red real de 2026. Las ubicaciones, los corredores y las potencias son aproximados y agregados por región.
