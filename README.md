# Rodrygo de Souza

Desenvolvedor em formação, estudante de Análise e Desenvolvimento de Sistemas na ULBRA, com foco em **desenvolvimento web**, **APIs REST**, **Angular**, **backend com .NET e Spring Boot** e **boas práticas de arquitetura de software**.

Tenho direcionado meus projetos para demonstrar organização técnica, separação de responsabilidades, documentação, testes, integração de sistemas e evolução incremental de software.

Busco oportunidade como **estagiário** ou **desenvolvedor júnior**, contribuindo em times que valorizam código limpo, aprendizado contínuo, colaboração e entrega com qualidade.

---

## Tech Stack

### Frontend

![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white)

### Backend

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=flat-square)

### Banco de Dados

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Cloud

![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

### Arquitetura

`Clean Architecture` · `Arquitetura por Features` · `DTOs` · `Services` · `Repository Pattern` · `Adapter Pattern` · `ADRs`

### Ferramentas

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=000)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)

### IA

Uso de IA como apoio à produtividade administrativa, documentação e prototipação, com separação clara entre automação administrativa e decisões de domínio sensível.

### DevOps

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Qualidade

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white)

---

## Projetos em Destaque

### 1. HealthFlow Gov

**Objetivo:** plataforma frontend Angular que simula uma solução de gestão pública de saúde, com foco em arquitetura, organização modular, integrações, rastreabilidade, riscos técnicos e IA administrativa.

**Tecnologias:** Angular, TypeScript, SCSS, Angular Router, Reactive Forms, Vitest, GitHub Actions.

**Principais conceitos utilizados:**

- Componentes standalone
- Lazy loading com `loadComponent`
- Arquitetura por features
- Services mockados como preparação para API REST
- Interfaces e models TypeScript
- Testes unitários
- Documentação técnica e ADRs
- CI com GitHub Actions
- Adapter conceitual para legado Sybase/PowerBuilder

**Diferenciais técnicos:**

- Projeto direcionado a um domínio realista da vertical saúde.
- Separação clara entre `core`, `shared`, `layout` e `features`.
- Documentação de decisões arquiteturais.
- IA apresentada como apoio administrativo, sem diagnóstico clínico.
- Pipeline de qualidade executando testes e build automaticamente.

