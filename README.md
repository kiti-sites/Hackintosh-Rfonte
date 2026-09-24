# Hackintosh Rfonte
> Esta configuração foi feita única e exclusivamente para a máquina em "Especificação".
## Especificação
* **Processador:** Intel Xeon E3-1270 v2
  * Arquitetura: Ivy Bridge
  * Núcleos: 4
  * Threads: 8
  * Socket: LGA1155
* **Placa-mãe:** Gigabyte GA-H61M-S2-B3 Rev. 1.0
  * Chipset: Intel H61
  * Firmware: BIOS Legacy
* **Memória RAM:** 16 GB DDR3
  * Configuração: 2 × 8 GB
  * Frequência: 1600 MHz
* **Placa de vídeo:** AMD Radeon RX 580 2048SP
  * Memória: 8 GB
* **Armazenamento:** Western Digital HDD SATA
  * Interface: SATA
  * Sistema de arquivos e capacidade: não especificados
* **Rede Ethernet:** Qualcomm Atheros AR8151
* **Adaptador USB/Wi-Fi:** Realtek RTL8192EU
**Configuração do Hackintosh**
* **Sistema operacional:** macOS Monterey 12.x
* **Bootloader:** OpenCore
* **Inicialização:** BIOS Legacy → OpenDuet → OpenCore
* **ACPI:** SSDT-EC, SSDT-IMEI, SSDT-PM, SSDT-RMNE e SSDT-SBUS
* **Principais kexts:** Lilu, WhateverGreen, VirtualSMC, SMCProcessor, SMCSuperIO, USBToolBox, UTBMap, RestrictEvents e NullEthernet
* **CpuTscSync:** desativado
* **AppleCpuPmCfgLock:** ativado
* **GPU:** aceleração gráfica configurada por meio do WhateverGreen

## O que funciona?
### Funções
* iCloud
* Ethernet

### Versões do macOS
* Big Sur
* Monterey (não testado o instalador)