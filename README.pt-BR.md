# OpenClawRun

OpenClawRun é um app de barra de menu para macOS que permite gerenciar o OpenClaw Gateway **sem abrir o Terminal**.  
É uma ferramenta prática para facilitar a operação do dia a dia, para qualquer perfil de usuário.

**Idiomas:** [English](./README.md) | [日本語](./README.ja.md) | [简体中文](./README.zh-Hans.md) | [繁體中文](./README.zh-Hant.md) | [Português (Brasil)](./README.pt-BR.md)

## Download

👉 **Baixar o DMG mais recente**  
<https://github.com/yamajinoboru/OpenClawRun/releases/latest>

- Formato de distribuição: DMG
- Instalação: abra o DMG e mova o OpenClawRun para Applications
- Após iniciar: use o ícone na barra de menu para controlar o Gateway (Start / Restart / Stop)

## Início rápido (3 passos)

1. Baixe o DMG mais recente no link acima
2. Abra o OpenClawRun (o ícone aparece na barra de menu)
3. Clique em `Start Gateway` e depois abra `Open Chat` / `Open Dashboard`

## O que você pode fazer

- Executar `openclaw gateway start / restart / stop / status`
- Verificar conectividade localhost (`127.0.0.1:18789`)
- Diagnóstico em segundo plano a cada 30 segundos
- Recuperação automática (até 2 tentativas)
- Emergency Recovery (recuperação forçada)
- Copiar informações de diagnóstico
- Abrir rapidamente o fluxo de reporte de issues
- UI multilíngue (ja / en / zh-Hans / zh-Hant / pt-BR)

## FAQ

- **Abriu, mas continua sem responder.**  
  Execute `Emergency Recovery` pela barra de menu.

- **Stop/Restart está desativado.**  
  Isso é esperado quando o Gateway está parado. Execute `Start Gateway` primeiro.

- **Onde reporto bugs?**  
  <https://github.com/yamajinoboru/OpenClawRun/issues/new/choose>
