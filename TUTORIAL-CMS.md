---
title: Tutorial do CMS
nav_order: 99
layout: home
has_children: false
has_toc: true
---

# Como editar o site de ementas

O painel de administração fica em:

**[https://cursos.ombudsmanviktor.me/admin/](https://cursos.ombudsmanviktor.me/admin/)**

---

## 1. Fazendo login

1. Acesse o endereço acima
2. Clique em **"Login with GitHub"**
3. Autorize o acesso na tela do GitHub (só é necessário na primeira vez)
4. Você será redirecionado ao painel de administração

---

## 2. Conhecendo o painel

O painel tem duas seções na coluna da esquerda:

- **Ementas** — lista todas as ementas de cursos
- **Páginas** — acesso à página inicial do site

---

## 3. Editando uma ementa existente

1. Clique em **Ementas** na coluna da esquerda
2. Clique no nome da ementa que deseja editar
3. Faça as alterações no editor de texto
4. Clique em **"Save"** no topo da página
5. Aguarde de 1 a 2 minutos — o site será atualizado automaticamente

---

## 4. Criando uma nova ementa

1. Clique em **Ementas** na coluna da esquerda
2. Clique no botão **"New Ementa"**
3. Preencha os campos:
   - **Título:** nome da disciplina (ex: `Comunicação e Cultura Digital`)
   - **Mostrar índice (TOC):** deixe marcado
   - **Ordem na navegação:** mantenha o valor `2`
   - **Conteúdo:** escreva o texto da ementa
4. Clique em **"Save"**

### Renomeando o arquivo (convenção do site)

O CMS cria o arquivo com nome gerado a partir do título (ex: `comunicacao-e-cultura-digital.md`). O padrão do site é `ANO-SEMESTRE-PROGRAMA-TEMA.md`. Para renomear:

1. Acesse [github.com/ombudsmanviktor/syllabus](https://github.com/ombudsmanviktor/syllabus)
2. Clique no arquivo novo na lista
3. Clique no ícone de lápis **(Edit this file)**
4. Clique no nome do arquivo no topo e renomeie (ex: `2026-2-gec-cultura-digital.md`)
5. Clique em **"Commit changes"**

---

## 5. Inserindo imagens

1. No editor de conteúdo, clique no ícone de **imagem** na barra de ferramentas
2. Clique em **"Choose an image"** e depois em **"Upload"**
3. Selecione o arquivo do seu computador
4. A imagem será inserida automaticamente no texto

---

## 6. Formatação do conteúdo (Markdown)

O editor usa **Markdown**. Use a barra de ferramentas para formatar, ou escreva diretamente:

| O que você quer | Como escrever | Resultado |
|---|---|---|
| Título grande | `## Título` | Seção principal |
| Título médio | `### Subtítulo` | Subseção |
| Negrito | `**texto**` | **texto** |
| Itálico | `*texto*` | *texto* |
| Link | `[texto](https://url.com)` | Link clicável |
| Lista com marcadores | `- item` | • item |
| Lista numerada | `1. item` | 1. item |
| Linha divisória | `---` | Linha horizontal |

### Estrutura recomendada para uma ementa

```
# Nome da Disciplina

**Professor:** Nome — email@uff.br
**Período:** 2026/2
**Horário:** Terça, 14h–17h

## Ementa

Descrição geral do curso...

## Recursos da Disciplina

- [Google Classroom](https://link)
- [Drive](https://link)

## Programa de Curso

### Aula 1 — Data

Tema da aula.

**Leituras Recomendadas**
- AUTOR, Nome. *Título*. Editora, ano.

## Bibliografia Resumida

- AUTOR, Nome. *Título*. Editora, ano.
```

---

## 7. Publicando as alterações

Ao clicar em **"Save"**, as alterações são commitadas diretamente no repositório GitHub. O GitHub Actions inicia automaticamente o build do Jekyll e publica o site em cerca de **1 a 2 minutos**.

Você pode acompanhar o progresso do deploy em:
[github.com/ombudsmanviktor/syllabus/actions](https://github.com/ombudsmanviktor/syllabus/actions)

---

## 8. Dúvidas frequentes

**O site não atualizou depois que salvei. O que fazer?**
Aguarde 2 minutos e atualize a página. Se ainda não aparecer, verifique o status do build em Actions no GitHub.

**Posso desfazer uma alteração?**
Sim. Toda alteração feita pelo CMS gera um commit no GitHub. Para desfazer, acesse o repositório, clique no commit indesejado e use "Revert" — ou peça ajuda a alguém familiar com Git.

**O CMS não carrega / botão de login não aparece.**
Verifique se o endereço está correto: `https://cursos.ombudsmanviktor.me/admin/`. Se o problema persistir, tente em uma aba anônima.
