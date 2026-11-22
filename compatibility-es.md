# Compatibilidad y alcance de pruebas

2026-11-22

| Equipo | Conexión | Verificación |
|---|---|---|
| iGPSPORT iGS630S | BLE | Probado: iGS630S |
| Garmin Edge 530 | Connect IQ + iPhone | Edge 530: un usuario confirmó la conexión. Faltan verificar firmware, uso prolongado con pantalla bloqueada y exportación FIT. |
| Otro equipo BLE | BLE | Cada modelo requiere pruebas. Admitir BLE no demuestra compatibilidad comprobada. |

Forzar el cierre, reiniciar, bloquear al quitarse el reloj y apagar la pantalla son estados distintos. Las pruebas con iGS630S confirmaron la reconexión tras reiniciar el equipo en ambos modos y las actualizaciones en segundo plano en modo iPhone. Los demás modelos requieren pruebas individuales.

## Garmin Edge 530

Edge 530 usa un campo Connect IQ. No enlaces SportHeart en su lista de sensores cardíacos.

Vincula el ciclocomputador en Garmin Connect y selecciónalo en Sport Heart Assistant / Ajustes / Frecuencia cardíaca Garmin.

2. Instala SportHeart y añade su campo a una pantalla de ciclismo.

Elige el puente del teléfono e inicia en el reloj. En iPhone, activa compartir en Frecuencia cardíaca Garmin.

Un recibo no confirma que se muestre el pulso. Comprueba la pantalla del ciclocomputador.

Este campo no sustituye al sensor nativo de Garmin ni garantiza el cálculo de carga de entrenamiento.

## iGPSPORT iGS630S

IGS630S: Configuración → Sensores → Agregar sensor → Frecuencia cardíaca.

Mantenga abierta la aplicación de iPhone para el emparejamiento inicial en modo iPhone. Los dos modos utilizan emisores diferentes y pueden requerir entradas de sensores guardadas por separado.

En las pruebas con iGS630S, mantener simultáneamente el enlace del equipo con su app del teléfono impidió a veces recibir datos de frecuencia cardíaca, aunque el sensor figuraba como conectado. Desconectar ese enlace, eliminar el sensor guardado y enlazarlo de nuevo restableció los datos. La causa no está confirmada; otros modelos pueden comportarse de forma distinta.

En el modo iPhone, desconecte únicamente el enlace de la aplicación complementaria del equipo. Deje activado el Bluetooth del iPhone y la conexión del reloj.

App Store: https://apps.apple.com/app/id6827442593

Connect IQ: https://apps.garmin.com/zh-CN/apps/0b750e18-5b36-4cc7-9470-b8f996dfa94a

Support: support-es.html
