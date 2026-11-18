
---
title: Guia de Comandos Git
---

# Guia de Comandos Git

O Git é um sistema de controle de versão utilizado para registrar e acompanhar alterações em projetos.

## 1. git clone

Realiza uma cópia de um repositório remoto para o computador local.

Exemplo:

```bash
git clone https://github.com/usuario/repositorio.git
```

## 2. git add

Adiciona arquivos à área de preparação (staging), selecionando as alterações que serão incluídas no próximo commit.

Exemplo:

```bash
git add .
```

## 3. git commit

Registra as alterações adicionadas à área de preparação, criando uma versão do projeto.

Exemplo:

```bash
git commit -m "Descrição das alterações"
```

## 4. git push

Envia os commits do repositório local para o repositório remoto.

Exemplo:

```bash
git push
```

## Resumo

- `git clone`: copia um repositório remoto.
- `git add`: prepara os arquivos modificados.
- `git commit`: registra as alterações.
- `git push`: envia as alterações para o GitHub.
