# Winglyst 📦

**Winglyst** é uma interface desktop nativa, leve e ágil para o **Windows Package Manager (Winget)**. Gerencie, instale e atualize os seus softwares com um clique através de uma UI moderna e intuitiva, eliminando a necessidade de comandos no terminal.

---

## 🚀 Funcionalidades

* **Gestão Centralizada**: Liste todos os softwares instalados e identifique instantaneamente quais possuem atualizações disponíveis.
* **Update com um Clique**: Botão "Atualizar Tudo" para manter todo o seu ambiente de software em dia de forma automatizada.
* **Loja Integrada**: Pesquise e instale novos aplicativos diretamente do repositório oficial do Winget.
* **Terminal Transparente**: Acompanhe o progresso em tempo real com um painel de logs que reflete as saídas do Winget CLI.
* **Design Nativo**: Interface construída com foco em ergonomia e perfeitamente integrada à estética do Windows 11.

---

## 🛠️ Stack Técnica

O projeto utiliza uma arquitetura híbrida para garantir máxima performance e segurança:

* **Frontend**: [Svelte](https://svelte.dev/) + [Tailwind CSS](https://tailwindcss.com/)
* **Core/Backend**: [Rust](https://www.rust-lang.org/)
* **Bridge**: [Tauri](https://tauri.app/) (v2.0)

---

## ⚙️ Como funciona?

O Winglyst atua como um *wrapper* sobre o executável local do **Winget**. Ele utiliza o backend em Rust para invocar comandos de sistema de forma segura e faz o *stream* dos dados para a interface em Svelte, proporcionando feedback visual imediato sem o "bloat" de aplicações baseadas em navegadores convencionais.

---

## 📄 Licença

Este projeto é licenciado sob a licença **Creative Commons Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional (CC BY-NC-SA 4.0)**.

### Resumo dos termos:
* **Atribuição**: Você deve dar o crédito apropriado ao autor original.
* **Não Comercial**: Você **não pode** usar este material para fins comerciais.
* **CompartilhaIgual**: Se você alterar, transformar ou criar algo baseado neste material, deverá distribuir as suas contribuições sob a mesma licença que o original.

Para ler o texto completo da licença, visite: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.pt_BR)

---
Developed by Thiago Teles Pereira.
