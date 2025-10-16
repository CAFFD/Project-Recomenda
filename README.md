# 🗺️ App Recomenda
Um aplicativo móvel colaborativo que conecta cidadãos à gestão pública, permitindo o reporte e acompanhamento de problemas urbanos de forma simples, transparente e interativa.

---

## 🎯 Sobre o Projeto
O **App Recomenda** nasceu da necessidade de criar um canal digital eficiente entre a população e o poder público.  
A proposta é empoderar o cidadão para reportar problemas urbanos — como buracos, iluminação precária ou lixo acumulado — e acompanhar o andamento das soluções pela prefeitura.

Além disso, o app busca promover o **engajamento comunitário**, permitindo que usuários apoiem e comentem em ocorrências, tornando a cidade um ambiente mais participativo e transparente.

---

## ✨ Funcionalidades Planejadas

### 🧱 Gestão de Ocorrências
- **Criação de Reportes:** Envie ocorrências com título, descrição, foto e localização no mapa.  
- **Visualização em Lista:** Acompanhe todos os reportes feitos pela comunidade.  
- **Detalhes da Ocorrência:** Veja todas as informações de um reporte específico.  
- **Status de Atendimento:** Monitore o progresso de cada ocorrência (Recebido, Em Análise, Concluído).

### 👤 Usuários e Autenticação
- **Cadastro e Login:** Crie sua conta e mantenha um histórico dos reportes enviados.  
- **Perfil do Usuário:** Consulte todas as suas contribuições em um só lugar.  

### 💬 Engajamento e Notificações
- **Apoiar Reportes:** Aumente a relevância de ocorrências já criadas.  
- **Comentários:** Interaja e discuta soluções diretamente nos reportes.  
- **Notificações Push:** Seja avisado quando o status de suas ocorrências mudar.

---

## 🛠️ Stack de Tecnologias
Este projeto está sendo desenvolvido com tecnologias modernas, priorizando **performance**, **escalabilidade** e **boa experiência do desenvolvedor**.

| Camada                | Tecnologia Principal             |
|------------------------|---------------------------------|
| **Frontend (Mobile)** | React Native + Expo              |
| **Backend (API)**      | Node.js + Express               |
| **Banco de Dados**     | PostgreSQL                      |
| **ORM & Validação**    | Prisma + Zod                    |
| **Ambiente de Dev**    | GitHub Codespaces / Docker      |

---

## 🚀 Como Executar o Projeto
O projeto está preparado para rodar facilmente via **GitHub Codespaces**, garantindo um ambiente padronizado de desenvolvimento.

### Iniciar Codespace
1. Clique no botão verde **< > Code** no topo deste repositório.  
2. Vá até a aba **Codespaces**.  
3. Clique em **Create codespace on main**.  
4. Aguarde o ambiente ser configurado automaticamente.  

> Ao finalizar, uma instância do VS Code abrirá no navegador, com o backend e banco de dados prontos para uso.

---

## 🧩 Estrutura de Pastas (Planejada)
app-recomenda/ <br>
│ <br>
├── mobile/ # Aplicativo em React Native <br>
│ ├── src/screens/ # Telas principais <br>
│ ├── src/components/ <br>
│ └── src/services/ <br>
│ <br>
├── server/ # API em Node.js (Express) <br>
│ ├── src/routes/ <br>
│ ├── src/controllers/ <br>
│ └── src/prisma/ <br>
│ <br>
├── docs/ # Documentação e diagramas <br>
└── README.md <br>

---

## 👥 Equipe de Desenvolvimento

Gabriel Guarsoni Dadário <br>
Bruno Cavalcante Nunes <br>
Bruno Henrique Franco Paião <br>
Reinaldo Candeo Filho <br>
Matheus Lemos

---

## 📅 Status Atual do Projeto
- [x] Backlog de Produto definido  
- [x] Planejamento da Sprint 1 (HU01 e HU02)  
- [ ] Implementação inicial das telas principais  
- [ ] Configuração da API e banco de dados  
- [ ] Deploy em ambiente de staging  

---

## 🧭 Próximos Passos
- Integração das telas com o backend real (API REST).  
- Implementação da autenticação de usuários.  
- Inclusão de sistema de comentários e notificações.  

---

📘 **Documentação adicional:**  
- [Product Backlog](./docs/product_backlog.md) 
- [Diagramas](./docs/architecture.md)  

