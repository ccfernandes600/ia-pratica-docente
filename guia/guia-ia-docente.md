# GUIA PRÁTICO: IA NA PRÁTICA DOCENTE
## Tarefas do dia a dia com as ferramentas Google + Gemini institucional
*Versão genérica — para qualquer escola ou rede de ensino que use o Google Workspace for Education*

> **Sobre esta versão:** este guia serve a qualquer professor ou servidor da educação. Onde aparecer "sua escola" ou "sistema acadêmico", entenda o sistema que a sua instituição usa (SUAP, SIGAA, sistema da secretaria estadual, plataforma própria, etc.). Adapte os exemplos à sua realidade.

---

## COMO USAR ESTE GUIA

Este material é um **receituário**: cada tarefa do seu dia a dia vira uma receita curta que você pode aplicar em minutos. A lógica é sempre a mesma:

> **Quando usar a IA → Passo a passo → Prompt pronto para copiar → O que conferir antes de usar.**

- **Se você é iniciante:** leia o corpo de cada receita. É o suficiente para resolver a tarefa.
- **Se você já tem prática:** ao fim de cada receita há um gancho para o **Apêndice B**, com prompts mais sofisticados, variações e formas de combinar tarefas.
- **Antes de qualquer receita**, leia a **Seção 1 (Régua de Segurança)**. Ela protege você e seus alunos, e é referenciada o tempo todo.

---

## SUMÁRIO

**Núcleo do guia**
- **Seção 0** — Princípios (leia primeiro)
- **Seção 1** — Régua de Segurança (LGPD)
- **Seção 2** — Comunicação · *responder e-mail · comunicado no mural · feedback*
- **Seção 3** — Preparação de aula · *plano de aula · adaptar nível · analogias · slides*
- **Seção 4** — Avaliação · *questões · rubrica · análise de turma · prova/quiz · planilhas*
- **Seção 5** — Burocracia docente · *plano de ensino · parecer · registro de aula*
- **Box de fronteira** — Automação do sistema acadêmico da escola (fora do escopo)

**Apêndices**
- **Apêndice A** — Prompts e instruções personalizadas (configure a IA uma vez)
- **Apêndice B** — Versões estruturadas das receitas (para quem já tem prática)
- **Apêndice C** — Criar imagens para uso didático (infográfico, linha do tempo, diagrama)
- **Apêndice D** — Simulações interativas para aulas de ciências (avançado)
- **Apêndice E** — Recursos da sua conta institucional Google (Gems, NotebookLM)

---

## SEÇÃO 0 — PRINCÍPIOS (leitura de 2 minutos)

1. **A IA é assistente, não professor.** Ela redige rascunhos e organiza ideias. O conhecimento, o julgamento pedagógico e a responsabilidade final são seus.
2. **A IA erra com confiança.** Ela inventa prazos, regras, contas e trechos de código com aparência correta. **Tudo que for fato, número ou código você confere antes de usar.**
3. **Dado de aluno não entra na IA.** Veja a Régua de Segurança a seguir. Esta é a regra que não se quebra.
4. **Atenção à idade de alunos menores.** Os recursos de IA voltados diretamente ao **aluno** (quizzes interativos, tutores) exigem 18+. Você pode usar a IA para *preparar* o material; o que é entregue diretamente a alunos menores de idade precisa de cuidado. Na dúvida, confirme a política da conta.

---

## SEÇÃO 1 — RÉGUA DE SEGURANÇA (LGPD)
*Leia antes de usar qualquer receita deste guia.*

A maioria das tarefas docentes envolve **dados pessoais de alunos**. A IA é uma ferramenta de terceiros: tudo que você cola nela sai do seu controle. Esta régua existe para que você use a IA **sem expor ninguém**.

### A regra de ouro (uma frase)
> **A IA pode ver o *texto* e a *estrutura*; nunca a *identidade* do aluno.**

### Checklist de 4 passos (antes de colar qualquer coisa)
1. **Removi nomes?** Troque por "o aluno", "a estudante", "Aluno A".
2. **Removi matrículas, e-mails e telefones?** Nenhum identificador direto.
3. **Removi dados sensíveis?** Situação socioeconômica, saúde, laudos, ocorrências.
4. **O texto ainda faz sentido anonimizado?** Se sim, pode usar. Se não, repense se a IA é mesmo necessária.

### Tabela de referência rápida

| ❌ Nunca colar na IA | ✅ Como adaptar antes |
| :--- | :--- |
| Nome do aluno | "o aluno", "Aluno A", "a turma" |
| Matrícula / e-mail / telefone | Remover por completo |
| Planilha de notas com nomes | Exportar **sem** a coluna de identificação, ou substituir nomes por A, B, C |
| Relato sobre saúde/família/situação social | Não usar a IA para isso — é dado sensível |
| Print do sistema acadêmico com dados | Não colar; transcreva só o trecho técnico já anonimizado |
| Ocorrência disciplinar / conselho de classe | Descreva a situação sem identificar o aluno; nunca o caso nominal |
| **Foto de aluno ou de pessoa identificável** (para gerar/editar imagem) | **Nunca enviar.** Geração de imagem é só para conteúdo didático (conceitos, processos), nunca retratos de pessoas reais da comunidade escolar |

> 🔎 **Por que isso importa:** a LGPD (Lei 13.709/2018) vale mesmo que a sua escola ainda não tenha norma interna sobre IA. A responsabilidade por um vazamento recai sobre quem colou o dado.

---

## SEÇÃO 2 — COMUNICAÇÃO
*Ferramentas: Gmail e Google Classroom + Gemini institucional.*

### 📩 Receita 2.1 — Responder e-mail de aluno

