# java-poo
Estudos e práticas , desenvolvimento real e funcional , conceitos exemplos práticos e mini projetos  que consolidam aprendizado
#  Java POO — Abordagem Técnica e Aplicada com JSF, PrimeFaces e Hibernate

###  Estudo Técnico e Prático de Programação Orientada a Objetos com Java  
 Baseado na obra “Programação Orientada a Objetos em Java: uma abordagem didática” — Prof. Dr. Manoel Campos da Silva Filho  
 Desenvolvido e documentado por **Luiz Paulo Medeiros da Cunha Júnior**

---

##  **Visão Geral**

Este repositório tem como objetivo **aprofundar o estudo técnico da Programação Orientada a Objetos (POO)** em Java, indo além da teoria para aplicar conceitos sólidos de engenharia de software em **frameworks corporativos modernos**, como:

- **JSF (Jakarta Faces)** – para desenvolvimento de interfaces web em Java.  
- **PrimeFaces** – biblioteca de componentes visuais ricos para JSF.  
- **Hibernate / JPA** – mapeamento objeto-relacional (ORM) e persistência de dados.  

A proposta é compreender a **POO como base estrutural** para o desenvolvimento de sistemas robustos, modulares e sustentáveis, evoluindo desde os **fundamentos teóricos até aplicações reais e integradas**.

---

##  **Propósito do Repositório**

> “A POO não é apenas um conjunto de conceitos — é uma forma de pensar, modelar e construir software com foco na modularidade, reutilização e abstração.”

Este repositório serve como um **guia de estudos progressivo**, unindo **código prático**, **documentação técnica** e **anotações explicativas**, para permitir uma compreensão profunda da POO e sua aplicação em ambientes empresariais com **JSF, PrimeFaces e Hibernate**.

---

##  **Fases do Estudo**

###  **Fase 1 — Fundamentos da Programação Orientada a Objetos**
Estudo conceitual e prático dos principais pilares da POO:
- Abstração  
- Encapsulamento  
- Herança  
- Polimorfismo  

 Exemplos básicos, diagramas UML, exercícios comentados e mini projetos de introdução.

---

###  **Fase 2 — POO Aplicada: Estrutura de Classes e Arquitetura**
Criação de estruturas mais robustas utilizando boas práticas:
- Classes e pacotes organizados por responsabilidade  
- Uso de interfaces e classes abstratas  
- Composição e agregação entre objetos  
- Reuso e extensibilidade de código  
- Aplicação de princípios **SOLID**  

 Nesta fase, a POO é estudada como **arquitetura de software**.

---

###  **Fase 3 — POO Integrada com JSF e PrimeFaces**
Aprofundamento técnico aplicando os conceitos em um ambiente **web corporativo**:

- Integração entre **camada de modelo (Model)** e **camada de visão (View)**  
- Criação de **Managed Beans** e **Controllers** em JSF  
- Manipulação de entidades Java via POO (getters/setters, heranças, abstrações)  
- Utilização de **PrimeFaces** para construir interfaces dinâmicas e reativas  
- Comunicação entre **frontend (JSF)** e **backend (Java)** com orientação a objetos  

 Mini projeto: *Sistema de Cadastro de Alunos e Professores com JSF + PrimeFaces*

---

###  **Fase 4 — POO e Persistência com Hibernate / JPA**
Exploração da integração entre **objetos Java e bancos de dados relacionais**:

- Mapeamento objeto-relacional (ORM)  
- Entidades e relacionamentos (`@OneToMany`, `@ManyToOne`, `@ManyToMany`)  
- Ciclo de vida de entidades  
- DAO e Repository Pattern  
- Persistência de objetos complexos com **POO + JPA**  
- Transações e gerenciamento de entidades  

 Mini projeto: *Sistema de Pedidos e Produtos com Hibernate e POO avançada.*

---

###  **Fase 5 — Arquitetura e Boas Práticas**
Aprofundamento em **Design Patterns** e padrões de arquitetura:
- **DAO, Service, Repository e MVC**  
- **Factory, Singleton, Strategy e Observer** aplicados em projetos reais  
- Modularização de código e reuso de componentes  
- Documentação JavaDoc e UML  

