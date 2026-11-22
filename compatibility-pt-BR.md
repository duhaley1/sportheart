# Compatibilidade e escopo dos testes

2026-11-22

| Equipamento | Conexão | Verificação |
|---|---|---|
| iGPSPORT iGS630S | BLE | Testado: iGS630S |
| Garmin Edge 530 | Connect IQ + iPhone | Edge 530: conexão confirmada por usuário. Firmware, uso prolongado com tela bloqueada e exportação FIT ainda precisam de verificação. |
| Outros equipamentos BLE | BLE | Outros modelos precisam de testes individuais. Suporte a BLE não comprova compatibilidade testada. |

Forçar o encerramento, reiniciar, bloquear ao retirar o relógio do pulso e apagar a tela são estados diferentes. Os testes com o iGS630S confirmaram a reconexão após reiniciar o equipamento nos dois modos e as atualizações em segundo plano no modo iPhone. Outros modelos exigem testes individuais.

## Garmin Edge 530

O Edge 530 usa um campo Connect IQ. Não emparelhe SportHeart na lista de sensores cardíacos.

Emparelhe no Garmin Connect e escolha o aparelho em Sport Heart Assistant / Ajustes / Frequência cardíaca Garmin.

2. Instale o SportHeart e adicione o campo à tela de ciclismo.

Escolha o modo ponte e inicie no relógio. No iPhone, ative o compartilhamento em Frequência cardíaca Garmin.

O recebimento não confirma a exibição. Confira a tela do ciclocomputador.

Este campo não substitui o sensor nativo Garmin nem garante cálculos de carga de treino.

## iGPSPORT iGS630S

IGS630S: Configurações → Sensores → Adicionar sensor → Frequência cardíaca.

Mantenha o aplicativo do iPhone aberto para o emparelhamento inicial no modo iPhone. Os dois modos usam transmissores diferentes e podem exigir entradas de sensores salvas separadamente.

Nos testes com o iGS630S, manter simultaneamente a conexão entre o equipamento e o app complementar do telefone às vezes impedia a chegada dos dados de frequência cardíaca, mesmo com o sensor conectado. Desconectar esse vínculo, remover o sensor salvo e emparelhar novamente restaurou os dados. A causa não foi confirmada; outros modelos podem se comportar de forma diferente.

No modo iPhone, desconecte apenas o link do aplicativo complementar do equipamento. Deixe o Bluetooth do iPhone e a conexão do relógio ligados.

App Store: https://apps.apple.com/app/id6827442593

Connect IQ: https://apps.garmin.com/zh-CN/apps/0b750e18-5b36-4cc7-9470-b8f996dfa94a

Support: support-pt-BR.html
