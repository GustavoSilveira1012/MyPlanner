# 🗓️ MyPlanner

O **MyPlanner** é uma aplicação desenvolvida para ajudar profissionais a **organizar o dia a dia pessoal e profissional**, centralizando eventos, tarefas e lembretes em um único lugar.  
A proposta é oferecer **mais produtividade, controle e praticidade**, permitindo que o usuário visualize compromissos, gerencie checklists e receba notificações sobre eventos importantes.

---

## 🌟 Visão Geral

Com o MyPlanner, o usuário pode:
- Criar, editar e excluir **eventos** da agenda.
- Receber **alertas automáticos** de compromissos próximos.
- Associar **pessoas e locais** a cada evento.
- Gerenciar **checklists** de documentos ou itens necessários.
- Organizar o cotidiano pessoal e profissional de forma visual e prática.

---

## 🎯 Objetivo do Projeto

Facilitar a **gestão de tempo e compromissos** de profissionais que lidam com múltiplas tarefas diárias, tornando o acompanhamento de atividades mais intuitivo, eficiente e confiável.

---

## 🧩 Funcionalidades Principais

| Categoria | Funcionalidade |
|------------|----------------|
| **Eventos** | Criar, editar, excluir e listar eventos na agenda |
| **Notificações** | Alertas automáticos para eventos próximos |
| **Participantes** | Adicionar e visualizar pessoas envolvidas em cada evento |
| **Localização** | Registrar o local do evento |
| **Checklist** | Criar listas de itens/documentos necessários para cada evento |
| **Interface amigável** | Layout moderno e intuitivo, com foco em usabilidade |

---

## 📋 Requisitos Levantados

### 🧠 Requisitos Funcionais

1. O sistema deve permitir o **cadastro de eventos** com data, hora, local e descrição.  
2. O sistema deve enviar **notificações de alerta** sobre eventos próximos.  
3. O sistema deve permitir **associar participantes** a cada evento.  
4. O sistema deve possibilitar a **inclusão de um checklist** vinculado ao evento.  
5. O usuário deve poder **editar e excluir** eventos cadastrados.  
6. O sistema deve permitir **visualizar a agenda completa** com todos os compromissos.

### ⚙️ Requisitos Não Funcionais

1. A aplicação deve possuir **interface responsiva** e de fácil navegação.  
2. O sistema deve garantir **armazenamento persistente** dos dados (local ou em nuvem).  
3. O carregamento das telas deve ser **rápido e otimizado**.  
4. O design deve seguir um estilo **moderno e limpo**, priorizando a clareza visual.  
5. O sistema deve emitir notificações de forma **eficiente e não intrusiva**.

---

## 🧱 Tecnologias Utilizadas

- **Frontend:** React.js (com TailwindCSS para estilização)
- **Gerenciamento de Estado:** Context API / Hooks
- **Notificações:** API de notificações do navegador (ou biblioteca compatível)
- **Armazenamento:** Local Storage / Firebase / API REST (dependendo da implementação)
- **Design:** Figma (protótipos e layout de telas)

---

## 🚀 Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/seuusuario/myplanner.git

# Acesse o diretório do projeto
cd myplanner

# Instale as dependências
npm install

# Execute o servidor de desenvolvimento
npm run dev
