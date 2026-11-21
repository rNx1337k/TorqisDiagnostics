<p align="center">
  <img src="imagens/banner.png" alt="Torqis" width="100%">
</p>

<p align="center">
  <b>Português</b> · <a href="README.en.md">English</a>
</p>

<p align="center">
  <a href="https://github.com/rNx1337k/Torqis-download/releases/latest"><img src="https://img.shields.io/github/v/release/rNx1337k/Torqis-download?label=vers%C3%A3o&color=3D7BFF&style=flat-square" alt="Versão"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0E1526?style=flat-square&logo=windows" alt="Windows 10 | 11">
  <img src="https://img.shields.io/badge/estado-beta-E8343A?style=flat-square" alt="Estado: beta">
  <a href="https://www.instagram.com/torqis.pt/"><img src="https://img.shields.io/badge/Instagram-@torqis.pt-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram @torqis.pt"></a>
</p>

<p align="center">
  <b>Programa de diagnóstico para oficinas do grupo VAG</b> — Volkswagen, Audi, Seat e Škoda.
</p>

<p align="center">
  <a href="https://github.com/rNx1337k/Torqis-download/releases/latest"><img src="https://img.shields.io/badge/Descarregar_para_Windows-2F5BFF?style=for-the-badge&logo=windows&logoColor=white" alt="Descarregar para Windows"></a>
</p>

---

## Descarregar

Na página da [última versão](https://github.com/rNx1337k/Torqis-download/releases/latest), em **Assets**:

- **`Setup_Torqis_<versão>.exe`** — instala o programa, com atalhos no menu Iniciar e no ambiente de trabalho
  (recomendado)
- **`Torqis_<versão>_portatil.zip`** — versão portátil: extraia para qualquer pasta (até uma pen) e abra o
  `Torqis.exe`

Os ficheiros `.sig` são as assinaturas que o programa usa para confirmar as actualizações; não precisa deles.

> [!NOTE]
> Na primeira vez o Windows pode mostrar *"O Windows protegeu o PC"*: carregue em **Mais informações → Executar
> mesmo assim**.

Depois de instalado, o Torqis **actualiza-se sozinho**: só são instaladas versões assinadas pelo editor.

## O que faz

- **Auto-Scan com mapa do veículo** — lê todos os controladores e mostra no carro onde estão as avarias
- **Assistente de diagnóstico** — gravidade, causas prováveis e o que verificar em cada avaria
- **Valores em tempo real** em mostradores e gráficos
- **Funções de oficina** — ajustes básicos, adaptação, codificação, login, teste de saídas e reposição do indicador
  de revisão, com cada valor gravado lido de volta e o original guardado para repor
- **Relatórios para o cliente** com o logótipo da oficina, em PDF ou impressos
- **Histórico de diagnósticos e de clientes**, pesquisável por matrícula, VIN ou cliente
- **Simulador incluído** para experimentar tudo sem carro

| | |
|---|---|
| <img src="imagens/01_home.png" alt="Início"> | <img src="imagens/02_autoscan.png" alt="Auto-Scan"> |
| <img src="imagens/03_faults.png" alt="Avarias"> | <img src="imagens/04_live_data.png" alt="Valores em tempo real"> |

## O que precisa

- Um PC com **Windows 10 ou Windows 11 (64 bits)**
- Um cabo de diagnóstico:

| Cabo | Para |
|---|---|
| **Cabo KKL 409.1 com chip FTDI** (USB) | VW, Audi, Seat e Škoda até cerca de 2005 (linha K) |
| **OBDLink EX** (USB) | Grupo VAG com CAN, de cerca de 2005 em diante |
| **Interface J2534** (ex.: Scanmatik 2 PRO) | Grupo VAG, linha K (KWP2000) e CAN |

Os cabos fechados de outros programas (por exemplo os HEX do VCDS, Autocom, Delphi) não funcionam: o Torqis
reconhece-os e explica porquê.

## Licença

Os primeiros **14 dias** são um teste com tudo desbloqueado. Depois, sem licença, o programa passa a **modo
demonstração**: liga ao carro, identifica os controladores e diz que módulos têm avarias, mas mostra só parte das
avarias e dos valores e não altera nada no carro.

Para obter a licença: abra **Opções → Licença**, copie o **ID deste PC** e envie-o por mensagem no
[Instagram @torqis.pt](https://www.instagram.com/torqis.pt/). Cole a chave que receber e carregue em
**Activar licença**. A activação não precisa de internet.

## Estado

O Torqis está em **beta**. Todas as funções podem ser experimentadas com o simulador incluído e a validação em
carros reais está em curso. Os resultados simulados aparecem sempre identificados como tal.

## Contacto

Dúvidas, licenças, ou uma oficina que queira experimentar o Torqis em carros reais:
**[Instagram @torqis.pt](https://www.instagram.com/torqis.pt/)**.

---

<sub>Copyright © 2026. Todos os direitos reservados. Software proprietário: não pode ser copiado, modificado nem
redistribuído sem autorização escrita. VW, Audi, Seat e Škoda são marcas dos respectivos donos; o Torqis é um
produto independente, sem ligação à Volkswagen AG.</sub>