**Contexto — quando usar**
Quando precisa responder com clareza e empatia, mas está sem tempo ou sem o tom certo. A IA monta o rascunho; você revisa e envia.

**Passo a passo**
1. Leia o e-mail e identifique o que o aluno realmente pede.
2. **Anonimize** (Seção 1): nada de nome ou dados no prompt.
3. Cole o prompt abaixo no Gemini, preenchendo os `[colchetes]`.
4. Revise tom, informação e se nada pessoal escapou.
5. Cole no Gmail, ajuste a saudação e envie.

**Prompt pronto**
> "Atue como professor de `[sua disciplina]`. Escreva uma resposta de e-mail breve, clara e cordial para um aluno que perguntou o seguinte: `[resuma a dúvida, sem nomes]`. A resposta deve `[informar / orientar / tranquilizar]` e terminar com uma frase de incentivo. Não use linguagem rebuscada."

**O que conferir**
- [ ] Nenhum dado pessoal no prompt.
- [ ] A informação está **correta** (a IA pode inventar prazos/regras).
- [ ] O tom combina com a sua forma de falar com a turma.

> ➕ Versão estruturada: **Apêndice B.2.1**

---

### 📢 Receita 2.2 — Redigir comunicado para o mural do Classroom

**Contexto — quando usar**
Para transformar um aviso corrido ("prova adiada, novo conteúdo, traga notebook") em um comunicado claro e organizado.

**Passo a passo**
1. Liste, em tópicos soltos, tudo que precisa avisar.
2. Cole o prompt abaixo no Gemini.
3. Revise datas e instruções (a IA pode trocar um dia).
4. Cole no mural do Classroom.

**Prompt pronto**
> "Transforme os avisos abaixo em um comunicado curto e organizado para o mural de uma turma `[do seu nível]`. Use tom direto e amigável, destaque a data principal e termine com o que o aluno precisa fazer. Avisos: `[cole seus tópicos]`."

**O que conferir**
- [ ] Datas e horários **batem** com a realidade.
- [ ] A ação esperada do aluno ficou clara.

> 🎨 **Dica visual:** dá para gerar um cartaz ou banner para acompanhar o comunicado no mural — ver **Apêndice C.1**.

> ➕ Versão estruturada: **Apêndice B.2.2**

---

### 🔁 Receita 2.3 — Padronizar feedback de uma atividade

**Contexto — quando usar**
Quando vários alunos cometeram erros parecidos e você quer um feedback consistente, sem reescrever do zero para cada um.

**Passo a passo**
1. Liste os erros mais comuns que você observou (sem nomes).
2. Cole o prompt abaixo.
3. Revise se o feedback está correto e construtivo.
4. Adapte pontualmente para cada aluno na hora de enviar.

**Prompt pronto**
> "Sou professor de `[sua disciplina]`. Os alunos cometeram os erros abaixo numa atividade. Para cada erro, escreva um feedback curto, respeitoso e que ajude o aluno a entender o que rever — sem dar a resposta pronta. Erros: `[liste os erros, sem nomes]`."

**O que conferir**
- [ ] O feedback **orienta** sem entregar a solução.
- [ ] O tom não é desmotivador.

> ➕ Versão estruturada: **Apêndice B.2.3**

---

## SEÇÃO 3 — PREPARAÇÃO DE AULA
*Ferramentas: Google Docs e Apresentações + Gemini.*

### 📝 Receita 3.1 — Esboçar um plano de aula

**Contexto — quando usar**
Para sair do zero rápido. A IA gera um esqueleto; você ajusta à realidade do seu laboratório e da sua turma.

**Passo a passo**
1. Defina tema, duração e nível da turma.
2. Cole o prompt abaixo.
3. **Valide a viabilidade**: o plano cabe no tempo e nos equipamentos que você tem?
4. Ajuste e leve para o Docs/Classroom.

**Prompt pronto**
> "Atue como professor de `[sua disciplina]`. Esboce um plano de aula de `[duração]` sobre `[tema, ex.: estruturas de repetição em Python]` para turma de nível `[iniciante/intermediário]`. Inclua: objetivo, sequência de atividades com tempo estimado, e uma atividade prática curta. Não inclua avaliação formal."

**O que conferir**
- [ ] O tempo estimado é **realista** para a sua turma.
- [ ] A atividade prática roda nos computadores do laboratório.
- [ ] Os exemplos de código (se houver) **funcionam** — teste antes.

> ➕ Versão estruturada: **Apêndice B.3.1**

---

### 🎚️ Receita 3.2 — Adaptar o nível de um material

**Contexto — quando usar**
Quando tem um texto/explicação pronta, mas ela está difícil demais (ou simples demais) para a turma.

**Passo a passo**
1. Copie o trecho que quer adaptar (material seu ou de domínio público — não cole conteúdo protegido inteiro).
2. Cole o prompt indicando o ajuste desejado.
3. Revise se a adaptação não perdeu precisão técnica.

**Prompt pronto**
> "Reescreva o texto abaixo para alunos iniciantes `[do seu nível]`, mantendo a precisão técnica mas usando linguagem simples e um exemplo do cotidiano. Não invente informação que não esteja no texto. Texto: `[cole aqui]`."

**O que conferir**
- [ ] A simplificação **não distorceu** o conceito.
- [ ] Nenhum dado novo foi inventado pela IA.

> ➕ Versão estruturada: **Apêndice B.3.2**

---

### 💡 Receita 3.3 — Gerar analogias e exemplos para um conceito difícil

**Contexto — quando usar**
Quando um conceito "não entra" e você quer formas alternativas de explicar.

**Passo a passo**
1. Nomeie o conceito e o que costuma confundir os alunos.
2. Cole o prompt.
3. Escolha a analogia que combina com a sua turma (descarte as que não servem).

