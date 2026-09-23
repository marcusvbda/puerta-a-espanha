# Plano de revisão de conteúdo — Puerta a España

> Status: **apenas planejamento. Nenhuma alteração no `index.html` foi feita ainda.**
> Arquivo alvo: `index.html` (arquivo único: HTML + CSS + JS com os dados `REGIONS`, `VISAS`, `Q`, `COSTS`).
> O site continua **em inglês simples** (projeto de escola de inglês). Os textos propostos abaixo são rascunhos em inglês; os números marcados com `[verificar]` só entram depois da Fase 0.

---

## Objetivo

Mudar o foco do site de "brasileiros" para **todos os imigrantes não europeus** que querem viver na Espanha, e deixar claro que:

- existem vários caminhos legais para qualquer não europeu (nômade digital, estudante, trabalho, empreendedor, família, arraigo);
- a cidadania em **2 anos** vale para **nacionais de países ibero-americanos** (não só o Brasil), além de Andorra, Filipinas, Guiné Equatorial, Portugal e sefarditas. Para a maioria dos outros não europeus a regra é **10 anos** (ou 1 ano em casos como casamento com espanhol);
- todos os números (renda, custos, salários, clima) vêm de **fontes oficiais**, com a fonte citada no rodapé.

---

## Pontos de atenção (decisões a confirmar antes de executar)

1. **"immediately AFTER your application"**: na anotação está "AFTER", mas o art. 22.3 do Código Civil diz *"residencia legal, continuada e inmediatamente **anterior** a la petición"*, ou seja, **antes** do pedido. O texto atual do site ("before") está correto. Plano: manter "before" e explicar melhor ("the 2 (or 10) years right before the day you apply"). Vou reconfirmar no BOE na Fase 0.
2. **Entrar como turista e pedir o visto dentro da Espanha**: isso é possível **só para alguns tipos de autorização**, e o tempo como turista **não conta** para a cidadania. Vai virar um bloco explicativo na linha do tempo (detalhes na Fase 6).
3. **Dupla nacionalidade**: hoje o site diz "you can keep your Brazilian nationality". Para os ibero-americanos, Andorra, Filipinas, Guiné Equatorial, Portugal e sefarditas isso vale. **Os outros não europeus precisam renunciar** à nacionalidade anterior no juramento (art. 23 CC). Como o site vai falar com todos os não europeus, isso precisa ser corrigido. Não estava nas anotações, mas é consequência direta da mudança de público.
4. **"Find your perfect region — Click on a region…"**: a anotação lista esse trecho em "Corrections in", mas não diz qual é a correção. Plano padrão: usar o texto como está na anotação ("Click **on** a region…") e revisar com fontes oficiais os dados das regiões (custos, salários, clima). Se a correção esperada era outra, preciso que você me diga.
5. **Hero "Why Spain is the best choice?"**: vou colocar essa pergunta no hero, no lugar do texto sobre os brasileiros (proposta na Fase 2). Recomendo manter o h1 atual e usar a pergunta como subtítulo/lead.

---

## Fase 0 — Pesquisa em fontes oficiais (antes de editar)

Checar cada dado e anotar valor + link. Prioridade: BOE, ministérios, INE, AEMET, Instituto Cervantes.

