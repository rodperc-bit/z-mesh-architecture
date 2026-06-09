Z-MESH Architecture

Z-MESH — Zero Trust Micro-MCP Ephemeral Sandbox Hub é uma proposta conceitual de arquitetura para governança segura de capacidades MCP acionadas por agentes de IA.

A proposta introduz o conceito de Micro-MCPs efêmeros executados em runtimes de sandbox isolados, com avaliação de políticas, credenciais temporárias, restrição de tráfego, auditoria contextual e destruição do runtime após a execução.

Documento Título: Z-MESH: uma proposta de arquitetura Zero Trust para Micro-MCPs efêmeros em runtimes de sandbox distribuídos Zenodo, v0.1, 2026.
DOI: 10.5281/zenodo.20600003

Autor: Rodrigo Persiani Ciscom Colaborador: Rogerio Alves de Macedo

Versão: v0.1 Tipo: Position Paper / Proposta Arquitetural Status: Versão inicial para discussão técnica, validação experimental e colaboração acadêmica Estrutura do repositório paper/ Documento principal em PDF e DOCX diagrams/ Figuras e diagramas da arquitetura hashes/ Hashes SHA-256 dos arquivos publicados lab-proposal/ Proposta futura de validação experimental Objetivo

O objetivo do Z-MESH é propor uma camada complementar de governança Zero Trust para mediar o acesso de agentes de IA a sistemas corporativos sensíveis por meio de capacidades MCP efêmeras, especializadas, autorizadas e auditáveis.

Conceitos principais Micro-MCPs efêmeros: servidores MCP mínimos, especializados e descartáveis. Runtimes de sandbox: ambientes isolados para execução controlada dos Micro-MCPs. Concentrador Z-MESH: plano de controle responsável por autenticação, autorização, seleção de capacidades, emissão de credenciais temporárias, controle de tráfego, auditoria e destruição do runtime. Governança Zero Trust: nenhuma chamada é implicitamente confiável; cada requisição deve ser avaliada por identidade, finalidade, política, escopo e risco. Licença

The position paper, diagrams and architectural documentation are licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

See LICENSE.md for details.

Any future source code or laboratory implementation may be licensed separately.

Citação

Uma versão com DOI poderá ser disponibilizada posteriormente via Zenodo após a criação da release pública v0.1.
