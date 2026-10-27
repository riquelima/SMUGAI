# SMUG AI ⚡
### *O copiloto invisível de IA em tempo real para entrevistas e reuniões.*

[![Platform: macOS](https://img.shields.io/badge/Platform-macOS%2014.2%2B-black?style=for-the-badge&logo=apple)](https://apple.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-emerald?style=for-the-badge)](LICENSE)
[![Status: Production Ready](https://img.shields.io/badge/Status-Ativo-violet?style=for-the-badge)](https://github.com/riquelima/SMUGAI)

---

## 🎯 Visão Geral

O **SMUG** é um assistente de inteligência artificial de alta performance desenvolvido para quem precisa de respostas rápidas, sínteses estratégicas e resolução de problemas ao vivo durante entrevistas técnicas, alinhamentos executivos e negociações de alto impacto.

Diferente de bots tradicionais que entram na chamada como participantes, o **SMUG opera de forma 100% invisível diretamente no sistema operacional**, exibindo respostas e códigos através de uma sobreposição gráfica que **não aparece em gravações nem em compartilhamento de tela**.

> **"Veja as respostas. Ao vivo. Indetectável."**

---

## ✨ Principais Funcionalidades

### 🎙️ Escuta Ativa Sem Bots
- Captura o fluxo de áudio diretamente do sistema ou microfone.
- Zero participantes extras na sala — ninguém sabe que o SMUG está rodando.
- Transcrição simultânea em tempo real com identificação contextual de perguntas.

### 🛡️ Sobreposição 100% Invisível
- Renderização na camada de janelas nativa do macOS.
- **Proteção contra captura de tela:** Mesmo que você compartilhe a tela inteira no **Zoom, Google Meet, Microsoft Teams, Slack, OBS ou Loom**, a janela do SMUG permanece invisível para os outros participantes.
- Painéis translúcidos com transparência ajustável para você nunca perder o contexto do que está por trás.

### 👁️ Análise de Tela em Tempo Real (Vision)
- Aponte o assistente para qualquer trecho da sua tela.
- Lê e resolve exercícios de código (LeetCode, HackerRank, CoderPad), diagramas de arquitetura, planilhas financeiras ou slides com resposta em menos de 200ms.

### 💬 Pergunte em Paralelo (*Ask on the Side*)
- Precisa de uma fórmula específica, uma tradução rápida ou um conceito técnico que fugiu da memória?
- Acione o atalho rápido (`⌥ + P`), faça sua pergunta e obtenha o dado mastigado sem pausar a fala.

### 📝 Atas & Notas Inteligentes Automáticas
- Após encerrar a chamada, o SMUG gera uma síntese estruturada com principais decisões, respostas dadas e próximos passos.
- Exportação facilitada em **Markdown**, **PDF** ou compartilhamento direto.

### 🔒 Privacidade e Processamento Local
- Seus dados não são utilizados para treinamento de modelos de terceiros.
- Gravações e transcrições ficam armazenadas estritamente na sua máquina.
- Botão de desligamento imediato (*kill-switch*) e suporte a modo offline.

---

## 🖥️ Requisitos do Sistema

- **Sistema Operacional:** macOS 14.2 (Sonoma) ou superior.
- **Hardware Suportado:**
  - Toda a linha **Apple Silicon** (M1, M2, M3, M4 — Base, Pro, Max, Ultra).
  - Macs com processadores Intel compatíveis com macOS 14+.
- *(Versão para Windows em fase de desenvolvimento).*

---

## 🚀 Estrutura do Projeto & Deploy

O projeto foi construído para ser extremamente leve, rápido e pronto para deploy imediato no **Vercel** ou qualquer provedor de hospedagem estática.

```
SMUGAI/
├── index.html        # Landing page completa moderna em PT-BR com o simulador interativo
├── animacao.html     # Simulador standalone da ferramenta com controles
├── vercel.json       # Configurações de rotas limpas para deploy no Vercel
├── package.json      # Manifesto do projeto e scripts locais
├── .gitignore        # Arquivos ignorados para versionamento limpo
└── README.md         # Documentação e apresentação da ferramenta
```

### Deploy em 1 Clique no Vercel:

1. Importe o repositório [`https://github.com/riquelima/SMUGAI`](https://github.com/riquelima/SMUGAI) no painel do [Vercel](https://vercel.com).
2. O Vercel detectará automaticamente a configuração estática com `vercel.json`.
3. Clique em **Deploy** — seu site estará no ar em poucos segundos com certificado SSL e CDN global.

### Executar Localmente:
```bash
# Clone o repositório
git clone https://github.com/riquelima/SMUGAI.git
cd SMUGAI

# Inicie o servidor local
python3 -m http.server 3001
```
Abra `http://localhost:3001` no seu navegador.

---

## 📄 Licença

Distribuído sob a licença **MIT**. Consulte o arquivo para mais informações.
