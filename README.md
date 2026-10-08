# POCs-IA

Repositório agregador de estudos e provas de conceito de inteligência artificial.
Os projetos mantêm históricos Git independentes e são vinculados a este repositório como submódulos.

## Objetivo

Centralizar o acesso às POCs de IA sem misturar código, dependências ou histórico de alterações entre os projetos.

## Projetos

| Projeto | Caminho | Descrição |
| --- | --- | --- |
| [Skills](https://github.com/AlexandreJareck/skills) | [`skills/`](./skills/) | Coleção de skills experimentais para Codex e agentes compatíveis com o formato `SKILL.md`. |

A relação acima corresponde aos submódulos registrados no arquivo [`.gitmodules`](./.gitmodules).

## Pré-requisitos

- Git 2.51 ou compatível.
- Acesso aos repositórios privados utilizados como submódulos.

## Instalação

Clone o repositório e inicialize seus submódulos:

```powershell
git clone https://github.com/AlexandreJareck/POCs-IA.git
cd POCs-IA
git submodule update --init --recursive
```

## Uso

Acesse o diretório do projeto desejado e consulte seu próprio `README.md` para conhecer instalação, comandos e validações específicos. Por exemplo:

```powershell
cd skills
```

Para restaurar os submódulos nos commits registrados pelo agregador, execute na raiz de `POCs-IA`:

```powershell
git submodule update --init --recursive
```

## Validação

Confira o estado do repositório principal e dos submódulos:

```powershell
git status
git submodule status
```
