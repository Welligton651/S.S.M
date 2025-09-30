# S.S.M
Sistema de solicitações de manutenção
O site que você enviou é um **Sistema de Ordem de Serviço (O.S.)** que utiliza a tecnologia *frontend* (HTML, CSS e JavaScript) com a estrutura visual moderna do **Tailwind CSS** e um design que utiliza o efeito "vidro" (*glass-effect*).

O sistema parece ser destinado ao uso interno de uma **Coordenação de Suporte e Logística - Manutenção** e é dividido em três abas principais, focadas na gestão de tarefas de manutenção:

---

## Estrutura e Funcionalidades Principais

### 1. Nova O.S. (Criação de Ordem de Serviço)
Esta seção é um formulário para registrar novas solicitações de serviço, com os seguintes campos obrigatórios:
* **Nome do Setor/Unidade**
* **Solicitante**
* **Tipo de Serviço**: Lista com opções predefinidas (ex: Manutenção Preventiva/Corretiva de Ar Condicionado, Troca de Lâmpadas, Manutenção Elétrica/Hidráulica, etc.)
* **Número SEI** (um protocolo administrativo)
* **Nível de Prioridade**: Opções de Baixa, Média, Alta e Urgente
* **Descrição do Serviço**

### 2. Lista de O.S. (Gerenciamento de Ordens)
Esta aba é projetada para exibir as Ordens de Serviço criadas dinamicamente. O código indica que cada item na lista deve conter informações detalhadas, como o número da O.S., solicitante, setor, prioridade, status, e um botão de ação (como "Ver Detalhes/Assinar").

### 3. Dashboard (Painel de Análise)
Esta seção fornece uma visão estatística e gráfica das Ordens de Serviço, incluindo:
* **Estatísticas Gerais**: Total de O.S., Quantidade de O.S. Concluídas, Em Andamento e Abertas.
* **Gráficos**: Análise das Unidades que Mais Solicitam e dos Serviços Mais Solicitados.

---

## Outras Características Técnicas

* **Design Responsivo**: O layout utiliza Tailwind CSS e foi otimizado para visualização em dispositivos móveis (*mobile optimizations*).
* **Assinatura Digital**: Inclui um modal (*modal*) de assinatura (*signature-pad*) para permitir que o solicitante ou técnico assine digitalmente a O.S. antes de imprimi-la.
* **Personalização**: Permite que o usuário defina uma imagem de fundo personalizada para o sistema.
* **Data e Hora em Tempo Real**: Exibe a data e a hora atualizadas automaticamente.
