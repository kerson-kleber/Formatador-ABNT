# ⊞ Formatador ABNT

Ferramenta web **100% offline** para formatação acadêmica de Artigos Científicos e TCC/Monografias conforme as normas ABNT vigentes — **NBR 6022, NBR 6027 e NBR 10520**.

Um único arquivo HTML autocontido. Sem instalação, sem servidor, sem conta, sem dados enviados a lugar nenhum.

---

## 🎓 Filosofia do projeto

Este projeto foi criado para democratizar o acesso à formatação acadêmica.

Muitos estudantes enfrentam dificuldades com normas, margens, espaçamentos e elementos pré-textuais. O objetivo desta ferramenta é reduzir essas barreiras técnicas, permitindo que o estudante concentre seus esforços naquilo que realmente importa: pesquisar, refletir, aprender e produzir conhecimento.

**A ferramenta só formata o que o estudante mesmo escreve, cola e indica — ela nunca decide nada por ele.** Não há detecção automática de citações, referências ou estrutura em nenhuma das três abas. O aprendizado ocorre também durante a escrita; por isso, o Formatador ABNT não produz conteúdo acadêmico algum, só organiza o que já foi produzido.

Gratuito, livre e desenvolvido para apoiar a educação.

## 📌 Compatibilidade institucional

Embora o documento seja gerado seguindo as principais normas ABNT vigentes, algumas instituições de ensino possuem manuais próprios com exigências específicas. Recomenda-se conferir as orientações da sua instituição e realizar eventuais ajustes após a geração do documento.

## 📚 Observações acadêmicas

Este formatador auxilia exclusivamente na organização e formatação técnica de trabalhos acadêmicos conforme os padrões ABNT mais utilizados. A elaboração do conteúdo, a pesquisa bibliográfica, a análise dos dados, a argumentação científica, a revisão textual e a qualidade acadêmica do trabalho permanecem sob responsabilidade do autor.

---

## ✨ Funcionalidades

### ① Artigo / TCC
- Alternância entre dois modelos de documento: **Artigo Científico** e **TCC / Monografia**
- Modo TCC exibe automaticamente os campos adicionais de capa e folha de rosto (instituição, curso, orientador, local)
- Campos pré-textuais completos: título, autor, instituição, e-mail, data, resumo, palavras-chave
- Corpo do trabalho: introdução, desenvolvimento (com subtítulos numerados), conclusão e referências
- Geração de arquivo **.docx** pronto pra abrir no Word/LibreOffice, com nome de arquivo derivado do título

### ② Referências
- Não gera referências automaticamente — orienta o estudante a usar o **MORE/UFSC** (Mecanismo Online para Referências), gerador oficial e gratuito conforme a NBR 6023:2018
- Botão de acesso direto ao MORE
- Botão **A→Z** para ordenar alfabeticamente as referências já coladas no campo, por sobrenome

### ③ Citações (NBR 10520)
Três sub-abas, cada uma com formatação e validação de campos obrigatórios:
- **Direta curta** — citação direta de até 3 linhas, com aspas
- **Direta longa** — citação direta com mais de 3 linhas, recuada
- **Indireta** — paráfrase, com página opcional
- Marcador de supressão `[...]` inserível no ponto do cursor
- Campo opcional de "referência completa" para conferência lado a lado
- Botão de copiar a citação formatada

---

## 📂 Estrutura do repositório

| Arquivo | Descrição |
|---|---|
| `Formatador_ABNT_v3_DIST.html` | Versão de distribuição — pronta pra baixar e usar |

O código-fonte é mantido e evoluído em ambiente próprio; este repositório disponibiliza a versão de distribuição, testada e validada, para uso direto pelo estudante.

## 🚀 Como usar

1. Baixe o arquivo `Formatador_ABNT_v3_DIST.html`
2. Abra no navegador — **recomendado Edge ou Firefox** (o Chrome tem restrições com `file://` que podem afetar o funcionamento local)
3. Preencha os campos e gere seu documento — nenhuma informação sai do seu computador

Não requer internet após o carregamento inicial, não usa `localStorage`, não coleta nenhum dado do estudante.

## 🧩 Tecnologia

Arquivo HTML único, sem dependências externas além da biblioteca [docx.js](https://docx.js.org/) (terceiros, embutida) para geração dos arquivos `.docx`.

## 📄 Licença

**Filantrópica e livre.** Distribuição permanentemente gratuita, desde que citado o autor.

> *"De graça recebestes, de graça dai."* — Mt 10.8

Desenvolvido por **Kerson Kleber Espínola Pereira** — TILSP · Professor
