# POCs-IA

Repositório agregador para estudos e provas de conceito de inteligência artificial.
Cada projeto será mantido em um repositório próprio e conectado aqui como submódulo Git.

## Objetivo

- Organizar POCs independentes sem misturar seus históricos.
- Reunir estudos de skills, MCP e outros experimentos de IA.
- Permitir que todos os projetos sejam obtidos a partir de um único repositório agregador.

## Estrutura

Neste momento, o repositório contém apenas esta documentação. Os diretórios dos estudos serão adicionados como submódulos conforme cada POC for criada.

## Pré-requisitos

- Git 2.51 ou compatível.
- Acesso aos repositórios privados referenciados pelos futuros submódulos.

## Instalação

Clone o repositório:

```powershell
git clone https://github.com/AlexandreJareck/POCs-IA.git
cd POCs-IA
```

Quando houver submódulos, inicialize-os com:

```powershell
git submodule update --init --recursive
```

## Uso

Cada diretório filho imediato representará uma POC independente. Consulte o `README.md` do projeto correspondente para seus comandos específicos.

## Validação

Confira o estado do agregador e de seus submódulos com:

```powershell
git status
git submodule status
```
