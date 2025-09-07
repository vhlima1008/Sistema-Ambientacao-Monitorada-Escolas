# Sistema de Ambientação Monitorada em Escolas (SAME)
![Languages](https://img.shields.io/github/languages/count/vhlima1008/Sistema-Ambientacao-Monitorada-Escolas)
![Activity](https://img.shields.io/github/commit-activity/t/vhlima1008/Sistema-Ambientacao-Monitorada-Escolas)
![Contributors](https://img.shields.io/github/contributors/vhlima1008/Sistema-Ambientacao-Monitorada-Escolas)
![Size](https://img.shields.io/github/repo-size/vhlima1008/Sistema-Ambientacao-Monitorada-Escolas)

> **Aplicação web para monitorar e visualizar ambientes escolares, com perfis de acesso e painéis de dados.**

## Visão geral
O **SAME** organiza dados do ambiente estudantil e os apresenta em **dashboards** por **perfil de usuário** (*administrador*, *funcionário*, *aluno*), com busca e estrutura modular para futuras integrações de sensores/IoT.

## Status / Roadmap
**Concluído**
- [x] Estrutura de **perfis** (`administrador`, `funcionario`, `aluno`)
- [x] Base **React + TypeScript** com organização por módulos
- [x] **Barra de busca** inicial (pasta `search_bar/`)

**Em desenvolvimento**
- [ ] Integração com **sensores** (API/IoT) e persistência
- [ ] **Dashboards** com gráficos e histórico por sala/andar
- [ ] **Alertas** (limiares de conforto e saúde) e notificações
- [ ] **Autenticação e autorização** por função
- [ ] Exportação de **relatórios** (CSV/PDF)

## Stack
- **Front-end:** React + TypeScript  
- **Estilo & UI:** CSS modular
- **Arquitetura de pastas:** `src/`, `administrador/`, `funcionario/`, `aluno/`, `search_bar/`

## Como executar
1. **Clonar**
   ```bash
   git clone https://github.com/vhlima1008/Sistema-Ambientacao-Monitorada-Escolas.git
   cd Sistema-Ambientacao-Monitorada-Escolas
