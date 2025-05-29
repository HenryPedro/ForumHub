# Forum Hub: Construindo um Ecossistema de Conhecimento em TI 💡
**Versão Base: v0.1.0**
---

## 📝 Descrição do Projeto

**Forum Hub** é um projeto ambicioso de uma API de fórum, idealizada para ser um espaço de troca de **dicas e conhecimentos sobre TI e Desenvolvimento em geral**. Embora ainda em fase de desenvolvimento e com funcionalidades a serem implementadas e aprimoradas, a estrutura fundamental do sistema está montada, servindo como uma base robusta para futuras expansões.

Este projeto representa um marco significativo na minha jornada de aprendizado em desenvolvimento Back-end, sendo o culminar de meses de estudo no programa Oracle Next Education (ONE) em parceria com a Alura.

---

## ✨ Funcionalidades Atuais e em Desenvolvimento

O esqueleto do **Forum Hub** já conta com pilares essenciais para uma aplicação web moderna:

* **Autenticação de Usuário:** Estrutura para gerenciamento de usuários, incluindo criação de contas.
* **Segurança com JWT:** Implementação de JSON Web Tokens (JWT) para autenticação segura, complementada por um `TokenService` robusto, garantindo a proteção das rotas da API.
* **Banco de Dados Funcional:** Configuração e operações básicas com MySQL e entidades de dados prontas para uso.
* **Tratamento de Erros:** Mecanismos de `ErrorHandler` e tratamento de exceções comuns (como 404 Not Found) para uma experiência de usuário mais robusta.

**Ainda em fase de implementação e planejamento:**

* Configuração completa das rotas da API e integração do `TokenService` do JWT.
* Desenvolvimento do `Authentication Controller` e lógica de autorização.
* Criação da interface web (visual) do fórum.
* Refinamento e correção de pequenos bugs.

---

## 🛠️ Tecnologias Utilizadas

O **Forum Hub** é construído sobre uma pilha tecnológica moderna e amplamente utilizada no mercado:

* `Java 17`
* `Spring Boot`
* `MySQL`
* `JWT` (JSON Web Tokens)
* `Maven` (Gerenciamento de Dependências)
* `IntelliJ IDEA` (IDE de Desenvolvimento)

---

## 🏗️ Estrutura e Organização do Código

O projeto segue uma **estrutura modular e organizada por camadas**, buscando a clareza e a manutenibilidade do código. As pastas estão bem identadas, refletindo uma separação lógica das responsabilidades, como:

* `config`: Contém configurações globais, incluindo `exception` (para tratamento de erros) e `security` (para configurações de segurança).
* `controller`: Responsável pelos endpoints da API, com módulos dedicados à `Autenticação` e ao `Hub` principal do fórum.
* Outras camadas como `model` (entidades de banco de dados) e `repository` (acesso a dados) também estão presentes, seguindo as boas práticas do Spring.

---

## 🚀 Status e Futuras Implementações

Este projeto é um **legado em construção**. Devido a prazos e à sua alta complexidade, ele não foi entregue 100% funcional em sua primeira iteração. No entanto, é um projeto que será **continuamente aprimorado conforme a progressão do aprendizado** e mantido como uma base para evolução.

**Importante:** Algumas partes do código foram adaptadas de exemplos e contribuições de outros colegas do curso para acelerar o processo de desenvolvimento e atender aos prazos, o que permitiu o avanço para a implementação de novas funcionalidades. Algumas **configurações iniciais podem requerer manutenção** e ajustes para um funcionamento ideal.

**Planos para o futuro:**

* Concluir a implementação das rotas da API e a integração total do JWT.
* Desenvolver o frontend da aplicação para oferecer uma interface de usuário completa.
* Implementar funcionalidades avançadas de fórum (criação de tópicos, respostas, moderação, etc.).
* Realizar refatorações e otimizações de código para alinhar com padrões de clean code e escalabilidade.
* Corrigir bugs identificados e aprimorar a experiência geral do usuário.

---

## 🎓 Desafios, Aprendizados e Propósito

O **Forum Hub** foi, sem dúvida, o **maior desafio** enfrentado durante o curso Oracle Next Education e Alura. Sua natureza complexa e escalonável me colocou em diversas situações onde a solução não era imediatamente óbvia. A pressão para entregar o projeto foi imensa, mas serviu como um catalisador para buscar o conhecimento necessário e aprender a transformar a lógica em código funcional.

Este projeto me ensinou a importância de:

* **Persistência:** Mesmo sem saber "como" implementar tudo, o desejo de resolver o problema me impulsionou a buscar ajuda e aprender.
* **Adaptação:** Lidar com prazos apertados e a necessidade de entregar um produto viável, mesmo que não 100% completo.
* **Aprendizado Contínuo:** A percepção clara de que a primeira versão nunca é perfeita e que a melhoria contínua faz parte do desenvolvimento.
* **Colaboração:** A importância de aprender com outros e buscar inspiração em códigos bem estruturados.

Este projeto não possui uma licença específica, sendo destinado a **fins de estudo e evolução pessoal**. Ele representa um ponto de partida para aprofundar meus conhecimentos em desenvolvimento Back-end com Java e Spring Boot, com o objetivo de futuramente reconstruí-lo, melhorá-lo e torná-lo um projeto de destaque em meu portfólio.

---
