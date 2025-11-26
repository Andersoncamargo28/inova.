#  Otimização do Processo de Corte e Embalagem de Manta -  <img width="339" height="60" alt="Freudenberg_logo svg" src="https://github.com/user-attachments/assets/22bffa2d-5af9-4d11-b453-67b57f6fd125" />

Este repositório documenta as melhorias propostas e implementadas no projeto de otimização do processo de corte e embalagem de manta na Freudenberg. O objetivo é resolver desafios operacionais chave, como desperdício de material, baixa produtividade e ergonomia dos operadores, através da integração de metodologias Lean e tecnologias de automação e digitalização.



## TEAM 
<img width="1185" height="645" alt="Captura de tela 2025-11-26 092427" src="https://github.com/user-attachments/assets/0070900a-61cc-48c9-ba11-17a96b26064e" />

## LINK YOUTUB SPRINT 1
https://youtu.be/F2NRJu3voaY?feature=shared
##  LINK YOUTUB SPRINT 2
https://youtu.be/OPk1OzhFVxA
## LINK YOUTUB SPRINT 3
https://youtu.be/OPk1OzhFVxA
##  Visão Geral do Projeto

O projeto visa transformar o processo de corte e embalagem de mantas, abordando problemas crônicos identificados na operação diária. Através de um esforço colaborativo da equipe Scrum, foram desenvolvidas e propostas soluções que prometem aumentar a eficiência, reduzir custos e melhorar as condições de trabalho.

###  Problemas Atuais Abordados:

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

##  Como este Repositório Ajuda

Este repositório serve como um hub central para:
*   **Documentação**: Armazenar todos os POPs, guias de treinamento e especificações de sistema.
*   **Código-Fonte (Proposto/Hipotético)**: Contém estruturas de código para componentes digitais do projeto, como o sistema Kanban e interfaces de automação.
*   **Configurações**: Modelos de arquivos de configuração para os sistemas.
*   **Histórico**: Rastrear as evoluções e contribuições para o projeto.

## 🛠️ Instalação e Configuração (Componentes de Software)

Embora grande parte do projeto envolva mudanças físicas e de processo, este repositório contém _placeholders_ e exemplos para os componentes de software que dão suporte às melhorias.
<img width="1190" height="662" alt="Captura de tela 2025-11-26 104406" src="https://github.com/user-attachments/assets/2b3db24f-2e32-4256-bf92-bfcf3837c7a8" />


### Pré-requisitos (para os módulos de software hipotéticos):

*   **Python 3.8+**: Para o backend do Kanban e módulos Jidoka/otimização.
*   **`pip`**: Gerenciador de pacotes Python.
*   **Git**: Para clonar o repositório.
# 📦 Guia Detalhado para Gestão do "Banco de Sobras"

Este documento detalha o procedimento para organizar e gerenciar eficazmente o "Banco de Sobras" de mantas, visando a redução de desperdícios e a otimização do uso de materiais.

## 1. Introdução
A gestão eficiente das sobras de manta é crucial para a redução de custos e a sustentabilidade do processo. Este guia estabelece um método padronizado para armazenar, identificar e reutilizar as sobras.

## 2. Criação de um "Banco de Sobras" Físico Organizado

### 2.1. Definição do Espaço
*   Designar um espaço exclusivo (estante, prateleira ou caixas etiquetadas) na área de corte para o armazenamento das sobras.
*   Garantir que o espaço seja de fácil acesso e que permita a visualização rápida do material.

### 2.2. Organização por Critérios
As sobras devem ser organizadas por categorias claras para facilitar a localização e o uso.
*   **Critérios Mínimos de Organização**:
    *   **Tipo de Manta**: (Ex: Manta A, Manta B, etc.)
    *   **Espessura**: (Ex: 5mm, 10mm)
    *   **Cor**: (Ex: Preta, Branca, Azul)
    *   **Metragem**: Separar em faixas, por exemplo: "até 1m", "acima de 1m", "até 50cm".

