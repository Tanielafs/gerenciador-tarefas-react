Gerenciador de Tarefas - React
Sistema de gerenciamento de tarefas desenvolvido em React.js.

Sobre o Projeto
Aplicação web para gerenciar tarefas do dia a dia, permitindo adicionar, marcar como concluída e filtrar tarefas por status.
Desenvolvido por: Taniela
Tecnologia: React.js
Ano: 2025

Funcionalidades
Adicionar novas tarefas
Marcar tarefas como concluídas
Filtrar tarefas por status (Todas, Pendentes, Concluídas)
Visualizar progresso em tempo real
Design responsivo


Tecnologias Utilizadas
React.js - Biblioteca JavaScript
JavaScript (ES6+) - Linguagem de programação
CSS3 - Estilização

Hooks do React Utilizados

useState - Gerenciamento de estado local
useContext - Acesso ao contexto global
useReducer - Gerenciamento de estado complexo
createContext - Criação do contexto


Estrutura de Arquivos
src/
├── components/
│   ├── Tarefa.js              # Componente individual de tarefa
│   └── ListaDeTarefas.js      # Lista de tarefas com filtros
├── context/
│   └── TarefasContext.js      # Estado global da aplicação
├── App.js                      # Componente principal
├── App.css                     # Estilos e animações
└── index.js                    # Entrada da aplicação

Como Executar
Pré-requisitos

Node.js instalado
npm ou yarn

Instalação
bash# Instalar dependências
npm install

# ou
yarn
Executar o projeto
bash# Iniciar servidor de desenvolvimento
npm start

# ou
yarn start
O projeto abrirá automaticamente em http://localhost:3000

Como Usar
Adicionar Tarefa: Digite no campo de texto e clique em "Adicionar"
Marcar como Concluída: Clique no checkbox ao lado da tarefa
Filtrar: Use os botões "Todas", "Pendentes" ou "Concluídas"


Conceitos Aplicados
Gerencia as ações de adicionar tarefa, alternar status e definir filtro.
Componentização
Divisão da aplicação em 3 componentes principais:

App - Componente principal
ListaDeTarefas - Gerencia a lista e filtros
Tarefa - Representa cada tarefa individual

  Requisitos Atendidos
 Campo de entrada para adicionar tarefas
 Botão para adicionar tarefas
 Lista de tarefas na tela
 Checkbox para marcar como concluída
 Filtros por status (Todas, Concluídas, Pendentes)
 Estado global com useContext e useReducer
 Mínimo de 3 componentes
 Atualização imutável do estado
 Event listeners (onClick, onChange, onSubmit)


  Design
Paleta de cores: Tons laranjas pastéis (#FB923C, #FDBA74, #FFEDD5)
Gradientes CSS
Animações suaves
Layout responsivo
Efeitos hover


  Licença
Projeto desenvolvido para fins acadêmicos.

👨‍💻 Autor
Taniela
Projeto de React.js - 2025
