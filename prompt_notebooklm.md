# Prompt para o NotebookLM - Miniguia de Estudos: Model Context Protocol (MCP)

Copie e cole o prompt abaixo no campo de chat do **NotebookLM** após fazer o upload das fontes curadas (ou inserção dos links indicados no README.md).

---

```text
Olá, NotebookLM. Com base exclusivamente nos documentos e fontes que eu carreguei sobre o Model Context Protocol (MCP), preciso que você crie um "Miniguia de Estudo" aprofundado e altamente estruturado. 

A entrega final deve conter exatamente as seguintes seções estruturadas:

1. **Resumos Estruturados do Assunto**:
   - **O que é o MCP e por que ele foi criado**: Explique o problema histórico de integrações ponto a ponto e como o MCP atua como um padrão universal (analogia com "USB-C").
   - **Arquitetura do MCP**: Detalhe os papéis do Host (ex: Claude Desktop, Cursor), do Cliente e do Servidor MCP. Explique como eles se comunicam.
   - **Recursos, Ferramentas (Tools) e Prompts**: Diferencie claramente cada uma dessas três capacidades fundamentais que um servidor MCP pode expor.
   - **Transportes de Comunicação**: Explique a diferença de uso entre `stdio` (processos locais) e `SSE` (Server-Sent Events para conexões remotas via HTTP).
   - **Depuração e Ferramentas**: Explique o que é o "MCP Inspector" e como ele é utilizado no desenvolvimento de servidores.

2. **Glossário Técnico**:
   - Liste e defina em termos claros e precisos os seguintes conceitos básicos e avançados do protocolo:
     * Model Context Protocol (MCP)
     * Host
     * Client
     * Server
     * Resource (Recurso)
     * Tool (Ferramenta)
     * Prompt
     * Transport (Transporte)
     * stdio
     * Server-Sent Events (SSE)
     * MCP Inspector
     * JSON-RPC 2.0 (usado no protocolo)

3. **Conjunto de Prompts Reutilizáveis para Revisão**:
   - Crie 3 a 5 templates de prompts estruturados que eu poderei usar no futuro para fazer revisões rápidas ou testar meu próprio conhecimento sobre MCP (ex: prompts para simulação de flashcards, prompts de cenários práticos de arquitetura para resolver problemas, etc.).

Adote um tom didático, preciso, profissional e adequado para desenvolvedores ou entusiastas de tecnologia que desejam dominar o MCP. Organize a saída usando formatação rica em Markdown (tópicos, negrito, tabelas e caixas de destaque se aplicável).
```