**Prompt pronto**
> "Explique o conceito de `[ex.: laço de repetição]` de 3 formas diferentes para alunos iniciantes: uma analogia do cotidiano, um exemplo visual e um exemplo mínimo de código em Python 3.11. Mantenha cada uma curta."

**O que conferir**
- [ ] A analogia **não cria** um entendimento errado.
- [ ] O código de exemplo roda e está atualizado.

> 🎨 **Dica visual:** gere um diagrama do conceito para reforçar a explicação — ver **Apêndice C.3**.

> ➕ Versão estruturada: **Apêndice B.3.3**

---

### 🖼️ Receita 3.4 — Gerar a estrutura de uma apresentação (Slides)

**Contexto — quando usar**
Para sair de uma página em branco. A IA monta o esqueleto da apresentação (títulos e tópicos por slide); você refina o conteúdo e o visual.

**Passo a passo**
1. Defina o tema, o número de slides e o nível da turma.
2. No Google Apresentações, use **"Ajude-me a criar"** (Gemini) com o prompt abaixo — ou gere o roteiro no Gemini e cole.
3. Revise: a IA tende a colocar texto demais por slide.
4. Ajuste o visual e **teste qualquer código** que apareça nos slides.

**Prompt pronto**
> "Crie a estrutura de uma apresentação de `[8]` slides sobre `[tema]` para alunos `[do seu nível de ensino]`. Para cada slide, dê um título e até 3 tópicos curtos. Comece com um slide de abertura e termine com um de resumo. Linguagem simples."

**O que conferir**
- [ ] Cada slide tem **pouco texto** (slide não é documento).
- [ ] Os exemplos de código estão corretos e atualizados.
- [ ] A sequência faz sentido didático.

> 🎨 **Dica visual:** precisa de uma imagem para um slide? Ver **Apêndice C** (infográfico, linha do tempo ou diagrama).

> ➕ Versão estruturada: **Apêndice B.3.4**

---

## SEÇÃO 4 — AVALIAÇÃO
*Ferramentas: Google Docs e Planilhas + Gemini.*

> ⚠️ **Alerta para esta seção inteira:** a IA erra em contas e em código. **Toda questão, gabarito e cálculo gerado deve ser refeito e testado por você** antes de aplicar à turma.

### ❓ Receita 4.1 — Gerar questões a partir de um conteúdo

**Contexto — quando usar**
Para criar rascunhos de questões rapidamente a partir de um conteúdo que você já ensinou.

**Passo a passo**
1. Indique o conteúdo e o tipo de questão.
2. Cole o prompt.
3. **Resolva cada questão você mesmo** e confira o gabarito.
4. Descarte ou reescreva as que não estão boas.

**Prompt pronto**
> "Atue como professor de `[sua disciplina]`. Crie `[3]` questões `[discursivas / de múltipla escolha]` sobre `[conteúdo]`, nível iniciante. Para cada uma, forneça enunciado e gabarito comentado. Se houver código, limite a `[10]` linhas."

**O que conferir**
- [ ] Você **resolveu** cada questão e o gabarito está correto.
- [ ] O código do gabarito **roda** sem erro.
- [ ] O enunciado não é ambíguo.

> ➕ Versão estruturada: **Apêndice B.4.1**

---

### 📊 Receita 4.2 — Criar uma rubrica de correção

**Contexto — quando usar**
Para tornar sua correção mais justa e transparente, com critérios claros.

**Passo a passo**
1. Defina o que a atividade avalia e quantos níveis quer (ex.: 3).
2. Cole o prompt.
3. Ajuste os critérios ao que você realmente valoriza.

**Prompt pronto**
> "Crie uma rubrica analítica de correção para `[uma atividade prática de Python]`, com `[3]` níveis (Excelente, Regular, Insuficiente). Foque na **lógica técnica** da solução, não no estilo de escrita. Apresente em tabela."

**O que conferir**
- [ ] Os critérios refletem **o que você ensinou**.
- [ ] Os níveis são distinguíveis (não se confundem).

> ➕ Versão estruturada: **Apêndice B.4.2**

---

### 📈 Receita 4.3 — Analisar o desempenho da turma (planilha anonimizada)

**Contexto — quando usar**
Para enxergar padrões: em que conteúdo a turma foi pior, onde concentrar revisão.

> 🔒 **Atenção máxima de LGPD:** exporte a planilha de notas **sem a coluna de nomes/matrículas**. Substitua por Aluno A, B, C. Só então use a IA.

**Passo a passo**
1. Exporte do sistema acadêmico/Planilhas e **remova identificadores**.
2. Cole os dados anonimizados (ou descreva-os).
3. Peça a análise.
4. Use a leitura para planejar revisão — a decisão pedagógica é sua.

**Prompt pronto**
> "Os dados abaixo são notas anonimizadas de uma turma (Aluno A, B, C...) por conteúdo. Aponte em quais conteúdos a turma teve mais dificuldade e sugira 2 focos de revisão. Dados: `[cole a tabela anonimizada]`."

**O que conferir**
- [ ] **Zero** identificadores na planilha.
- [ ] As médias/contas conferem (a IA erra em aritmética).

> ➕ Versão estruturada: **Apêndice B.4.3**

---

### 📝 Receita 4.4 — Montar uma prova/quiz (Classroom + Forms)

**Contexto — quando usar**
Para transformar questões em um quiz aplicável e corrigível na turma. A IA redige as questões; **você configura a avaliação**.

> ⚠️ **O que a IA faz e o que não faz:** o Gemini gera as perguntas e as opções de resposta, mas **gabarito, pontuação e feedback são marcados por você, manualmente.** Não existe "prova pronta com um clique".
> 🔞 **Idade:** recursos de IA voltados ao **aluno** exigem 18+. Para o professor *gerar* o quiz, não há restrição; atenção em turmas com alunos menores de idade.