### 2.3. Exemplo de Estrutura de Prateleiras:
![rack-gaiola-para-transporte-grande-03062025195910683f540ec3892](https://github.com/user-attachments/assets/6c194b6b-1bbf-459c-9d79-0d083c5e1355)

#  Conceito e Implementação do Sistema Jidoka no Processo de Corte

## 1. O Que é Jidoka?
Jidoka é um dos pilares do Sistema Toyota de Produção e significa "automação com toque humano". A essência do Jidoka é a capacidade de um equipamento ou processo parar automaticamente ao detectar uma anomalia (defeito, erro, condição fora do padrão), notificando o operador. Isso previne que defeitos passem para as próximas etapas e permite a correção imediata na fonte do problema.

## 2. Princípios do Jidoka
1.  **Detectar a Anormalidade**: Reconhecer que algo está errado.
2.  **Parar o Processo**: Interromper a operação imediatamente.
3.  **Corrigir a Condição Anormal**: Resolver a causa raiz do problema.
4.  **Investigar a Causa Raiz**: Analisar o porquê do problema ter ocorrido para prevenir reincidência.

## 3. Aplicação do Jidoka no Processo de Corte de Manta

### 3.1. Problemas Atuais que o Jidoka Resolverá:
*   Cortes fora de especificação que só são notados em etapas posteriores.
*   Desalinhamento do rolo de manta causando desperdício.
*   Variações de espessura ou defeitos na manta não identificados precocemente.
*   Danos à máquina de corte por operação contínua sob condição anormal.

### 3.2. Pontos de Detecção e Ações Jidoka Propostos:

| Ponto de Detecção      | Anomalia Detectada                     | Tipo de Sensor (Exemplo) | Ação Jidoka (Sistema)                      | Ação Humana (Operador)                                      |
| :--------------------- | :------------------------------------- | :----------------------- | :----------------------------------------- | :---------------------------------------------------------- |
| **Alinhamento do Rolo**| Rolo de manta desalinhado              | Sensor de proximidade/visão | Parada automática da máquina de corte   | Reajustar o rolo, verificar fixação.                        |
| **Corte Impreciso**    | Desvio das dimensões de corte          | Sensor de visão/medida   | Parada automática da máquina de corte   | Verificar lâmina, calibrar máquina, inspecionar material.   |
| **Tensão da Manta**    | Tensão inconsistente da manta          | Célula de carga          | Redução de velocidade / Parada automática | Verificar sistema de alimentação e freio do rolo.            |
| **Fim de Rolo**        | Rolo de manta atingindo o final         | Sensor de proximidade    | Aviso sonoro/visual, parada programada   | Preparar próximo rolo, agilizar troca.                      |
| **Falha na Embalagem** | Embalagem fora do padrão ou incompleta | Sensor de visão          | Alerta ao operador, possível parada      | Corrigir falha na embalagem, verificar material.            |

### 3.3. Componentes do Sistema Jidoka (Hipotético)
*   **Sensores**: Dispositivos físicos que coletam dados e detectam anomalias (vide tabela acima).
*   **Módulo de Monitoramento (`src/jidoka_monitor/`)**:
    *   `sensor_data_processor.py`: Recebe e processa os dados dos sensores em tempo real.
    *   `alerts.py`: Contém a lógica para identificar condições anormais e disparar ações (parada da máquina, alertas sonoros/visuais).
*   **Interface de Usuário (Painel de Controle)**: Exibe o status da máquina, alertas ativos e histórico de anomalias (pode ser integrado ao sistema Kanban digital ou um painel dedicado).
*   **Mecanismo de Parada**: Conexão com os controles da máquina de corte para iniciar uma parada emergencial ou controlada.

## 4. Benefícios da Implementação do Jidoka
*   **Qualidade na Fonte**: Previne que produtos defeituosos sigam para as próximas etapas, economizando tempo e material.
*   **Redução de Desperdício**: Minimiza a produção de material fora de especificação.
*   **Aumento da Eficiência**: Operadores podem se concentrar em atividades de valor agregado e na resolução de problemas, em vez de monitoramento constante.
*   **Segurança**: Paradas automáticas podem prevenir acidentes causados por falhas no processo.
*   **Aprendizado Contínuo**: A análise das causas-raiz das paradas Jidoka leva a melhorias contínuas no processo.

## 5. Processo de Implementação e Manutenção
1.  **Mapeamento de Pontos Críticos**: Identificar onde as anomalias são mais propensas a ocorrer.
2.  **Seleção e Instalação de Sensores**: Escolher os sensores adequados para cada ponto.
3.  **Desenvolvimento do Módulo de Monitoramento**: Programar a lógica de detecção e ação.
4.  **Integração com Máquinas**: Conectar o módulo de monitoramento aos controles da máquina.
5.  **Testes e Validação**: Realizar testes rigorosos para garantir a eficácia do sistema.
6.  **Treinamento de Operadores**: Capacitar os operadores para responder aos alertas Jidoka e participar da análise de causa-raiz.
7.  **Manutenção Preditiva**: Realizar manutenção regular nos sensores e no software para garantir o funcionamento contínuo.

A implementação do Jidoka é um passo fundamental para transformar o processo de corte em uma operação mais autônoma, robusta e eficiente, alinhada com os princípios da Indústria 4.0.
# ⚙️ Equipamento para Manuseio Ergonômico de Mantas

Este documento descreve o novo equipamento desenvolvido para otimizar o manuseio e corte de mantas, abordando diretamente os desafios ergonômicos identificados no processo.

## 1. SUPORTE 

**Suporte Ergonômico para Rolos de Manta com Guia de Corte Integrada**


## 2. Descrição Geral
O Suporte Ergonômico para Rolos de Manta com Guia de Corte Integrada é um sistema projetado para facilitar o carregamento, desenrolar, alinhamento e corte de rolos de manta de forma segura e eficiente. Ele minimiza a necessidade de intervenção manual pesada e promove uma postura de trabalho correta para o operador.

## 3. Características Principais

*   **Eixo Rolante Robusto**: Permite que rolos de manta de diferentes pesos e diâmetros sejam facilmente carregados e desenrolados, eliminando a necessidade de levantamento manual direto. O eixo possui rolamentos de baixa fricção.
*   **Sistema de Fixação Segura**: Garante que o rolo permaneça estável durante todo o processo de desenrolar e corte, prevenindo quedas e desalinhamentos (abordando o problema de "rolo de manta sem suporte adequado").
*   **Guia de Corte Integrada**: Uma régua fixa ou laser guia o cortador, assegurando cortes retos e precisos com mínimo esforço de medição e marcação manual. Pode ser adaptada para cortadores manuais ergonômicos ou cortadores semiautomáticos.
*   **Altura Ajustável (Opcional, mas Recomendado)**: A altura do suporte pode ser ajustada para se adequar à estatura do operador e à altura da mesa de corte, promovendo posturas neutras.
*   **Freio de Tensão Controlado**: Permite controlar a tensão da manta durante o desenrolar, evitando o afrouxamento ou tensionamento excessivo, que poderia levar a cortes imprecisos ou danos ao material.
*   **Estrutura Modular e Robusta**: Construído com materiais duráveis para suportar o uso industrial contínuo e ser facilmente integrado ao layout existente.

## 4. Benefícios Ergonômicos

*   **Redução Drástica do Esforço Físico**: Elimina o levantamento manual e o esforço de desenrolar rolos pesados.
*   **Promoção de Posturas Neutras**: Com a estabilidade e guias, o operador pode manter uma postura mais ereta e natural durante o corte e medição.
*   **Diminuição da Repetitividade**: A guia de corte e a estabilidade do rolo reduzem a necessidade de ajustes e movimentos repetitivos.
*   **Aumento da Segurança**: Previne quedas de rolos, minimiza o risco de cortes acidentais devido à instabilidade do material ou da ferramenta.
*   **Melhora na Precisão**: Reduz o erro humano, resultando em cortes mais consistentes e menos retrabalho.

## 5. Integração no Fluxo de Trabalho

O equipamento é projetado para ser o ponto de partida do processo de corte, atuando como um alimentador de material para a mesa de corte, que idealmente seria também ajustável em altura. A interação com o software Audace para otimização de corte é facilitada pela estabilidade do material fornecido pelo suporte.

## 6. Imagem do Equipamento

**<img width="1192" height="661" alt="Captura de tela 2025-11-26 104233" src="https://github.com/user-attachments/assets/55067114-69d6-418d-b947-1e83a3b0b8bc" />
**
_Nota: A imagem acima representa a ilustração conceitual ou foto do equipamento desenvolvido._

## 7. Próximos Passos
*   Validação em ambiente de produção.
*   Treinamento detalhado para os operadores sobre o uso correto e os ajustes ergonômicos.
*   Coleta de feedback dos usuários para futuras melhorias.

<img width="1189" height="662" alt="Captura de tela 2025-11-26 111859" src="https://github.com/user-attachments/assets/956ffbe9-c3a4-4739-b735-b18070ef3def" />
