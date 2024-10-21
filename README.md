# 🌟 Configuração Personalizada do Oh My Posh

Bem-vindo(a)! Este repositório contém **minha configuração personalizada** para o [Oh My Posh](https://ohmyposh.dev/). ✨

## 🚀 Sobre a Configuração

Este tema foi ajustado para exibir informações importantes como:
- 🖥️ Status do Git (branch, mudanças, etc.)
- 📁 Diretório atual
- 📦 Informações de ambiente como Node.js e Docker
- ⏰ Data e hora, e muito mais!

A combinação ideal de funcionalidade e estilo para quem passa muitas horas no terminal.

## 🔧 Pré-requisitos

1. **Oh My Posh** - Instale seguindo a [documentação oficial](https://ohmyposh.dev/docs/installation)
2. **Fonte Nerd Font** - Para exibir ícones corretamente. Recomendo [FiraCode Nerd Font](https://github.com/ryanoasis/nerd-fonts).
   
   > **Dica:** Você pode instalar outras Nerd Fonts também, caso queira uma variação visual.

## ⚙️ Instalação - Altere seu arquivo de configuração do shell:

No powershell execute: 
```bash
oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/rhuancsg/oh-my-posh/main/minhaConfig.json' | iex
```
No bash execute:
``` bash
eval "$(oh-my-posh init bash --config 'https://raw.githubusercontent.com/rhuancsg/oh-my-posh/main/minhaConfig.json')"
```
