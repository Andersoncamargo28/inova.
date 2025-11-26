#  Otimização do Processo de Corte e Embalagem de Manta -  <img width="339" height="60" alt="Freudenberg_logo svg" src="https://github.com/user-attachments/assets/22bffa2d-5af9-4d11-b453-67b57f6fd125" />


Este repositório documenta as melhorias propostas e implementadas no projeto de otimização do processo de corte e embalagem de manta na Freudenberg. O objetivo é resolver desafios operacionais chave, como desperdício de material, baixa produtividade e ergonomia dos operadores, através da integração de metodologias Lean e tecnologias de automação e digitalização.

## 🌟 Visão Geral do Projeto

O projeto visa transformar o processo de corte e embalagem de mantas, abordando problemas crônicos identificados na operação diária. Através de um esforço colaborativo da equipe Scrum, foram desenvolvidas e propostas soluções que prometem aumentar a eficiência, reduzir custos e melhorar as condições de trabalho.

### ❓ Problemas Atuais Abordados:

*   **Rolo de Manta Instável**: Quedas frequentes devido à falta de suporte adequado, gerando riscos e paradas.
*   **Esforço Físico Excessivo**: Operadores submetidos a cargas de trabalho que demandam grande esforço físico.
*   **Controle de Estoque Ineficiente**: Falta de um sistema Kanban, resultando em pedidos de material apenas quando este acaba, gerando interrupções.
*   **Desperdício de Material**: Corte manual sem otimização, levando a um alto desperdício de manta.
*   **Variações de Tempo de Corte**: Tempos de corte muito inconsistentes (de 25 a 600 segundos), impactando a previsibilidade da produção.

### ✨ Melhorias Propostas (Sprint 3):

1.  **Suporte para Rolo com Eixo Rolante**: Desenvolvimento de um suporte ergonômico e seguro para a fixação dos rolos de manta.
2.  **Kanban Físico/Visual e Digital**: Implementação de um sistema Kanban para controle de estoque de forma mais eficiente e visível, com suporte a uma versão digital para maior rastreabilidade.
3.  **Sistema Jidoka**: Introdução do conceito Jidoka para autodetecção de anomalias no processo, com paradas automáticas para correção imediata.
4.  **Software de Plano de Corte (Audace)**: Integração e utilização de software especializado (Audace) para otimizar os planos de corte e minimizar desperdícios.
5.  **Padronização do Processo (POP e Treinamento)**: Criação de Procedimentos Operacionais Padrão (POP) e programas de treinamento para garantir consistência e qualidade.
6.  **Reorganização do Layout**: Otimização do layout físico da área de corte e embalagem para melhorar o fluxo de trabalho e a ergonomia.
7.  **Estoque de Segurança**: Implementação de um estoque de segurança estratégico para evitar paradas por falta de material.
8.  **Gestão de Sobras**: Criação de um "Banco de Sobras" organizado e rotinas para consulta obrigatória e padronização de etiquetas, com controle inicial manual e potencial digitalização futura.

## 🚀 Como este Repositório Ajuda

Este repositório serve como um hub central para:
*   **Documentação**: Armazenar todos os POPs, guias de treinamento e especificações de sistema.
*   **Código-Fonte (Proposto/Hipotético)**: Contém estruturas de código para componentes digitais do projeto, como o sistema Kanban e interfaces de automação.
*   **Configurações**: Modelos de arquivos de configuração para os sistemas.
*   **Histórico**: Rastrear as evoluções e contribuições para o projeto.

## 🛠️ Instalação e Configuração (Componentes de Software)

Embora grande parte do projeto envolva mudanças físicas e de processo, este repositório contém _placeholders_ e exemplos para os componentes de software que dão suporte às melhorias.

### Pré-requisitos (para os módulos de software hipotéticos):

*   **Python 3.8+**: Para o backend do Kanban e módulos Jidoka/otimização.
*   **`pip`**: Gerenciador de pacotes Python.
*   **Git**: Para clonar o repositório.

### 1. Clonar o Repositório:

```bash
git clone https://github.com/seu-usuario/freudenberg-manta-process-sprint3.git
cd freudenberg-manta-process-sprint3
