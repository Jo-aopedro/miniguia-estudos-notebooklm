# Miniguia de Estudos: Model Context Protocol (MCP)

Este repositório serve como um **Caderno Temático de Estudos** dedicado ao aprendizado profundo do **Model Context Protocol (MCP)**, combinando curadoria de fontes de alta qualidade, engenharia de prompts e a síntese de conhecimento realizada através da ferramenta **NotebookLM**.

---

## 1. Contexto e Objetivos

### Contexto
A inteligência artificial generativa avançou de forma exponencial nos últimos anos. No entanto, os grandes modelos de linguagem (LLMs) frequentemente operavam de forma isolada, sem acesso nativo e seguro aos nossos dados locais, arquivos de projetos ou ferramentas específicas. Tradicionalmente, conectar um LLM a fontes de dados (como bancos de dados locais, APIs internas ou ferramentas de terceiros) exigia a construção de integrações customizadas, complexas e fragmentadas para cada cliente e para cada fonte de dados.

Para resolver este problema crônico de fragmentação, a Anthropic introduziu o **Model Context Protocol (MCP)** em novembro de 2024. O MCP é um padrão aberto que atua como uma porta "USB-C" para a inteligência artificial. Ele estabelece um protocolo de comunicação unificado baseado em JSON-RPC 2.0 que permite a aplicativos de IA (como Claude Desktop, Cursor e outros clientes) conectar-se a servidores de dados padronizados de forma segura, escalável e bidirecional.

### Objetivos do Estudo
O principal objetivo deste caderno temático é consolidar um conhecimento aprofundado sobre o MCP, cobrindo os seguintes aspectos:
1. **Compreender a Arquitetura do Protocolo**: Entender a separação de responsabilidades e a dinâmica de comunicação entre o Host (aplicação de IA), o Cliente MCP e o Servidor MCP.
2. **Dominar as Três Capacidades Principais**: Estudar o funcionamento detalhado de **Recursos** (dados estáticos), **Ferramentas** (ações executáveis) e **Prompts** (fluxos de trabalho).
3. **Explorar os Mecanismos de Transporte**: Compreender a diferença e aplicabilidade prática dos transportes locais via entrada/saída padrão (`stdio`) e conexões remotas via HTTP/Server-Sent Events (`SSE`).
4. **Capacitar no Desenvolvimento e Depuração**: Aprender a estruturar e testar servidores customizados utilizando ferramentas essenciais como o **MCP Inspector**.

---

## 2. Curadoria de Fontes

Abaixo estão selecionadas 5 fontes abertas oficiais e de referência para fundamentar o aprendizado do MCP. Estes links e seus conteúdos foram adicionados ao NotebookLM para alimentar o modelo de contexto:

1. **[Site Oficial do Model Context Protocol](https://modelcontextprotocol.io)**
   * **Descrição:** A página oficial e centralizadora do protocolo. Contém guias de início rápido, conceitos fundamentais da especificação, guias práticos e a referência geral do ecossistema.
2. **[Guia Quickstart Oficial (Criando um Servidor)](https://modelcontextprotocol.io/quickstart)**
   * **Descrição:** O tutorial prático oficial passo a passo que ensina como construir um servidor MCP do zero (Weather Server em Python ou TypeScript), conectá-lo a um cliente (Claude Desktop) e depurar sua execução.
3. **[Anúncio Oficial de Lançamento da Anthropic](https://www.anthropic.com/news/model-context-protocol)**
   * **Descrição:** O post de blog original que introduz a visão conceitual do MCP, explicando a motivação da sua criação e o problema de conexões ponto a ponto que o protocolo visa sanar.
4. **[Repositório de Servidores Oficiais no GitHub](https://github.com/modelcontextprotocol/servers)**
   * **Descrição:** Catálogo oficial com implementações open-source de servidores MCP para ferramentas populares (GitHub, Postgres, Slack, Google Drive, Brave Search). Ideal para estudar padrões de design de código.
5. **[Especificação Formal do Protocolo (Docs)](https://modelcontextprotocol.io/docs/concepts/specification)**
   * **Descrição:** Documentação técnica rigorosa que descreve o esquema de mensagens JSON-RPC 2.0, o ciclo de vida de conexões do protocolo, segurança, negociação de recursos e limites de transporte.

---

## 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

*Esta seção serve para documentar os experimentos de prompt que você utilizou no NotebookLM, as respostas e eventuais "cicatrizes" (dificuldades e ajustes necessários para obter a resposta ideal).*

### O Prompt de Entrada (NotebookLM)
O prompt detalhado criado para orquestrar a geração do caderno temático final no NotebookLM foi salvo no arquivo:
* [prompt_notebooklm.md](file:///prompt_notebooklm.md)

### Diário de Ajustes e Resoluções (Cicatrizes)
*Preencha esta área à medida que interagir com o NotebookLM. Use a estrutura abaixo para documentar seu aprendizado na formulação de perguntas:*

* **Tentativa 1**:
  * **Prompt Utilizado:** *[Descreva o primeiro prompt que você testou]*
  * **Resultado Obtido:** *[O que o NotebookLM respondeu de forma satisfatória e o que faltou]*
  * **Problema/Dificuldade:** *[Ex: O modelo confundiu stdio com SSE ou não deu detalhes sobre o MCP Inspector]*
  * **Correção/Ajuste:** *[Como você reescreveu o prompt ou qual pergunta de acompanhamento fez para corrigir a resposta]*

* **Dica de Ouro:** *[Insira aqui dicas práticas que você descobriu ao ler a documentação ou ao interagir com o modelo]*

---

## 4. Miniguia de Estudo (Entrega Final)

*Esta é a entrega final consolidada que deve ser preenchida com a saída estruturada gerada pelo NotebookLM com base no prompt fornecido.*

### Resumos Estruturados do Assunto
*(Cole aqui a seção de Resumos Estruturados gerada pelo NotebookLM)*
- **O que é o MCP e por que ele foi criado**: [Placeholder]
- **Arquitetura (Host, Client, Server)**: [Placeholder]
- **Recursos vs Ferramentas vs Prompts**: [Placeholder]
- **Transportes (stdio vs SSE)**: [Placeholder]
- **Depuração (MCP Inspector)**: [Placeholder]

### Glossário Técnico
*(Cole aqui o glossário com os principais conceitos aprendidos)*
* **Model Context Protocol (MCP)**: [Placeholder]
* **Host**: [Placeholder]
* **Client**: [Placeholder]
* **Server**: [Placeholder]
* **Resource (Recurso)**: [Placeholder]
* **Tool (Ferramenta)**: [Placeholder]
* **Prompt**: [Placeholder]
* **Transport (Transporte)**: [Placeholder]
* **stdio**: [Placeholder]
* **Server-Sent Events (SSE)**: [Placeholder]
* **MCP Inspector**: [Placeholder]

### Prompts Reutilizáveis para Revisão
*(Cole aqui o conjunto de prompts de revisão sugerido pela IA)*
1. *[Prompt de Revisão 1]*
2. *[Prompt de Revisão 2]*
3. *[Prompt de Revisão 3]*