**Repositório:** [github.com/rodrygords/healthflow-gov](https://github.com/rodrygords/healthflow-gov)

---

### 2. CRUD-ap2

**Objetivo:** aplicação Angular para gerenciamento de veículos, com CRUD completo e persistência local simulada por JSON Server.

**Tecnologias:** Angular, TypeScript, HTML, CSS, JSON Server.

**Principais conceitos utilizados:**

- Componentes Angular
- Services para manipulação de dados
- Consumo de API REST simulada
- Modelo `Veiculo`
- Configuração de ambiente frontend

**Diferenciais técnicos:**

- Demonstra prática de Angular em cenário CRUD.
- Usa JSON Server para simular backend durante o desenvolvimento.
- Mantém uma separação inicial entre modelo, componente e serviço.

**Repositório:** [github.com/rodrygords/CRUD-ap2](https://github.com/rodrygords/CRUD-ap2)

---

### 3. ApiUsers

**Objetivo:** API REST em Java/Spring Boot para cadastro e gerenciamento de usuários com persistência em MySQL.

**Tecnologias:** Java 21, Spring Boot, Spring Web, Spring Data JPA, Hibernate, MySQL, Maven, JUnit.

**Principais conceitos utilizados:**

- API REST
- Spring Boot
- Camadas de controller, service, repository e entity
- DTOs
- JPA/Hibernate
- Identificadores UUID
- Testes automatizados

**Diferenciais técnicos:**

- Projeto útil para demonstrar fundamentos backend em Java.
- Integra aplicação Spring com banco relacional.
- Documenta limitações conhecidas e melhorias futuras.

**Repositório:** [github.com/rodrygords/ApiUsers](https://github.com/rodrygords/ApiUsers)

---

### 4. API-de-usuario-as-Rodrygo

**Objetivo:** API REST em C#/.NET para gerenciamento de usuários, estruturada em camadas e com validações de negócio.

**Tecnologias:** C#, ASP.NET Core, Entity Framework Core, SQLite, FluentValidation, Swagger/OpenAPI.

**Principais conceitos utilizados:**

- Clean Architecture
- Minimal APIs
- DTOs
- Repository Pattern
- Service Pattern
- Dependency Injection
- Soft delete
- Problem Details
- Hash de senha com PBKDF2

**Diferenciais técnicos:**

- Melhor projeto backend do perfil em termos de organização.
- Possui validações, tratamento de erros e cuidado com dados sensíveis.
- Inclui testes e collection Postman para validação da API.

**Repositório:** [github.com/rodrygords/API-de-usuario-as-Rodrygo](https://github.com/rodrygords/API-de-usuario-as-Rodrygo)

---

### 5. Sistema de Orçamentos de Telhados

**Objetivo:** API REST para cadastro de clientes e gerenciamento de orçamentos de serviços de telhado, conectando experiência de negócio com desenvolvimento backend.

**Tecnologias:** C#, ASP.NET Core Web API, Entity Framework Core, SQLite, Swagger/OpenAPI.

**Principais conceitos utilizados:**

- CRUD de clientes e orçamentos
- DTOs
- Validações com Data Annotations
- Services com regras de negócio
- Cálculo automático de valor total
- Filtro por status
- Proteção contra exclusão indevida

**Diferenciais técnicos:**

- Projeto pequeno, objetivo e fácil de explicar em entrevista.
- Mostra capacidade de transformar regra de negócio real em API.
- Boa documentação de endpoints, execução e próximos passos.

**Repositório:** [github.com/rodrygords/sistema-orcamentos-telhados](https://github.com/rodrygords/sistema-orcamentos-telhados)

---

### 6. AP1 Aplicações Front-End

**Objetivo:** aplicação web para lista de estudos com cadastro manual, validação e busca de sugestões em API externa.

**Tecnologias:** HTML5, CSS3, JavaScript, Fetch API, GitHub Pages.

**Principais conceitos utilizados:**

- Manipulação do DOM
- Eventos
- Validação de formulário
- Estado local com array
- `fetch` e `async/await`
- Consumo de API REST externa
- Deploy estático no GitHub Pages

**Diferenciais técnicos:**

- Demonstra fundamentos sólidos de JavaScript sem framework.
- Usa API externa para tornar a interface dinâmica.
- Mostra evolução entre JavaScript puro e Angular nos projetos posteriores.

**Repositório:** [github.com/rodrygords/AP1-aplicacoes-front-end](https://github.com/rodrygords/AP1-aplicacoes-front-end)

---

## O que gosto de construir

- Aplicações web com Angular e TypeScript
- APIs REST em .NET e Spring Boot
- Sistemas organizados por camadas e responsabilidades
- Interfaces conectadas a services e contratos claros
- Integrações entre frontend, backend e banco de dados
- Documentação técnica objetiva
- Testes unitários e validações automatizadas
- Pipelines simples com GitHub Actions
- Projetos que simulam problemas reais de negócio

---

## Atualmente estudando

- Angular moderno: standalone components, lazy loading, forms e arquitetura por features
- Spring Boot com JPA/Hibernate e MySQL
- ASP.NET Core, Minimal APIs, Entity Framework Core e validações
- Testes unitários em frontend e backend
- CI/CD com GitHub Actions
- Documentação arquitetural com ADRs
- Boas práticas para APIs REST, DTOs, validação e tratamento de erros

---

## Boas práticas que procuro aplicar

✔ Clean Code  
✔ Separação de responsabilidades  
✔ APIs REST  
✔ DTOs  
✔ Services  
✔ Repository Pattern quando agrega valor  
✔ Validação de entrada  
✔ Tratamento padronizado de erros  
✔ Testes unitários  
✔ CI com GitHub Actions  
✔ Arquitetura por features  
✔ Componentes reutilizáveis  
✔ TypeScript e contratos explícitos  
✔ Documentação técnica  
✔ Commits e repositórios organizados  

---

## Objetivo Profissional

Busco uma oportunidade como **estagiário** ou **desenvolvedor júnior** em um time de tecnologia onde eu possa atuar em desenvolvimento web, backend, APIs REST, testes e manutenção evolutiva de sistemas.

Meu foco é crescer tecnicamente em ambientes com revisão de código, boas práticas de engenharia, colaboração com pessoas mais experientes e contato com problemas reais de produto e negócio.

Tenho interesse especial em empresas que trabalham com plataformas digitais, sistemas distribuídos, modernização de aplicações, integrações, dados e arquitetura de software.

---

## Contato

- LinkedIn: [linkedin.com/in/rodrygo-de-souza](https://www.linkedin.com/in/rodrygo-de-souza/)
- GitHub: [github.com/rodrygords](https://github.com/rodrygords)
- E-mail: [rodrygoulbra@gmail.com](mailto:rodrygoulbra@gmail.com)
- Localização: Arroio do Sal, RS
