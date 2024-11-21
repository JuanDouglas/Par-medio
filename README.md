# Projeto: Analisador de Atração com Base em Preferências

## Descrição

Este projeto tem como objetivo criar uma plataforma onde os usuários podem fornecer **informações sobre suas preferências físicas** em um parceiro, e com base nas **preferências de outros usuários**, o sistema **retorna um perfil de características físicas de um possível parceiro** que seria atraído por ele.

A ideia é que o sistema, ao analisar as **preferências** de várias pessoas, possa gerar um perfil de parceiro baseado nas características físicas que seriam atraentes para o usuário, conforme o que é atraente para outras pessoas com preferências similares.

### Objetivo Principal

O sistema permitirá que os usuários forneçam informações sobre suas preferências físicas e também sobre as preferências que têm em um parceiro. Com isso, será possível gerar um perfil de um **possível parceiro atraido**, com base nas preferências de **outros usuários** que compartilham características semelhantes.

> Além disso com os dados obtidos é possivel de forma mais precisa utilizar as médias estatisticas para retornar perfis mais qualificados a duas pessoas, e também, a analise de perfis mais e menos atraentes. 

### Ferramentas e Tecnologias

- **Back-end**: .NET Core (para processamento e API)
- **Front-end**: Angular (para interface com o usuário)
- **Banco de Dados**: SQL Server (para armazenamento dos dados)
- **Análise**: Algoritmo para calcular compatibilidade e gerar os perfis com base em dados coletados

## Funcionalidades do Sistema

- Coleta de informações pessoais e preferências do usuário (ex: idade, peso, tipo de cabelo, cor da pele, etc.)
- Análise das preferências de outros usuários e criação de um perfil de parceiro atraente para o usuário
- Geração de perfil baseado nas preferências informadas e características do próprio usuário
- Análise estatística para determinar quais características seriam atraentes para o usuário, considerando as preferências de outras pessoas
- Feedback de usuários para aprimoramento do sistema
- Funcionalidade de anonimato para garantir a privacidade das preferências

## Fases do Projeto

Este projeto será desenvolvido em várias fases, começando pela coleta de dados do usuário e análise inicial das preferências.

- **Fase 1**: Coleta de dados e preferências
- **Fase 2**: Análise dos dados e definição de perfil
- **Fase 3**: Geração do perfil atraente e ajustes com base no feedback
- **Fase 4**: Integração de uma API pública e funcionalidade de feedback de usuários

> Para obter mais detalhes das fases do projeto entre [Aqui](.\FASES.md).

### Observação

O projeto é uma **análise estatística** das preferências dos usuários, e **não garante** que os resultados representem a realidade de todos os indivíduos. A atração é uma característica subjetiva e pode variar de acordo com muitos fatores externos.