**Passo a passo — Caminho A (recomendado, com Gemini ativo na conta institucional)**
1. No Google Classroom, gere o quiz com o Gemini informando tema e nível.
2. Revise as questões e **exporte para o Google Forms**.
3. No Forms, marque o gabarito e defina a pontuação de cada questão.
4. **Resolva você mesmo** cada questão (e teste o código, se houver) antes de atribuir à turma.

**Passo a passo — Caminho B (alternativa)**
1. No Google Forms, use **"Ajude-me a criar"** (form novo) ou **"Sugerir perguntas"** (form com 2+ questões).
2. Configure gabarito e pontuação.
3. Atribua o Form pelo Classroom como qualquer atividade.

**Prompt pronto (para gerar as questões)**
> "Sou professor de `[sua disciplina]`. Gere `[5]` questões de múltipla escolha sobre `[conteúdo]`, nível iniciante, cada uma com 4 alternativas e indicação da correta. Se houver código, no máximo `[8]` linhas."

**O que conferir**
- [ ] Gabarito e pontuação **configurados** (a IA não faz isso).
- [ ] Você **resolveu** cada questão; o código roda.
- [ ] Sem dados de aluno em nenhum momento do processo.

> ➕ Versão estruturada: **Apêndice B.4.4**

---

### 🧮 Receita 4.5 — Apoio com fórmulas e organização (Planilhas)

**Contexto — quando usar**
Para montar cálculos de notas/médias, condicionais ("aprovado/reprovado") e organização de dados — sem decorar sintaxe de fórmula.

> 🔒 Trabalhe com a planilha **anonimizada** sempre que ela contiver dados de aluno (ver Seção 1 e Receita 4.3).

**Passo a passo**
1. Descreva o que quer calcular (sem colar dados reais de aluno).
2. Cole o prompt; a IA devolve a **fórmula** e onde aplicá-la.
3. Cole a fórmula na célula e **confira o resultado** com um caso conhecido.

**Prompt pronto**
> "No Google Planilhas, preciso de uma fórmula que `[ex.: calcule a média de B2:E2 e escreva 'Aprovado' se for ≥ 6, senão 'Reprovado']`. Explique em que célula colar e o que cada parte faz."

**O que conferir**
- [ ] A fórmula **devolve o resultado certo** num caso que você conhece.
- [ ] A IA não inventou função inexistente (acontece) — teste antes de confiar.

> ➕ Versão estruturada: **Apêndice B.4.5**

---

## SEÇÃO 5 — BUROCRACIA DOCENTE
*Texto produzido com a IA que depois você cola, **manualmente**, nos sistemas oficiais.*

> ℹ️ Lembre-se: a IA **não acessa o sistema acadêmico da escola**. Ela ajuda a redigir o texto; o lançamento no sistema é sempre feito por você. (Ver box de fronteira ao final.)

### 🗂️ Receita 5.1 — Estruturar um plano de ensino

**Contexto — quando usar**
Para organizar ementa, objetivos e cronograma num texto coeso antes de cadastrar.

**Passo a passo**
1. Reúna ementa, carga horária e tópicos.
2. Cole o prompt.
3. Revise alinhamento com o PPC/ementa oficial.
4. Cole no sistema oficial manualmente.

**Prompt pronto**
> "Organize as informações abaixo em um plano de ensino estruturado (objetivos, conteúdos por unidade, metodologia, cronograma). Mantenha linguagem formal de documento acadêmico. Informações: `[cole ementa, carga horária, tópicos]`."

**O que conferir**
- [ ] Bate com a **ementa oficial** do curso.
- [ ] Carga horária e cronograma fecham.

> ➕ Versão estruturada: **Apêndice B.5.1**

---

### 🖋️ Receita 5.2 — Redigir um parecer ou registro (anonimizado)

**Contexto — quando usar**
Para dar forma clara e formal a um parecer, sem travar na escrita.

> 🔒 Descreva a situação **sem identificar o aluno**. Nada de nome, matrícula ou caso reconhecível.

**Passo a passo**
1. Descreva a situação de forma anonimizada e factual.
2. Cole o prompt.
3. **Revise integralmente** — parecer é responsabilidade sua.

**Prompt pronto**
> "Redija um parecer acadêmico formal, claro e objetivo, a partir da situação descrita a seguir (já anonimizada). Mantenha tom institucional e evite juízos pessoais. Situação: `[descreva sem identificar ninguém]`."

**O que conferir**
- [ ] Nenhum dado identificável.
- [ ] O parecer reflete **a sua avaliação**, não a da IA.

> ➕ Versão estruturada: **Apêndice B.5.2**

---

### 📅 Receita 5.3 — Organizar o registro de aula

**Contexto — quando usar**
Para transformar suas anotações soltas no registro formal do diário.

**Passo a passo**
1. Junte suas anotações da aula (tópicos dados, atividades).
2. Cole o prompt.
3. Revise e cole no diário manualmente.

**Prompt pronto**
> "Transforme as anotações abaixo em um registro de aula formal e conciso (conteúdo trabalhado e atividades realizadas), em um parágrafo. Anotações: `[cole aqui]`."

**O que conferir**
- [ ] O registro corresponde **ao que de fato** ocorreu.

> ➕ Versão estruturada: **Apêndice B.5.3**

---

## 🔭 BOX DE FRONTEIRA — AUTOMAÇÃO DO SISTEMA ACADÊMICO (fora do escopo)

A maioria das escolas usa um sistema de gestão acadêmica (lançamento de notas, frequência, diário). Embora muitas vezes seja **tecnicamente possível** automatizar tarefas nesses sistemas (alguns têm API, outros permitem agentes de navegador), **optamos por não incluir isso neste guia**, por três razões:

