<p align="center">
  <img src=".github/assets/banner.png" alt="Bip: assistente de voz para Windows" width="100%">
</p>

<p align="center">
  <a href="https://github.com/Idannyel/bip-download/releases/latest"><img alt="Versão" src="https://img.shields.io/github/v/release/Idannyel/bip-download?style=for-the-badge&label=vers%C3%A3o&color=b6f25c&labelColor=0e0e17"></a>
  <img alt="Windows 10 e 11" src="https://img.shields.io/badge/Windows-10%20%7C%2011-8fb4ff?style=for-the-badge&labelColor=0e0e17">
  <img alt="Grátis" src="https://img.shields.io/badge/pre%C3%A7o-gr%C3%A1tis-b6f25c?style=for-the-badge&labelColor=0e0e17">
  <a href="https://github.com/Idannyel/bip-download/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/Idannyel/bip-download/total?style=for-the-badge&label=downloads&color=ededf7&labelColor=0e0e17"></a>
</p>

<p align="center">
  <b>Diga “Bip” e peça. Ele entende, responde e faz.</b><br>
  Abre programas e jogos, toca músicas, cuida dos seus timers, tarefas e e-mails, sem tirar você do que está fazendo.
</p>

<p align="center">
  <a href="https://github.com/Idannyel/bip-download/releases/latest"><img alt="Baixar para Windows" src="https://img.shields.io/badge/%E2%AC%87%20Baixar%20para%20Windows-b6f25c?style=for-the-badge&logoColor=14200a&labelColor=b6f25c&color=b6f25c" height="44"></a>
</p>

---

## Visão geral

O Bip é um assistente de voz para Windows, em português do Brasil. Ele fica encostado na borda da tela como uma pílula pequena. Quando você chama, ele se abre, resolve o pedido e volta a ficar discreto.

<p align="center"><img src=".github/assets/pills.png" alt="A pílula do Bip em espera, com timer e respondendo" width="100%"></p>

## Recursos

| | Recurso | Exemplos do que dizer |
|:-:|---|---|
| 🎮 | **Programas e jogos** | “Abre o Cuphead na Steam”, “bora jogar GTA 5”, “abre o Excel” |
| 🎵 | **Música e vídeos** | “Toca Garota de Ipanema no YouTube”, “abre o canal do Felipe Neto”, “pausa” |
| ⏱️ | **Timers e foco** | “Timer de 10 minutos para a pizza”, “me acorda amanhã às 7”, “modo foco” |
| ✅ | **Tarefas e notas** | “Adiciona tarefa enviar proposta amanhã”, “anota que preciso ligar pro dentista” |
| ✉️ | **E-mail** | “Tenho e-mail novo?”, “responde a Ana dizendo que confirmo” (sempre pede confirmação) |
| 📁 | **Arquivos** | “Cria uma pasta Relatórios 2026 na área de trabalho”, “organiza a área de trabalho” |
| 🌐 | **Sites e informação** | “Abre o site do Mercado Livre”, “como está o clima?”, “quanto está o dólar?” |
| 📱 | **Celular** | Fale com o Bip pelo celular, no mesmo Wi-Fi |

## Telas

<p align="center"><img src=".github/assets/s-home.png" alt="Tela de início do Bip" width="100%"></p>
<p align="center"><img src=".github/assets/s-tasks.png" alt="Tarefas" width="100%"></p>
<p align="center"><img src=".github/assets/s-timers.png" alt="Foco e timers" width="100%"></p>
<p align="center"><img src=".github/assets/s-media.png" alt="Mídia" width="100%"></p>
<p align="center"><img src=".github/assets/s-groq.png" alt="Ajustes: entender melhor com o Groq" width="100%"></p>

## Instalação

1. Baixe o **`Bip-Setup-x.y.z.exe`** na [última versão](https://github.com/Idannyel/bip-download/releases/latest).
2. Abra o arquivo. Se o Windows mostrar **“O Windows protegeu o computador”**, clique em **Mais informações** e depois em **Executar assim mesmo**. O aviso aparece porque o instalador não tem assinatura paga da Microsoft.
3. Siga o instalador. Ele não pede administrador.
4. Na primeira vez, o Bip pergunta seu nome e como ele deve pensar:
   - **IA local (Ollama):** roda no seu PC, sem internet. Baixa alguns GB uma única vez.
   - **Groq (grátis, na nuvem):** entende melhor e responde mais rápido. Basta colar uma chave gratuita em **Ajustes → Entender melhor**.

O atalho **Bip** fica na área de trabalho e no Menu Iniciar. Para atualizar, instale a versão nova por cima: tarefas, notas e ajustes continuam.

## Requisitos

| | Mínimo | Recomendado |
|---|---|---|
| Sistema | Windows 10, 64 bits | Windows 11 |
| Memória | 4 GB (com Groq) | 8 GB ou mais (para a IA local) |
| Microfone | Qualquer um | Headset ou microfone de mesa |
| Internet | Para a voz falada e o Groq | Banda larga |

## Privacidade

- Suas tarefas, notas e ajustes ficam no seu PC, em `%APPDATA%\bip`.
- Chaves e senhas são criptografadas com a sua conta do Windows.
- Com a IA local, nada do que você pede sai do computador.
- Com o Groq ligado, sua voz e seus pedidos passam pelos servidores do Groq.
- E-mails só são enviados depois que você confirma.

## Perguntas frequentes

<details>
<summary><b>O Bip é pago?</b></summary>
Não. O Bip é grátis. A IA local e o plano gratuito do Groq também são.
</details>

<details>
<summary><b>Por que o Windows mostra um aviso ao instalar?</b></summary>
O instalador não tem um certificado de assinatura pago. Clique em <i>Mais informações</i> e depois em <i>Executar assim mesmo</i>.
</details>

<details>
<summary><b>Posso mudar a posição da pílula?</b></summary>
Sim. Em <b>Ajustes → Posição na tela</b>, escolha embaixo, em cima, à esquerda ou à direita. Você também pode arrastar a pílula até a borda que preferir.
</details>

<details>
<summary><b>Como desinstalo?</b></summary>
Configurações do Windows → Aplicativos → <b>Bip - assistente</b> → Desinstalar.
</details>

---

<p align="center">
  <img src=".github/assets/logo.png" alt="Bip" width="72"><br>
  <sub><b>Bip</b> · assistente de voz para Windows</sub>
</p>
