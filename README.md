# README - Landing Page Totalmente Personalizável

Este documento descreve um sistema completo para geração de landing pages modernas desenvolvidas com React 18 e Tailwind CSS.[1]

## Visão Geral

O projeto define uma arquitetura para criação de Single Page Applications (SPA) focadas em performance, design responsivo e experiência de usuário avançada. A implementação é baseada em três pilares principais: definição de conteúdo, requisitos técnicos/UX e regras de design/arquitetura.[1]

## Estrutura do Projeto

### Parte 1: Definição de Contexto e Dados

Define a identidade do projeto através de dois tipos de configuração:[1]

- **Configuração Pessoal/Profissional (Tabela 2.1)**: Para portfólios pessoais com campos como nome, foto de perfil, currículo, experiências e galeria de trabalhos
- **Configuração de Produto/Serviço (Tabela 2.2)**: Para empresas e produtos com campos como nome do produto, logotipo, whitepaper, características e mockups

### Parte 2: Requisitos Técnicos e UX

Módulos organizados em categorias de funcionalidades opcionais:[1]

**Performance e Acessibilidade (RNF1-RNF4)**
- Lazy loading de imagens
- Intersection Observer para animações
- Conformidade A11Y (ARIA, navegação por teclado)
- Tags de SEO essenciais

**Personalização e Interação (RF1-RF6)**
- Dark/Light Mode com persistência
- Internacionalização (pt/en)
- Controle dinâmico de cores
- Command Palette (Ctrl + K)
- Menu gaveta mobile
- Bloqueio de scroll em modais

**Mídia e Animação (RF7-RF12)**
- Barra de progresso de scroll
- Efeito typing no subtítulo
- Marquee animado para skills
- Galeria modal com zoom
- Botão voltar ao topo

**Contato e Comunicação (RF13-RF16)**
- Integração com EmailJS
- Validação client-side
- Validação de formato de email
- Compartilhamento nativo

### Parte 3: Regras de Design e Arquitetura

Especificações técnicas e visuais:[1]

**Stack Técnica**
- Arquivo HTML auto-contido único
- React 18 (Hooks funcionais)
- Tailwind CSS
- Dependências via CDN
- Lucide React para ícones

**Design System**
- Tipografia: Google Fonts (Inter e Roboto Mono)
- Esquema de cores: Paleta escura (slate-900) e clara (slate-50) com cor primária dinâmica
- Microinterações com transições CSS suaves

**Estrutura de Seções**
- Header com navegação
- Hero com CTA principal
- Sobre/Visão Geral
- Skills/Características
- Experiência/Linha do Tempo
- Contato com formulário
- Footer com documentação
- Modals e overlays

## Como Utilizar

1. Preencha a seção de "Visão Geral e Conceito" com a descrição do projeto
2. Responda SIM ou NÃO para definir o tipo (pessoal ou produto/empresa)
3. Complete a tabela correspondente (2.1 ou 2.2) com todo o conteúdo
4. Selecione os módulos desejados respondendo SIM/NÃO em cada requisito (RNF1-RNF16)
5. Configure as variáveis globais (cor primária, URLs, regras de layout)
6. O sistema gerará o código HTML auto-contido com todas as funcionalidades selecionadas

## Observações Importantes

- Todos os links externos devem usar `target="_blank" rel="noopener noreferrer"`[1]
- Navegação interna utiliza smooth scroll[1]
- Se EmailJS for habilitado, é necessário configurar SERVICE_ID, TEMPLATE_ID e PUBLIC_KEY[1]
- A separação lógica do código deve seguir: Hooks (lógica), UI Components (elementos visuais), Layout Components (estrutura) e Modals (sobrecamadas)[1]

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/38332461/ae8eae20-207b-426c-8dfb-932ebd48e3ec/Prompt-Landing-Page.pdf)