1. **Proteção de dados (LGPD):** o sistema acadêmico contém dados pessoais de alunos; seu tratamento por IA externa exige base legal e controles institucionais que estão fora do alcance do docente individual — e a LGPD incide independentemente de norma interna.
2. **Ausência de regulamentação:** a maioria das escolas ainda não possui norma sobre uso de IA articulado ao sistema acadêmico. Na falta dela, o caminho responsável é a prudência, não a iniciativa individual.
3. **Escopo:** este guia trata das tarefas já assistidas pela IA institucional (Workspace/Gemini); os sistemas acadêmicos, em geral, não têm essa integração.

*O caminho pode existir e ser legítimo para quem quiser aprofundar com a devida autorização da escola — mas ensiná-lo aqui fugiria ao propósito deste material.*

---

# APÊNDICE A — PROMPTS E INSTRUÇÕES PERSONALIZADAS
*A base para tirar mais proveito da IA: como pedir bem (A.1) e como configurar a IA uma vez para sempre (A.2).*

## A.1 — Engenharia de prompts em 3 níveis
*Para quem quiser entender a lógica por trás dos prompts prontos.*

- **Nível 1 — Básico:** `[Ação] + [Tema]`. Ex.: "Liste 5 exercícios sobre variáveis."
- **Nível 2 — Intermediário:** `[Papel] + [Ação] + [Público] + [Formato]`. Define quem a IA é, para quem é o material e como entregar.
- **Nível 3 — Avançado:** acrescenta `[Restrições] + [Regras]`. Ex.: limitar linhas de código, pedir rubrica, proibir ambiguidade.

> Os prompts prontos deste guia já estão, em geral, no Nível 2. As versões do Apêndice B sobem para o Nível 3.

---

## A.2 — Instruções personalizadas (configure uma vez, melhore sempre)

Este é, talvez, o recurso de **maior impacto e menor uso** da IA. Em vez de repetir seu contexto e suas preferências a cada conversa, você configura **uma vez** como a IA deve se comportar — e isso vale para *todas* as conversas seguintes.

No **Gemini**, o recurso fica em **Configurações → "Suas instruções para o Gemini"** (o nome pode variar). Outras IAs têm equivalente ("instruções personalizadas", "instruções de sistema").

### Por que vale tanto a pena
- Você para de reescrever "atue como professor, seja claro, use exemplos..." toda vez.
- As respostas saem no seu tom e no seu nível desde a primeira linha.
- É engenharia de prompt que você **não precisa repetir**.

### Como escrever uma boa instrução: pense em blocos
O erro mais comum é escrever tudo num parágrafo corrido. A IA aproveita melhor quando você **separa por blocos**:

1. **Como responder** — tom, profundidade, tamanho.
2. **Formato** — listas, resumo no início, etc.
3. **Seu contexto** — quem você é, o que ensina, seu nível.
4. **O que evitar** — instruções negativas valem tanto quanto as positivas.

### Modelo genérico para professores (adapte ao seu caso)

> **Como quero que você responda:**
> Seja claro e prático, com foco em aplicação em sala de aula. Comece simples e aprofunde só quando o tema pedir.
>
> **Formato:**
> Use tópicos e listas quando ajudarem a clareza. Em respostas longas, comece com um resumo.
>
> **Meu contexto:**
> Sou professor de `[sua disciplina]`, do `[seu nível de ensino]`. `[Acrescente o que for útil: turmas grandes, foco em prática, etc.]`
>
> **O que evitar:**
> Respostas longas demais para perguntas simples; jargão desnecessário; inventar dados ou fontes.

### Para quem quer respostas mais críticas (opcional)
Se você prefere que a IA **questione** em vez de concordar com tudo, acrescente um bloco assim:

> **Pensamento crítico:**
> Não concorde por concordar. Aponte pontos fracos, riscos e alternativas, mesmo que eu não peça. Prefiro um contraponto honesto a uma validação vazia. Evite elogios genéricos.

> 🔒 **Atenção (LGPD):** as instruções personalizadas são sobre **você** e seu estilo — nunca coloque dados de alunos nelas. Elas se aplicam a todas as conversas, então um dado pessoal ali ficaria exposto continuamente.

> ⚠️ **Dois limites honestos:** (1) há um **limite de caracteres** que varia conforme a ferramenta; seja conciso. (2) instrução personalizada **não é memória perfeita** — em conversas muito longas, a IA pode dar menos peso a partes dela. Se algo importante for ignorado, relembre no próprio chat.

---


# APÊNDICE B — VERSÕES ESTRUTURADAS
*Não repete o passo a passo do corpo. Traz só o que muda: prompt sofisticado, variações e encadeamento. Mesma numeração das receitas.*

### 🔧 B.2.1 — Responder e-mail (estruturado)
**Prompt:** "Você é um professor de `[sua disciplina]`, atencioso e objetivo. Dúvida do aluno (anonimizada): `[...]`. Tarefa: resposta de e-mail. Tom: cordial e encorajador. Restrições: máx. 6 linhas; não invente prazos — use `[CONFIRMAR]` onde faltar dado. Formato: assunto + corpo."
**Variações:** aluno ansioso → "acolha antes de orientar". Recorrente → "transforme em modelo reutilizável com lacunas".
**Encadeamento:** guarde o modelo; nas próximas vezes, cole modelo + nova dúvida e peça "adapte para o caso abaixo".
> ⚠️ O `[CONFIRMAR]` é proposital: a IA não sabe os prazos do seu curso.

