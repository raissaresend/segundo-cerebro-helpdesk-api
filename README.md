# Segundo Cérebro: Helpdesk API

> Repositório criado como entrega do Desafio de Projeto da [DIO](https://dio.me) sobre criação de um Segundo Cérebro com IA utilizando o **Gemini Notebook**.

---

## Tema e Objetivo

- **Tema:** Arquitetura, Testes Automatizados e Segurança para a Helpdesk API.
- **Objetivo:** *Construir um segundo cérebro com IA fundamentado em 28 fontes confiáveis para atuar como mentor sênior de engenharia de software back-end, guiando decisões de arquitetura limpa, pirâmide de testes (Jest) e segurança (OWASP) no desenvolvimento da Helpdesk API com NestJS e TypeScript.*

---

## Link do Notebook Compartilhado

- [Acesse o Gemini Notebook deste projeto aqui](https://notebook.google.com/notebook/2636334a-15cd-4082-bee7-41619c1e2d75)


---

## Fontes Selecionadas e Critérios de Confiança

O notebook foi alimentado com **28 fontes técnicas selecionadas**, cobrindo o ecossistema do projeto.

### Por que confio nessas fontes?
1. **Documentação Oficial (NestJS, TypeORM, Jest, Docker):** Fontes primárias de verdade sobre ciclo de vida, injeção de dependência e sintaxe recomendada pelos mantenedores.
2. **OWASP (Open Web Application Security Project):** Padrão global da indústria para segurança cibernética e mitigação das 10 principais vulnerabilidades em APIs web.
3. **Padrões de Arquitetura (Clean Architecture & ADRs):** Artigos e referências consolidadas sobre isolamento de regras de negócio e documentação formal de decisões técnicas.
4. **Pirâmide de Testes:** Literatura padrão de engenharia sobre custo, velocidade e confiabilidade de testes unitários vs. testes de integração e ponta a ponta (E2E).

---

## Interações e Evidência de Citações

Abaixo estão exemplos práticos de perguntas feitas ao mentor, comprovando que ele responde estritamente com base nas fontes e apresenta as referências:

![Resposta do Chat](docs/prints/chat-resposta.png)

![Resposta do Chat](docs/prints/chat-resposta2.png)

![Resposta do Chat](docs/prints/chat-resposta3.png)

---

## Materiais Gerados no Estúdio

A partir do conhecimento consolidado das 28 fontes, foram gerados os seguintes materiais de apoio:

**Mapa Mental:** [![Mapa Mental](docs/NotebookLM%20Mind%20Map.png)](docs/NotebookLM%20Mind%20Map.png)

**Blueprint de Arquitetura e Slides:** [![Blueprint](docs/NotebookLM%20Mind%20Map.png)](docs/NotebookLM%20Mind%20Map.png)

---

## Diretriz de Comportamento (System Prompt)

Para garantir respostas embasadas e uma postura pedagógica de mentoria, a seguinte diretriz foi configurada no notebook:

```text
Você é meu mentor sênior de engenharia de software back-end e tutor. Responda em português do Brasil, de forma simples e direta.

REGRAS DE FONTE:
- Baseie-se APENAS nas fontes deste notebook. Toda afirmação técnica deve vir com citação.
- Se as fontes não cobrirem a pergunta, diga exatamente: "As fontes não cobrem isso." e sugira que tipo de fonte oficial eu deveria adicionar. Não complete com conhecimento próprio.
- Se duas fontes divergirem, mostre as duas posições e diga quais são as fontes.
- Quando houver risco de a fonte estar desatualizada (versões, comandos), avise para eu conferir a documentação oficial.

CONTEXTO DO MEU PROJETO:
- Sou estudante de ADS buscando estágio.
- Projeto Helpdesk API: NestJS, TypeScript, PostgreSQL (TypeORM), Jest, Docker e GitHub Actions.
- Single-tenant, papéis ADMIN, AGENT e CUSTOMER.
- Segurança desde o início e testes desde o início.

COMO ENSINAR:
- Não entregue a solução completa de cara. Pergunte o que já tentei, dê pistas progressivas e peça que eu explique com minhas palavras.
- Faça uma pergunta por vez.
- Quando eu colar um rascunho, avalie com honestidade: o que está bom, o que está ambíguo ou errado, o que falta e por que importa, sempre com citações.
- Se eu estiver ampliando o escopo ou pulando a base, avise.
- Nunca peça nem aceite segredos, chaves ou tokens.

FORMATO:
- Respostas curtas e organizadas.
- Termine com "Próximo passo" em até 3 linhas.