| # | Dado | Valor atual no site | Fonte oficial para checar |
|---|------|---------------------|---------------------------|
| 1 | Art. 22 CC: 10 / 2 / 1 anos, lista de países e o "inmediatamente anterior" | 10 / 2 / 1 | BOE — Código Civil art. 22 |
| 2 | Quais países contam como "ibero-americanos" (lista explícita) | "Brazil and other Ibero-American countries" | Ministerio de Justicia — Nacionalidad por residencia |
| 3 | Isenções de DELE A2 e CCSE (países de língua espanhola, menores, quem cursou ESO na Espanha etc.) | "Only nationals of Spanish-speaking countries are exempt from DELE" | Ministerio de Justicia + Instituto Cervantes (examenes.cervantes.es) |
| 4 | Dupla nacionalidade / renúncia (art. 23 e 24 CC) | "keep your Brazilian nationality" | BOE — Código Civil art. 23 |
| 5 | SMI 2026 (valor e decreto) | €1,221 × 14 (RD 126/2026) | BOE / La Moncloa. **O link atual do rodapé aponta para uma nota de 2023; corrigir** |
| 6 | Nômade digital: 200% SMI = ~€2,849/mês; +75% / +25% por familiar | €2,849/mês, €34,188/ano | Ley 14/2013 art. 74 bis + UGE (inclusion.gob.es) |
| 7 | IPREM 2026 | €600/mês | BOE (Lei de Orçamentos / prorrogação) |
| 8 | Visto não lucrativo: 400% IPREM + 100% por familiar | €2,400/mês | RD 1155/2024 (novo Regulamento de Estrangeiros) |
| 9 | Estudante: meios mínimos (100% IPREM? % por familiar) e limite de 30 h/semana | "Enough money (based on IPREM)" | RD 1155/2024 + exteriores.gob.es |
| 10 | Blue Card UE / Profissional Altamente Qualificado: diploma ou experiência exigida, salário mínimo, duração mínima do contrato | "high salary" | Ley 14/2013 (reformada pela Ley 11/2023) + UGE |
| 11 | Empreendedor: meios econômicos mínimos para o titular e familiares, relatório da ENISA | "Enough money" | Ley 14/2013 + guia da UGE para empreendedores + ENISA |
| 12 | Quais autorizações podem ser pedidas **de dentro da Espanha** em estadia legal (turista) | não existe no site | RD 1155/2024 + Ley 14/2013 (UGE) |
| 13 | Países latino-americanos isentos de visto Schengen para estadias curtas (90/180) + EES/ETIAS | não existe no site | exteriores.gob.es / Regulamento UE 2018/1806 |
| 14 | Empadronamiento: obrigatório para todos os residentes | "register your address" | Ley 7/1985 (Bases de Régimen Local) art. 15 / INE padrón |
| 15 | A partir de quando o tempo conta (data de concessão da primeira autorização) | "Your clock starts now" | Ministerio de Justicia / jurisprudência |
| 16 | Arraigo: 2 anos no novo regulamento, tipos | "Usually 2 years" | RD 1155/2024 |
| 17 | Salário médio bruto anual por região | ranges por região | **INE — Encuesta de Estructura Salarial** (usar a mais recente publicada: 2024 se já saiu, senão 2023) |
| 18 | Aluguel por região | ranges | Idealista é portal privado → complementar com **INE IPVA** ou **MIVAU — Sistema Estatal de Referencia del Precio del Alquiler**; manter Idealista como fonte "de mercado" |
| 19 | Temperatura média verão/inverno por região | ranges | **AEMET — valores climatológicos normales 1991–2020** (capital de cada região) |
| 20 | "300+ sunny days on the Costa del Sol" | 300+ | AEMET (horas de sol de Málaga). Se não tiver dado oficial de "dias de sol", trocar por "~2,900+ hours of sunshine a year in Málaga (AEMET)" |
| 21 | Orçamento mensal (single/couple) e gráfico de custos | ranges + gráfico | Recalcular: aluguel (fonte 18) + gastos básicos (INE — Encuesta de Presupuestos Familiares). Marcar como estimativa |

Saída da fase: tabela com o valor confirmado e o link de cada item. Se algum dado mudou, o texto das fases seguintes usa o valor novo.

---

## Fase 1 — Público: de "brasileiros" para "imigrantes não europeus"

Todas as ocorrências atuais de "Brazil/Brazilian" e o que muda:

| Onde (linha aprox.) | Hoje | Mudança |
|---|---|---|
| `<meta description>` (L7) | "helps Brazilians and Latin Americans" | "helps non-EU immigrants find their way to live in Spain" |
| Badge do hero (L287) | "🇧🇷 → 🇪🇸 For Brazilians & Latin Americans" | "🌍 → 🇪🇸 For non-EU immigrants" |
| Lead do hero (L289) | "Brazilians can apply… after only 2 years" | Substituir pelo texto "Why Spain is the best choice?" (Fase 2) |
| Stat 1 (L295) | "(Brazilians)" | "for Ibero-American nationals (10 for most others)" |
| Why Spain sub (L308) | "For Brazilians, Spain is one of the fastest routes" | "For Ibero-American nationals, Spain is one of the fastest routes in the EU, and every non-EU citizen has several legal ways in." |
| Card "Fast citizenship" (L310) | "including Brazil" | Citar exemplos de vários países: "Mexico, Colombia, Argentina, Brazil, Peru…" |
| Card "EU passport" (L311) | "keep your Brazilian nationality" | "Ibero-American nationals can keep their original nationality; others may need to give it up (check your case)." |
| Card "Culture & language" (L315) | só brasileiros | Ver Fase 2 |
| Galicia / Vigo (L575) | "For Brazilians who speak Portuguese" | "For Portuguese speakers (from Brazil, Angola, Mozambique, Cape Verde…)" + nota nova (Fase 4) |
| Timeline passo 3 (L406) | "Brazilians must pass…" | Ver Fase 6 |
| Timeline passo 5 (L408) | "keep your Brazilian nationality" | Mesma regra de dupla nacionalidade |
| FAQ (L467–469) | 3 perguntas só sobre brasileiros | Ver Fase 7 |
| Depoimentos (L454–456) | 3 perfis com cara de brasileiros | Diversificar (Fase 7) |

