# Portal dos Cursos Integrados de Vigilância em Saúde

Site moderno e responsivo desenvolvido com [Quarto](https://quarto.org) para divulgação dos **10 Cursos Integrados de Análise de Dados para a Vigilância em Saúde**.

> **Parceria institucional:** Universidade Federal de Santa Catarina (**UFSC**), Associação Brasileira de Saúde Coletiva (**ABRASCO**) e Instituto Todos pela Saúde (**ITpS**), com apoio da **Fiocruz**, **UFPel** e **UNA-SUS**.

---

## 📚 Catálogo dos 10 Cursos

| # | Curso | Carga Horária | Nível | Inscrição UFSC | Acesso Moodle |
|---|---|:---:|:---:|:---:|:---:|
| 1 | **Monitoramento das Desigualdades em Saúde na Vigilância** | 15h | Intermediário | [Inscrever-se](https://inscricoes.ufsc.br/activities/12556) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=4877) |
| 2 | **Análises de Séries Temporais aplicadas à Vigilância em Saúde** | 45h | Avançado | [Inscrever-se](https://inscricoes.ufsc.br/activities/12029) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=4350) |
| 3 | **Estatística Espacial aplicada à Vigilância em Saúde** | 45h | Avançado | [Inscrever-se](https://inscricoes.ufsc.br/activities/12030) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=4714) |
| 4 | **Análise de Dados para a Vigilância em Saúde – Curso Básico** | 45h | Básico | [Inscrever-se](https://inscricoes.ufsc.br/activities/9897) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=3900) |
| 5 | **Visualização de Dados de Interesse para a Vigilância** | 15h | Intermediário | [Inscrever-se](https://inscricoes.ufsc.br/activities/9899) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=3901) |
| 6 | **Produção Automatizada de Relatórios na Vigilância em Saúde** | 15h | Intermediário | [Inscrever-se](https://inscricoes.ufsc.br/activities/9900) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=3902) |
| 7 | **Análise Espacial de Dados para a Vigilância em Saúde** | 15h | Intermediário | [Inscrever-se](https://inscricoes.ufsc.br/activities/9903) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=3905) |
| 8 | **Construção de Painéis (Dashboards) para Monitoramento** | 15h | Intermediário | [Inscrever-se](https://inscricoes.ufsc.br/activities/9901) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=3906) |
| 9 | **Linkage de Bases de Dados de Saúde** | 15h | Avançado | [Inscrever-se](https://inscricoes.ufsc.br/activities/9884) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=3904) |
| 10 | **Construção de Diagramas de Controle na Vigilância** | 15h | Intermediário | [Inscrever-se](https://inscricoes.ufsc.br/activities/9898) | [Acessar](https://grupos.moodle.ufsc.br/course/view.php?id=3903) |

---

## 🚀 Como executar e desenvolver localmente

### Pré-requisitos
* [Quarto CLI](https://quarto.org/docs/get-started/) (v1.4 ou superior)
* Opcional: [RStudio Desktop](https://posit.co/download/rstudio-desktop/)

### Comandos principais

1. **Visualizar localmente com hot-reload:**
   ```bash
   quarto preview
   ```
   O navegador abrirá automaticamente em `http://localhost:XXXX/`. Qualquer alteração nos arquivos `.qmd` ou no `styles.scss` atualizará a página instantaneamente.

2. **Compilar o site completo para produção:**
   ```bash
   quarto render
   ```
   Os arquivos compilados são gerados na pasta `docs/`.

---

## 🌐 Publicação no GitHub Pages

O projeto está configurado para publicar diretamente a partir da pasta `docs/` da branch `main`:

1. Faça o commit e push dos arquivos:
   ```bash
   git add .
   git commit -m "feat: site modernizado dos cursos de vigilância"
   git push origin main
   ```
2. No repositório do GitHub, vá em **Settings** > **Pages**:
   * **Source**: `Deploy from a branch`
   * **Branch**: `main`
   * **Folder**: `/docs`
   * Clique em **Save**.
3. O site estará disponível em instantes no endereço público do GitHub Pages.
