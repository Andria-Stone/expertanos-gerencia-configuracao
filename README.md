# 📚 Expertanos
 
### Sistema de Organização e Acompanhamento de Estudos
 
Projeto Integrador da disciplina de **Gerência de Configuração de Software**, que aplica práticas de identificação, controle e versionamento durante a adaptação e evolução do sistema Expertanos.
 
---
 
## 🎯 Sobre o projeto
 
O **Expertanos** é uma aplicação web voltada à organização e ao acompanhamento da rotina de estudos. Reúne ferramentas de planejamento, produtividade e gamificação para estudantes.
 
O projeto parte de uma aplicação existente (protótipo web) e a adapta conforme o [Plano de Projeto](docs/Plano_de_Projeto.pdf) e a [Especificação de Requisitos](docs/Especifica%C3%A7%C3%B5es%20de%20Requisitos.pdf), controlando seus artefatos com práticas de Gerência de Configuração.
 
## 📍 Estado atual (25/11/2026)
 
| Componente | Situação | Local |
|---|---|---|
| Documentação de GCS (Plano, ERS, Inventário de ICs, Matrizes de Rastreabilidade, Status Accounting) | Documentos presentes; versões e status em revisão | `docs/` |
| Frontend (protótipo em HTML/CSS/JS, dados no `localStorage` do navegador) | Código importado do repositório de origem; funciona como MVP local, sem contas de usuário | `frontend/` |
| Backend, banco de dados, migrações, contrato de API, testes automatizados, CI | Previstos no Plano de Projeto; **ainda não presentes neste repositório** | — |
| Baselines, PCM, auditorias FCA/PCA, relatório final | Previstos no Plano de Projeto; sem evidências no repositório até esta data | — |
 
## 📁 Organização do repositório
 
```
expertanos-gerencia-configuracao/
├── README.md                  este arquivo
├── docs/                      documentação e artefatos de GCS
│   ├── README.md              índice dos artefatos
│   ├── Plano_de_Projeto.pdf
│   ├── Especificações de Requisitos.pdf
│   ├── Status_Accounting.pdf
│   ├── Inventario_ICs.xlsx
│   ├── matriz_de_rastreabilidade_RF.xlsx
│   ├── matriz_de_rastreabilidade_RNF.xlsx
│   └── Analise_de_Aderencia_e_Divergencias.md
└── frontend/                  protótipo web do Expertanos
    ├── README.md              descrição do sistema
    ├── index.html
    ├── script.js
    ├── style.css
    └── .vscode/settings.json
```
 
Pastas como `backend/`, `db/` e `tests/` serão criadas quando houver conteúdo real a controlar.
 
## ▶️ Como executar o frontend
 
1. Abra a pasta `frontend/` no VS Code.
2. Com a extensão **Live Server**, inicie o servidor (a porta configurada em `.vscode/settings.json` é a 5501), ou abra o `index.html` diretamente no navegador.
Observações:
 
- Os arquivos de áudio do player (`1.mp3`, `2.mp3`, `3.mp3`) **não foram incluídos** no repositório (origem e licença a confirmar). Sem eles, o player de estudo não reproduz som; as demais funções não são afetadas.
- As fontes (Google Fonts) são carregadas da internet.
## ✨ Funcionalidades
 
O frontend atual implementa, de forma local: Pomodoro com pausa automática ao sair da aba, tarefas, flashcards, XP e níveis, sequência de dias (streak), meta diária fixa e resumo semanal. O ranking usa usuários simulados.
 
Cadastro, login, banco de dados, edição de tarefas e flashcards, gerenciamento de metas e histórico detalhado estão previstos nos requisitos e ainda não foram implementados. O detalhamento por requisito está em [`docs/Analise_de_Aderencia_e_Divergencias.md`](docs/Analise_de_Aderencia_e_Divergencias.md).
 
## ⚙️ Gerência de Configuração
 
Práticas previstas no Plano de Projeto: identificação e inventário de Itens de Configuração (ICs); controle de versões; Matriz de Rastreabilidade; Status Accounting; Processo de Controle de Mudanças (PCM/RFC); baselines (BL-REQ-S1, BL-IMPL-S2, BL-REL-S3); auditorias FCA e PCA.
 
## 🛠️ Tecnologias e ferramentas
 
- **Em uso:** HTML5, CSS e JavaScript (frontend); Git e GitHub; Google Docs.
- **Previstas no Plano de Projeto:** banco de dados, contrato de API com coleção Postman, integração contínua. Tecnologias de backend e banco: a confirmar pela equipe.
 
## 🎓 Contexto acadêmico
 
- **Instituição:** Centro Universitário Fametro
- **Curso:** Bacharelado em Engenharia de Software
- **Disciplina:** Gerência de Configuração de Software
- **Projeto:** Expertanos - Sistema de Organização e Acompanhamento de Estudos
- **Equipe:** Ândria Pereira, Adrianne Veiga, Gabriel Ramos, Giovanna Martins, Sebastião Lopes
- **Ano:** 2026
 