Critério de aceite: `grep -i brazil index.html` só retorna ocorrências em que o Brasil aparece **como um exemplo entre vários**.

---

## Fase 2 — Hero e "Why Spain"

### Hero (L287–299)
- Manter h1 "Your European dream starts in Spain".
- Novo lead, respondendo "Why is Spain the best choice?" (rascunho):
  > **Why is Spain the best choice?** It offers many legal ways to move, as a remote worker, student, professional, founder or family member, and one of the fastest roads to an EU passport: only **2 years** of legal residence for Ibero-American nationals. We help you choose the right visa, the right city and the right plan.
- **Stat do €2,849** (L297), para deixar claro que é **um requisito**, não um salário:
  - Número: `€2,849`
  - Label: "**minimum monthly income** — one of the requirements for the Digital Nomad Visa (2026)"
  - O card vira link para a aba do Digital Nomad (`#visas` + abre a aba `nomad`).
- Stat "27 EU countries": revisar a frase ("live and work in all 27 EU countries") depois da checagem.

### Card "Culture & language" (L315), rascunho
> Spanish is the official language of most of Latin America, so many Ibero-American immigrants arrive already speaking it (and don't need the DELE exam). Portuguese speakers, like Brazilians, learn Spanish fast because the languages are very close. Latin culture, family values and a warm welcome.

---

## Fase 3 — Vistos (`VISAS`, L616–645)

### Digital Nomad
- Destacar €2,849 como **requisito mínimo de renda**: primeira linha em negrito, com um pequeno badge "Key requirement".
- Recalcular os valores de família (+75% / +25% do SMI) com o SMI confirmado na Fase 0.

### Student: estimativa mínima mensal
Trocar "Enough money to live (based on IPREM)" por duas linhas:
- **Legal minimum:** 100% IPREM = **~€600/month** (€7,200/year) `[verificar]`, com o percentual para familiares `[verificar]`, a menos que a moradia já esteja paga.
- **Realistic budget:** **~€900–1,400/month**, dependendo da cidade (quarto compartilhado + comida + transporte), com base nos dados de aluguel da Fase 0. Salamanca/Valladolid na faixa baixa, Madrid/Barcelona na alta.

### Work / Blue Card: explicar melhor
Separar em 3 sub-rotas, em inglês simples:
- **General work visa:** contrato com empresa espanhola; em geral a vaga precisa estar na lista de ocupações de difícil cobertura ou passar pela checagem do mercado de trabalho `[verificar]`.
- **Highly Qualified Professional (Ley 14/2013):** cargos de gestão ou profissionais com diploma universitário (ou experiência equivalente); a empresa pede pela UGE; processo rápido (~20 dias) `[verificar salário de referência]`.
- **EU Blue Card:** diploma universitário **ou** X anos de experiência profissional relevante `[verificar: 5 anos; 3 para TI]`, contrato de pelo menos X meses `[verificar]` e salário de pelo menos **~€X/ano** `[verificar: 1,5× o salário médio; 1,2× para profissões em falta]`. Permite se mudar para outros países da UE depois de um tempo.
- Frase-resumo: "High salary" = explicar como "at least about €X per year (gross), much higher than the Spanish average of ~€Y".

### Entrepreneur: meios mínimos
Trocar "Enough money for you and the project" por:
- **Personal funds (estimate):** ~200% IPREM = **~€1,200/month (~€14,400/year)** para o titular + ~75% IPREM (**~€450/month**) por familiar `[verificar no guia da UGE]`.
- **Project funds:** não há valor mínimo fixo em lei; tem que bater com o business plan aprovado pela ENISA.
- Explicar o que é a ENISA em uma linha ("a public company under the Ministry of Industry that evaluates if your business is innovative").

### Outros
- NLV, Family e Arraigo: só checar números/regras (Fase 0) e trocar o que tiver mudado.
- Adicionar em cada visto um campo novo **"Apply from"**: *Consulate in your country* / *Inside Spain (if you are there legally)* / *Both*, com base no item 12 da Fase 0. Isso responde à dúvida sobre entrar como turista.

---

## Fase 4 — Mapa / regiões (`REGIONS`, L530–613)

- Sub da seção (L325): "Click **on** a region to see costs, salaries, weather, food, pros and cons. Use the filters to find the best match for you."
- Atualizar `rent`, `single`, `couple`, `gross`, `net`, `summer`, `winter` de cada região com os resultados da Fase 0 (INE / AEMET / MIVAU). Atualizar a nota `.approx` (L365) com as fontes e o ano.
- **Galicia / Vigo**, ponto sobre o galego: reescrever para Portuguese speakers em geral.
- **Nota do galego (L575)**, explicada melhor (rascunho):
  > **Good to know:** Galician is an official language only in Galicia, and it is very close to Portuguese, so Portuguese speakers understand a lot from day one (street signs, neighbours, local news). But the citizenship exam (DELE A2) is in **Spanish**, not Galician. So if Spanish is not your native language, you still need to study Spanish. Everyone in Galicia also speaks Spanish, so Spanish-speaking immigrants have no language problem here.
- Madrid "Big Latin community": manter (é verdade para toda a América Latina).
- Revisar o gráfico `COSTS` (L789) com os novos valores médios.

---

## Fase 5 — Quiz: mais perguntas, cobrindo todos os vistos do site

Hoje: 4 perguntas sim/não → só 4 resultados + um "Let's talk" genérico. Entrepreneur, Family e Arraigo nunca aparecem direito.

### Novo fluxo (8 perguntas, algumas condicionais)
| # | Pergunta | Tipo | Leva para |
|---|----------|------|-----------|
| 1 | Where is your passport from? — *A Spanish-speaking country in Latin America* / *Brazil (or another Ibero-American country where Spanish isn't official)* / *Another non-EU country* | múltipla escolha | Não define o visto; define os **anos para a cidadania (2 ou 10)** e se precisa do **DELE** no resultado |
| 2 | Is your partner (married or registered) a Spanish or EU citizen, or do you have close family living legally in Spain? | sim/não | `family` |
| 3 | Do you have a job offer from a company in Spain? | sim/não | `work` |
| 3b | *(só se 3 = sim)* Do you have a university degree (or several years of senior experience) and a salary of about €X+/year? | sim/não | `work` → Highly Qualified / Blue Card, ou general work visa |
| 4 | Do you work remotely for a company or clients outside Spain and earn at least €2,849/month? | sim/não | `nomad` |
| 5 | Do you want to study in Spain (degree, master's or course)? | sim/não | `student` |
| 6 | Do you want to start an innovative business or startup in Spain? | sim/não | `entre` |
| 7 | Do you have savings or passive income of about €2,400/month, without needing to work? | sim/não | `nlv` |
| 8 | Have you already lived in Spain for 2+ years without a residence permit? | sim/não | `arraigo` |

### Resultado
- **Main suggestion** pela prioridade: family → work (HQ/Blue Card) → nomad → work (general) → student → entrepreneur → NLV → arraigo → "Let's talk".
- **"Also possible for you"**: lista das outras rotas que também deram match (clicáveis → abrem a aba do visto).
- **Linha de cidadania** baseada na pergunta 1, por exemplo: "With your nationality, you can apply for Spanish citizenship after **2 years** of legal residence. You don't need the DELE, only the CCSE." / "…after **10 years**… you need DELE A2 and CCSE."
- O texto "Answer 4 quick questions" (L386) passa a usar o número real de perguntas, gerado pelo próprio script.
- Manter a UI atual (card, barra de progresso, botões); adicionar só o suporte a múltipla escolha e perguntas condicionais no `drawQuiz`.

---

## Fase 6 — Cidadania / linha do tempo (L392–420)

- **Sub (L396)**: "Spanish Civil Code, article 22. The years must be **legal, continuous and immediately before** your application: the 2 (or 10) years right before the day you apply." (ver ponto de atenção 1)
- **Card 2 anos (L399)**: listar os países explicitamente (lista do Ministerio de Justicia): "Nationals of Ibero-American countries (Argentina, Bolivia, Brazil, Chile, Colombia, Costa Rica, Cuba, Dominican Republic, Ecuador, El Salvador, Guatemala, Honduras, Mexico, Nicaragua, Panama, Paraguay, Peru, Uruguay, Venezuela…) `[verificar lista]`, plus Andorra, the Philippines, Equatorial Guinea, Portugal and people of Sephardic origin."
- **Card 10 anos**: "the general rule for most other non-EU nationals (e.g., Morocco, India, USA, China…)".
- **Novo bloco "Can I come as a tourist first?"** (antes do Month 0), rascunho:
  > Many Latin Americans don't need a visa for short visits (up to 90 days) `[verificar lista de países]`. Some permits **can** be requested from inside Spain while you are there legally as a visitor (for example, Digital Nomad, Highly Qualified, Entrepreneur and, since 2025, Student) `[verificar]`. Others **must** be requested at the Spanish consulate in your country (for example, Non-Lucrative and most work visas) `[verificar]`. Time as a tourist **never** counts for citizenship, and if you stay longer than 90 days without a permit, you become irregular.
- **Month 0**, explicar o que é obrigatório e para quem (rascunho):
  > **Get your residence permit and register your address.** *Empadronamiento* (registering at the town hall) is **mandatory for everyone who lives in Spain**, whatever the nationality or visa. You need it for healthcare, schools and renewals. For citizenship, your clock starts on the date your **first residence permit** is granted `[verificar]`, not the day you arrive.
- **Year 2 / Year 10**: os rótulos passam a ser "Year 2 (Ibero-American) · Year 10 (most others)".
- **Year 1–2, DELE + CCSE (L406)**, rascunho:
  > **Pass the CCSE and, if needed, the DELE A2.** Everyone takes the **CCSE** (a test on the Spanish Constitution and culture). If Spanish is **not** an official language in your country (for example Brazil, the Philippines, Morocco or India), you also need the **DELE A2** Spanish exam. Both are run by Instituto Cervantes. Exemptions: nationals of Spanish-speaking countries (no DELE), under-18s, and people who finished secondary school (ESO) in Spain `[verificar]`.
- **After approval (L408)**: aplicar a regra de dupla nacionalidade (ponto de atenção 3).
- **Caveats (L411–418)**: adicionar "Tourist time does not count, even if you later get a permit from inside Spain."

---

## Fase 7 — FAQ, depoimentos, rodapé, formulário

### FAQ (L467–472)
- "Do Brazilians really get citizenship after 2 years?" → "**Who can get citizenship after only 2 years?**" (lista de países + regra de 10 anos para os outros).
- "Do I need to take a Spanish exam?" → resposta nova com a regra CCSE para todos + DELE só se o espanhol não for língua oficial no seu país.
- "Will I lose my Brazilian nationality?" → "**Will I lose my current nationality?**", com resposta diferenciada (ibero-americanos e similares mantêm; outros podem ter que renunciar).
- Nova: "**Can I enter as a tourist and apply from Spain?**" (resumo do bloco da Fase 6).
- Nova: "**I'm not from Latin America. Can I still move to Spain?**" → sim, todos os vistos valem para qualquer não europeu; só a cidadania leva mais tempo.

### Depoimentos (L454–456), continuam marcados como fictícios
- Manter um brasileiro (ex.: nômade em Valencia).
- Trocar os outros por perfis diversos: uma família colombiana ou mexicana em Zaragoza (sem barreira de idioma, sem DELE) e um engenheiro indiano ou marroquino com Blue Card em Madrid (caminho de 10 anos).

### Rodapé (L509–520)
- Corrigir o link do SMI 2026 (hoje aponta para uma nota de 2023).
- Adicionar: RD 1155/2024 (Regulamento de Estrangeiros), Ley 14/2013 / UGE, ENISA, AEMET, INE IPVA ou MIVAU, Ministerio de Justicia (lista de países ibero-americanos).
- Cada número novo do site precisa ter uma fonte nessa lista.

### Formulário (L490–493)
- Adicionar "Entrepreneur Visa" e "Arraigo" no select (hoje esses dois vistos estão no site mas não aparecem no formulário).

---

## Fase 8 — Verificação

1. `grep -in "brazil" index.html` → conferir cada ocorrência restante (só como exemplo entre vários países).
2. Abrir o `index.html` no navegador e testar:
   - hero: textos novos + o card do €2,849 abrindo a aba do Digital Nomad;
   - todas as abas de visto (campo novo "Apply from");
   - mapa: abrir cada região clicável, pins de Valencia/Vigo, filtros, painel no mobile (≤ 900px);
   - quiz: um caminho que chegue em **cada um** dos 7 vistos + "Let's talk", e as 3 respostas de nacionalidade (2 vs 10 anos, DELE ou não);
   - timeline e FAQ.
3. Console do navegador sem erros.
4. Leitura final do texto: inglês simples (nível de escola de inglês), sem contradições entre hero, cards, timeline e FAQ (ex.: 2 vs 10 anos, DELE, dupla nacionalidade).

---

## Fora do escopo

- Mudanças de layout/design além do necessário (badge "Key requirement", campo "Apply from", bloco "tourist first", suporte a múltipla escolha no quiz).
- Tradução do site para outros idiomas.
- Tornar clicáveis as regiões que hoje não são (Asturias, Navarra etc.). Posso fazer se você quiser, mas isso exige coletar dados de mais regiões.
