# Atividade de Fixação - .NET CLI e Estrutura de Projetos

Esta atividade tem como objetivo praticar o uso da CLI do .NET, explorando templates de projetos, criação de aplicações e análise da estrutura interna de um projeto.

## Objetivo

Desenvolver familiaridade com comandos da CLI do .NET:

- Listagem de templates  
- Criação de projetos com versão específica  
- Análise de arquivos do projeto  

## Exercícios

### 1. Explorando Templates

Comando utilizado:

`dotnet new list`

Objetivo:
- Identificar templates disponíveis  
- Encontrar o Short Name para Web API e xUnit  

---

### 2. Criando Projeto com Versão Específica

Comando utilizado:

`dotnet new console -n Calculadora -f net8.0`

Objetivo:
- Criar projeto com versão definida  
- Entender o uso do parâmetro `-f`  

---

### 3. Análise do Arquivo `.csproj`

Comando utilizado:

`notepad Calculadora.csproj`

Objetivo:
- Verificar a configuração do projeto  
- Identificar:

`<TargetFramework>net8.0</TargetFramework>`

---

## Estrutura do Projeto

- `Calculadora.csproj` → Configuração do projeto  
- `Program.cs` → Código principal  

## Aprendizados

- Uso da CLI do .NET (`dotnet`)  
- Templates de projeto  
- Target Framework  
- Estrutura interna de projetos  