### 🔧 B.2.2 — Comunicado Classroom (estruturado)
**Prompt:** acrescente "gere também uma versão de 1 linha para notificação e uma versão completa para o mural" e "destaque visualmente a data com emoji 📌".
**Encadeamento:** peça que o mesmo comunicado vire um lembrete de e-mail para reenviar 1 dia antes.

### 🔧 B.2.3 — Feedback padronizado (estruturado)
**Prompt:** "Para cada erro, gere feedback em 2 versões: uma curta (1 linha) e uma com dica de estudo. Organize em tabela: Erro | Feedback curto | Dica."
**Encadeamento:** transforme a tabela num banco de feedbacks reutilizável por tipo de erro.

### 🔧 B.3.1 — Plano de aula (estruturado)
**Prompt:** adicione "considere laboratório com `[nº]` máquinas e `[restrições, ex.: sem internet]`" e "marque com ⏱️ os pontos onde o tempo costuma estourar".
**Variação:** peça uma versão "plano B" caso uma atividade não funcione.

### 🔧 B.3.2 — Adaptar material (estruturado)
**Prompt:** "Gere 2 versões: uma para quem está com dificuldade e outra como desafio para quem já domina. Mantenha o mesmo conceito central."

### 🔧 B.3.3 — Analogias (estruturado)
**Prompt:** "Para cada analogia, aponte também onde ela **falha** (o limite da comparação), para eu não induzir erro."

### 🔧 B.3.4 — Apresentação/Slides (estruturado)
**Prompt:** acrescente "para cada slide, sugira uma imagem ou diagrama que eu possa buscar" e "inclua um slide de atividade prática no meio da sequência".
**Variação:** peça uma versão "aula invertida" — slides que o aluno estuda antes da aula.

### 🔧 B.4.1 — Questões (estruturado)
**Prompt:** "Gere questões em níveis crescentes de dificuldade e marque o nível de cada uma. Inclua, para cada questão, o erro conceitual mais provável do aluno."
> ⚠️ Continua valendo: resolva e teste tudo antes de aplicar.

### 🔧 B.4.2 — Rubrica (estruturado)
**Prompt:** "Gere a rubrica e, ao lado, um descritor observável para cada nível (o que exatamente eu veria no trabalho do aluno)."

### 🔧 B.4.3 — Análise de turma (estruturado)
**Prompt:** "Além dos focos de revisão, sugira uma atividade de reforço para o conteúdo mais fraco."
> 🔒 Os dados continuam 100% anonimizados, sempre.

### 🔧 B.4.4 — Prova/quiz (estruturado)
**Prompt:** "Gere o quiz com questões em dificuldade crescente e, em uma tabela à parte (só para mim), liste questão | resposta correta | erro conceitual mais provável." A tabela acelera a configuração manual do gabarito no Forms.
**Encadeamento:** reaproveite as questões da Receita 4.1 em vez de gerar do zero.
> ⚠️ Gabarito e pontuação continuam sendo configurados por você.

### 🔧 B.4.5 — Planilhas (estruturado)
**Prompt:** "Gere a fórmula e uma versão alternativa mais robusta (ex.: que trate célula vazia ou erro). Explique quando usar cada uma."
**Variação:** peça formatação condicional (cores) para destacar reprovados ou notas baixas.

### 🔧 B.5.1 — Plano de ensino (estruturado)
**Prompt:** "Alinhe os objetivos a verbos de competência (Bloom) e organize o cronograma por semana."

### 🔧 B.5.2 — Parecer (estruturado)
**Prompt:** "Gere o parecer e uma versão alternativa com tom mais conciso, para eu escolher."

### 🔧 B.5.3 — Registro de aula (estruturado)
**Encadeamento:** acumule registros e peça, ao fim da unidade, um resumo do que foi trabalhado no período.

---

# APÊNDICE C — CRIAR IMAGENS PARA USO DIDÁTICO COM O GEMINI
*Como gerar infográficos, linhas do tempo e diagramas para suas aulas. Técnica opcional — mas a regra de segurança abaixo não é opcional.*

> 🔒 **Antes de tudo (ver Régua, Seção 1):** a IA gera imagem de **conteúdo** (conceitos, processos, datas), **nunca de pessoas reais**. Não envie foto de aluno, colega ou de qualquer pessoa identificável para gerar ou editar imagem. Em conta escolar, os termos de uso de dados podem variar conforme a licença.

## Três coisas que você precisa saber antes

1. **Imagem é "pixel", não dado.** Um infográfico ou linha do tempo gerado é uma figura. Se você errar uma data no pedido, ela sai errada — e bonita. **Você confere os fatos na imagem final.**
2. **Editar depois é trabalhoso.** Para poder ajustar texto e elementos depois, peça a exportação em **SVG** (vetorial, editável). Caso contrário, qualquer correção exige gerar de novo.
3. **Marca d'água.** Toda imagem gerada leva uma marca d'água invisível (SynthID). Não impede o uso didático, e é um bom gancho para conversar com a turma sobre transparência no uso de IA.

> 💡 **Filosofia de uso:** o Gemini dá a "aceleração inicial" — entrega a estrutura visual pronta em segundos; o acabamento profissional (ajuste de texto, cor, posição) é seu.

---

### 🖼️ C.1 — Infográfico didático

**Quando usar:** para explicar um conceito de forma visual e atrativa.

**Prompt pronto**
> "Crie um infográfico vertical explicativo sobre `[tema]`, para alunos `[do seu nível de ensino]`. Use ícones simples, setas de fluxo e blocos de texto curtos. Paleta de cores `[ex.: azul e cinza]`. Mantenha o texto correto e legível."

**O que conferir**
- [ ] Todos os **textos e dados** na imagem estão corretos (a IA erra e escreve errado).
- [ ] Está legível quando projetado/impresso.
- [ ] Se vai editar depois, **peça versão em SVG**.