Objetivo: dominar o uso da POO para construção de **arquiteturas completas e escaláveis**.

---

##  **Estrutura do Repositório**

| Diretório | Conteúdo |
|:-----------|:----------|
| `/01-fundamentos` | Conceitos iniciais, sintaxe, classes e objetos |
| `/02-encapsulamento` | Controle de acesso, getters/setters e visibilidade |
| `/03-heranca-polimorfismo` | Hierarquia de classes e sobreposição de métodos |
| `/04-abstracao-interfaces` | Modelagem de classes abstratas e interfaces |
| `/05-relacionamentos` | Composição, agregação e dependências entre objetos |
| `/06-jsf-primefaces` | Integração da POO com a camada de visão (JSF + PrimeFaces) |
| `/07-hibernate-jpa` | Persistência de objetos com Hibernate e JPA |
| `/08-design-patterns` | Aplicações práticas de padrões de projeto e arquitetura |
| `/docs` | Documentação técnica, diagramas e JavaDocs |

---

##  **Conceitos Fundamentais Abordados**

| Pilar | Descrição Técnica |
|:------|:------------------|
| **Abstração** | Modelar entidades do domínio real, isolando comportamentos relevantes e omitindo detalhes internos. |
| **Encapsulamento** | Ocultar dados sensíveis e controlar o acesso a propriedades por meio de métodos públicos. |
| **Herança** | Criar hierarquias reutilizáveis de classes e compartilhar código entre superclasses e subclasses. |
| **Polimorfismo** | Permitir que métodos assumam comportamentos diferentes dependendo do contexto da instância. |

---

##  **Tecnologias e Ferramentas**

-  **Java 17+**
-  **Jakarta Faces (JSF 4.x)**
-  **PrimeFaces 13+**
-  **Hibernate / JPA**
-  **Maven** – gerenciamento de dependências
-  **Eclipse IDE / IntelliJ IDEA**
-  **MySQL / PostgreSQL** – banco de dados para persistência
-  **UML** – modelagem de classes e relacionamentos
-  **JavaDoc** – documentação técnica gerada automaticamente

---

##  **Aprendizados Esperados**

Ao final do projeto, você terá domínio técnico sobre:

- Aplicar **POO em contextos reais**, e não apenas teóricos.  
- Construir **sistemas corporativos** com **arquitetura orientada a objetos**.  
- Entender o ciclo completo: **Model → Controller → View → Persistência.**  
- Integrar **conceitos de engenharia de software** a **frameworks modernos**.  
- Produzir **código limpo, reutilizável e escalável**.  

---

##  **Filosofia de Desenvolvimento**

> "Cada classe deve representar algo significativo no domínio da aplicação."

Os códigos contidos neste repositório são fortemente **comentados e explicados**, servindo como **material de referência e estudo**.  
Cada módulo inclui exemplos práticos e mini sistemas evolutivos que demonstram a aplicação da POO no desenvolvimento **Web Full-Stack Java**.

---

##  **Próximos Passos**

- [ ] Implementar **projetos completos** integrando JSF, PrimeFaces e Hibernate  
- [ ] Aplicar **padrões de projeto** com foco em desacoplamento e extensibilidade  
- [ ] Criar **documentação UML e JavaDoc** para os módulos avançados  
- [ ] Publicar **PDF final** com resumo técnico e diagramas  

---

##  **Autor**

**Luiz Paulo Medeiros da Cunha Júnior**  
Desenvolvedor Full-Stack Java| Explorando POO de forma aplicada e arquitetural  
🔗 GitHub: [github.com/seu-usuario](https://github.com/seu-usuario)  
🔗 LinkedIn: [linkedin.com/in/seu-linkedin](https://linkedin.com/in/seu-linkedin)

---

##  **Licença**

Este projeto é de caráter **educacional e técnico**.  
Os direitos do material de referência pertencem ao **Prof. Dr. Manoel Campos da Silva Filho**.  
Códigos, exemplos e documentação adicionais foram desenvolvidos por **Luiz Paulo Medeiros da Cunha Júnior** sob licença **MIT**.

---
