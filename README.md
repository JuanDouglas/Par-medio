# Compatibility Analysis System

## **Descrição do Projeto**
O **Compatibility Analysis System** é um conceito de aplicação que visa mapear características pessoais de usuários e determinar padrões de atração com base em informações coletadas. A ideia do projeto é permitir que os usuários preencham formulários detalhados com suas características físicas, comportamentais e preferências, e, a partir desses dados, o sistema gerará uma análise estatística sobre o tipo de pessoa que seria atraída pelo perfil do usuário.

**Nota**: Este projeto ainda não foi construído. A implementação será feita utilizando as tecnologias listadas abaixo. O projeto fornecerá **análises estatísticas** sobre padrões de atração e não representará necessariamente a realidade. O objetivo é fornecer insights gerais sobre padrões de atração, e não uma previsão exata de comportamento humano.

### **Funcionalidades Planejadas**
#### **Cadastro e Perfil de Usuário**
- Criação de perfil pessoal através de formulários que capturam características físicas e comportamentais.
- Armazenamento seguro dos dados dos usuários no banco de dados.

#### **Definição do Par Ideal**
- Configuração de características pessoais para formar um perfil único de usuário.

#### **Análise Estatística com Relevância de Características**
- Análise baseada em **pesos atribuídos** a características físicas e comportamentais.
- O sistema irá considerar a relevância de cada característica no processo de análise de atração. Características mais importantes para o usuário terão maior impacto na recomendação do par ideal.
  - Exemplo: Se a altura é considerada uma característica mais importante, ela terá um peso maior na análise.
  
#### **Dashboard de Resultados**
- Interface intuitiva para visualização dos resultados da análise de compatibilidade.
- Relatórios e gráficos para representar os padrões observados nos dados, considerando as características com maior peso.

#### **Anonimato de Preferências**
- Garantia de privacidade ao permitir que os usuários ocultem suas preferências pessoais e características, caso desejem participar das análises de forma anônima.

#### **API Pública para Integração**
- Uma API pública permitirá que outras aplicações acessem os dados coletados (respeitando a privacidade dos usuários) para criar novas funcionalidades ou estender as existentes.
- A API exporá endpoints RESTful usando **ASP.NET Core**, com autenticação e autorização para proteger o acesso aos dados.

#### **Feature de Feedback de Compatibilidade**
- Sistema onde o usuário pode visualizar perfis sugeridos com base nos dados inseridos e avaliar se esses perfis atendem às suas expectativas.
- O feedback será utilizado para ajustar a relevância e o impacto das características no futuro.

### **Tecnologias Planejadas**
#### **Frontend**
- **Angular**: Framework JavaScript para criação da interface do usuário.
  - **Angular Material**: Para componentes de interface visual.
  - **RxJS**: Para manipulação de eventos e estados assíncronos.

#### **Backend**
- **.NET Core (ASP.NET Core)**: Framework robusto para construção do backend, APIs RESTful e lógica de negócios.
  - **Entity Framework Core**: ORM para interagir com o banco de dados SQL Server.
  - **ASP.NET Identity**: Para autenticação e gerenciamento de usuários.
  - **SignalR**: Para notificações em tempo real quando perfis compatíveis são encontrados.

#### **Banco de Dados**
- **SQL Server**: Banco de dados relacional para armazenamento seguro e eficiente dos dados dos usuários, características e preferências.
  - **Procedures e Triggers**: Para operações complexas e automações no banco de dados.

### **Instalação e Configuração Planejadas**
1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/username/compatibility-analysis-system.git