---

### 🕰️ C.2 — Linha do tempo

**Quando usar:** para mostrar evolução histórica, etapas de um processo ou versões de uma tecnologia.

**Prompt pronto**
> "Crie uma linha do tempo visual sobre `[assunto]`, de `[ano inicial]` a `[ano final]`. Destaque `[3 a 5]` marcos principais, cada um com data e uma frase curta. Layout horizontal, limpo, para projetar em sala."

**O que conferir**
- [ ] **Cada data e a ordem** dos eventos conferem (este é o erro mais comum aqui).
- [ ] Os marcos escolhidos são os que você quer enfatizar.

---

### 🔗 C.3 — Diagrama ou ilustração de um conceito

**Quando usar:** para visualizar um processo, uma estrutura ou um fluxo (ex.: como um laço de repetição funciona, etapas de um algoritmo).

**Prompt pronto**
> "Ilustre de forma didática o conceito de `[ex.: estrutura de repetição]` para iniciantes, como um diagrama com etapas numeradas e setas. Texto curto em cada etapa. Estilo limpo, fundo claro."

**O que conferir**
- [ ] O diagrama **não inventou** etapas ou relações erradas (revise a lógica).
- [ ] Para fluxograma/diagrama que você vai **editar**, prefira pedir SVG — ou montar numa ferramenta de diagrama a partir do texto que a IA gerar.

> ⚠️ **Limite:** "imagem de um fluxograma" não é um fluxograma editável. Para diagramas técnicos que mudam com frequência, a imagem serve de rascunho; o objeto final é melhor construído em ferramenta própria.

---

# APÊNDICE D — SIMULAÇÕES INTERATIVAS PARA AULAS DE CIÊNCIAS (AVANÇADO)
*Como usar a IA para criar simulações de fenômenos físicos — pêndulo, órbitas, lançamento de foguete, reações — com botões deslizantes (sliders) que dão dinâmica à demonstração.*

> ⚠️ **Este apêndice é avançado e opcional.** Ele serve a professores de ciências, exatas ou programação que queiram demonstrações visuais e interativas. Não exige programar do zero — a IA escreve o código —, mas exige um cuidado que os outros apêndices não têm: **validar a física, não só o visual.**

## A regra de ouro deste apêndice

> **A IA acerta o visual com facilidade e erra a física com a mesma facilidade.**

Uma simulação de órbita pode ficar linda e ter o período orbital errado; um pêndulo pode oscilar bonito com uma gravidade que não corresponde à realidade. Para o aluno, o erro é invisível — ele *vê* a animação e acredita. **Você é quem garante que a física está correta.** Por isso, cada receita aqui termina em "como validar".

## Três coisas que você precisa saber antes

1. **Onde isso roda.** Simulação interativa com sliders é uma página web (HTML + JavaScript). O Gemini gera o código, mas para **rodar e ver funcionando** o ideal é uma ferramenta que execute o artefato na hora (como o Claude, que roda a simulação no próprio chat) ou o **Google Colab** (seu terreno, com Python — ótimo para cálculo, embora o slider interativo seja mais simples que em HTML). O Gemini puro gera o código, mas o "ver rodando" é menos fluido.
2. **Slider precisa de faixa com sentido físico.** Peça explicitamente os limites (ex.: gravidade de 1 a 25 m/s²), senão a IA inventa faixas sem nexo (comprimento de pêndulo de 0 a 10.000 m).
3. **Comece simples e itere.** Peça primeiro a versão mínima que funciona; depois acrescente sliders e refinamentos. Tentar tudo num prompt só gera código que quebra e é difícil de depurar.

---

## D.1 — Receita-modelo: Pêndulo simples

*(Escolhi o pêndulo como modelo porque a física é validável com uma fórmula só — perfeito para você conferir se a IA acertou.)*

**Prompt pronto**
> "Crie uma simulação interativa de um pêndulo simples em HTML com JavaScript (canvas). Requisitos:
> - Um pêndulo que oscila de forma fisicamente realista (use a equação do pêndulo).
> - **Sliders** para: comprimento do fio (0,2 a 3 m), gravidade (1 a 25 m/s²) e ângulo inicial (5° a 60°).
> - Mostre na tela o **período de oscilação** calculado.
> - Visual limpo, fundo claro, pronto para projetar em sala.
> Comece com a versão funcional mínima; eu peço ajustes depois."

**Como validar (o passo que não se pula)**
- O período exibido bate com a fórmula **T = 2π√(L/g)**? Ex.: L=1 m, g=9,8 → T ≈ 2,0 s. Se a simulação mostrar outra coisa, a física está errada.
- Ao **aumentar o comprimento**, o período aumenta? (Deve.)
- Ao **aumentar a gravidade**, o período diminui? (Deve.)

> Se os três testes passam, a simulação está confiável. Se não, devolva o erro para a IA: "o período não corresponde a T=2π√(L/g), corrija a equação."

---

## D.2 — Variações (mesmo molde, validação própria)

Cada uma segue a lógica do D.1: peça a versão mínima + sliders com faixa física, depois **valide contra o que você sabe ser verdade**.

### 🌍 Órbita Terra–Lua
**Sliders:** distância, massa do corpo central, velocidade inicial.
**Como validar:** a órbita é estável (não espirala para dentro nem escapa) com valores realistas? Períodos relativos fazem sentido? Cuidado: a IA frequentemente erra a escala — deixe claro que é um modelo didático, não em escala real.

### 🚀 Lançamento de foguete / projétil
**Sliders:** ângulo de lançamento, velocidade inicial, gravidade.
**Como validar:** o alcance máximo ocorre a 45° (sem resistência do ar)? A trajetória é uma parábola? Se a IA incluir arrasto, o pico se desloca — confirme se é intencional.

