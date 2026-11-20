# 1355-optimizer
<div align="center">

# 🎮 1355 Optimizer v2.1

**Painel de otimização Windows para jogos — standalone, open source, sem instalação**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://python.org)
[![Platform: Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078d6.svg)](https://microsoft.com/windows)
[![Build Status](https://img.shields.io/github/actions/workflow/status/edu1355/1355-optimizer/build.yml?label=Build)](https://github.com/edu1355/1355-optimizer/actions)
[![Release](https://img.shields.io/github/v/release/edu1355/1355-optimizer?label=Latest%20Release)](https://github.com/edu1355/1355-optimizer/releases)
[![Downloads](https://img.shields.io/github/downloads/edu1355/1355-optimizer/total?label=Downloads)](https://github.com/edu1355/1355-optimizer/releases)
[![Donate](https://img.shields.io/badge/Donate-PIX%20%7C%20Ko--fi-ff69b4.svg)](https://ko-fi.com/edu1355)
[![PIX](https://img.shields.io/badge/PIX-58843ac0--8947--4de5--b269--01b16d26428d-00a650.svg)](https://github.com/edu1355/1355-optimizer#doação)

<br>

<img src="https://raw.githubusercontent.com/edu1355/1355-optimizer/main/logo_1355.png" alt="1355 Optimizer Logo" width="180">

<br><br>

**Otimize seu PC para máxima performance em jogos** — CPU, RAM, GPU, Rede, Serviços, Energia, Tudo em um clique.

[📥 **Baixar .exe (Standalone ~16MB)**](https://uploadnow.io/files/R5D9x7v) · [📦 **Baixar .zip (Portable ~16MB)**](https://uploadnow.io/files/R5D9x7v) · [🐛 Reportar Bug](https://github.com/edu1355/1355-optimizer/issues) · [💡 Sugerir Feature](https://github.com/edu1355/1355-optimizer/issues) · [☕ Doar](PIX ALEATORIO) · [💳 PIX: `58843ac0-8947-4de5-b269-01b16d26428d`]

</div>

---

## ✨ Features

| Categoria | O que otimiza |
|-----------|---------------|
| 🎯 **Sistema & Prioridade** | Game Mode, GPU Scheduling (HAGS), Core Parking, CPU Priority |
| ⚡ **Energia & Performance** | Plano "Performance Máxima", PCIe ASPM Off, C-States, USB Suspend |
| 🧠 **Memória & Cache** | Compressão RAM, Standby List, Prefetch/Superfetch, Pagefile fixo |
| 🌐 **Rede & Latência** | Nagle Off, TCP Optimize (RSS/ECN), DNS Flush, QoS Jogos |
| 🎮 **Gráficos** | Fullscreen Optimizations |
| 🛠 **Ferramentas** | Limpeza Disco, SFC, Desfragmentar, Painel NVIDIA, Gerenciador Dispositivos, Monitor Recursos |

### 🌐 Dashboard Web Tempo Real
Acesse **`http://localhost:5000`** no navegador (ou celular na mesma rede) para monitorar:
- 🖥️ CPU total + por núcleo (barras animadas)
- 💾 RAM usada/total + %
- 🎮 GPU % + Temp (via GPUtil)
- 🌡️ Temp CPU (via WMI/OpenHardwareMonitor)
- 🌐 Rede Mbps real (upload + download)
- ⭐ Score de performance
- 🔥 Top 10 processos por CPU

### 🛡 Segurança & Confiabilidade
- ✅ **Ponto de restauração automático** antes de otimizações rápidas
- ✅ **Auto-save** — preferências salvas em `%APPDATA%\1355Optimizer\settings.json`
- ✅ **Log de auditoria** — `%APPDATA%\1355Optimizer\audit.log` (data/hora/ação/resultado)
- ✅ **Verificação real** — lê registro do Windows, não "acha que aplicou"
- ✅ **Botão "Restaurar Padrão"** — reverte tudo em 1 clique
- ✅ **EULA obrigatória** na abertura — aceite consciente dos riscos
- ⚠️ **Requer Administrador** — otimizações mexem em registro/serviços/energia

---


## 🚀 Instalação Rápida

### Opção 1: Executável Standalone (Recomendado)
```bash
# 1. Baixe o 1355_Optimizer.exe na aba Releases
# 2. Botão direito → "Executar como administrador"
# 3. Aceite a EULA → use