### 🧪 Reação química / cinética
**Sliders:** temperatura, concentração, presença de catalisador.
**Como validar:** aumentar temperatura/concentração acelera a reação (curva mais íngreme)? **Atenção redobrada:** aqui a IA erra com mais frequência, porque "animação de reação" é fácil de fingir e difícil de acertar quantitativamente. Use como ilustração qualitativa, não como dado.

### 🌗 Rotação e translação (Terra, Lua, estações)
**Sliders:** velocidade de rotação, inclinação do eixo.
**Como validar:** a inclinação do eixo produz as estações de forma coerente? Dia/noite acompanham a rotação?

---

## D.3 — Quando a IA erra (e ela vai errar)

Fluxo de depuração para quem não programa:
1. **Não funciona / tela branca:** copie qualquer mensagem de erro e cole de volta na IA: "deu este erro, corrija."
2. **Funciona mas a física está errada:** diga exatamente qual lei foi violada ("o período deveria seguir T=2π√(L/g)").
3. **Slider sem efeito:** "o slider de [X] não altera a simulação; conecte-o ao cálculo."
4. **Trave a versão boa:** quando funcionar, **salve o código**. A próxima iteração pode quebrar o que já estava certo.

> 💡 **Uso pedagógico:** o erro da IA pode virar atividade. Peça aos alunos para *encontrar* o que está fisicamente errado numa simulação — vira exercício de pensamento crítico, exatamente o que o uso responsável de IA deveria desenvolver.

---
# APÊNDICE E — RECURSOS DA SUA CONTA INSTITUCIONAL GOOGLE
*Estes recursos fazem parte do Google Workspace for Education e estão disponíveis a qualquer escola com a licença adequada — não são exclusivos de nenhuma instituição.*

> **Pré-requisito comum:** todos os recursos abaixo dependem de estar logado na **conta institucional Google da sua escola** (`@suaescola.edu` ou equivalente), com o Gemini integrado. Isso garante a proteção de dados de nível institucional (dados não usados para treinar modelos fora do domínio) — mas depende de o administrador da conta ter os recursos habilitados sob esses termos. Mesmo assim, a **Régua de Segurança (Seção 1) continua valendo** — proteção de dados não dispensa anonimização.

---

## E.1 — Gems: tutores personalizados por disciplina

Um **Gem** é uma versão customizada do Gemini que você configura uma vez para se comportar como monitor da sua matéria. O Classroom já traz **modelos prontos** de Gem para começar — entre eles "Parceiro de estudos", "Me avalie (quiz)", "Parceiro de brainstorm" e "Conector com o mundo real".

**Quando vale a pena**
Quando você responde sempre as mesmas dúvidas e quer um monitor disponível 24h que conheça a ementa da sua disciplina.

**Como configurar (uma vez)**
1. Acesse a criação de Gem na conta institucional.
2. Defina o papel: "tutor da disciplina X, nível `[da sua turma]`".
3. Anexe os materiais de referência (ementa, roteiros, suas notas).
4. Defina a regra pedagógica: estimular o raciocínio em vez de entregar a resposta.
5. Teste com dúvidas reais antes de liberar para a turma.

> ⚠️ **Limite honesto (importante divulgar à turma):** um Gem orientado a "não dar a resposta pronta" **reduz**, mas não impede, que o aluno extraia a solução reformulando a pergunta. Não o apresente como barreira infalível — apresente como um monitor que ajuda a pensar.
> 🔞 **Idade:** os recursos de IA do Classroom voltados ao **aluno** exigem 18+. Em turmas com alunos menores de idade, use o Gem como ferramenta sua, não como recurso entregue diretamente a eles. Verifique a política antes.

**Aviso sugerido para o mural do Classroom**
> 🤖 *Tutor de IA da disciplina* — configurei um assistente para tirar dúvidas sobre os conteúdos da matéria. Ele foi ajustado para te **ajudar a pensar e encontrar seus erros**, como um monitor faria — não para entregar respostas prontas. Use para destravar, não para pular o raciocínio.

---

## E.2 — NotebookLM: caderno de estudos a partir dos seus materiais

O NotebookLM responde **com base apenas nos arquivos que você enviar** (slides, apostilas, ementas), o que o torna ótimo para um ambiente de estudo focado no conteúdo da disciplina. É um Core Service sob os termos do Workspace for Education (uploads e respostas não usados para treinar modelos).

**Quando vale a pena**
Para gerar resumos, guias de estudo e até áudio (*Audio Overview*) a partir do **seu** material — sem o aluno se perder em fontes aleatórias da internet.

**Como usar**
1. Crie um notebook e envie os materiais oficiais da disciplina.
2. Gere resumos, perguntas de revisão ou o Audio Overview.
3. Compartilhe o link com a turma como material complementar.

> ⚠️ **Correção de uma ideia comum:** o NotebookLM **não é "livre de erros"**. Ancorar nas suas fontes **reduz** a invenção de informação, mas o modelo ainda pode interpretar mal ou misturar trechos. A conferência continua sendo sua.
> 🔒 Envie materiais didáticos, **não** documentos com dados de alunos.

---

> 📌 **Como adaptar este guia à sua escola:** este material é genérico de propósito. Para deixá-lo institucional, basta acrescentar um apêndice com a realidade da sua escola — o nome do sistema acadêmico que vocês usam, eventuais normas internas sobre IA, e as plataformas adotadas. O núcleo (Seções 0–5) e os apêndices A–D funcionam em qualquer instituição que use o Google Workspace for Education.

---

*Material com suporte assistivo de IA para estruturação, integralmente revisado, validado e chancelado sob responsabilidade técnica e pedagógica do professor titular.*
