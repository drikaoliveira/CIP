# Journal — Piloto Cílios & Sobrancelhas

Histórico append-only. **Nunca apague entradas** — se algo mudou, registre
uma nova entrada que corrige a anterior.

Formato:

```
## AAAA-MM-DD — [F|H|D|A|EXP|FEEDBACK] título curto
- Operando: <quem>
- O quê:
- Por quê / contexto:
- Próximo efeito: (o que isso muda nas próximas decisões)
```

Tipos extras:
- **EXP** — experimento: hipótese, ação, critério de sucesso, prazo; depois, resultado.
- **FEEDBACK** — aprovação/rejeição/edição humana e o que ela revela.

---

## 2026-09-29 — [D] Arquitetura mínima da CIP v2
- Operando: sócias + CIP Strategist
- O quê: CIP reconstruída como agente único (CIP Strategist) no Claude
  Code, com memória em arquivos Markdown versionados em git. Sem banco,
  MCPs, Skills ou subagentes customizados por enquanto. n8n e Supabase da
  v1 congelados.
- Por quê: a v1 (n8n + Supabase) gastava energia demais em infraestrutura.
  Queremos provar primeiro que um agente consegue conduzir um projeto real
  até a primeira venda e melhorar com o uso.
- Próximo efeito: novas ferramentas só entram quando o piloto revelar uma
  necessidade concreta.

## 2026-09-29 — [F] Contexto inicial do piloto
- Operando: sócias
- O quê: projeto em coprodução; sócias operam e fazem repasses para a
  expert; depoimentos e perfil no Instagram; cursos hospedados na Hotmart.
- Próximo efeito: onboarding deve cobrir os termos da coprodução e o fluxo
  de aprovação com a expert.

## 2026-09-29 — [F] Onboarding: modelo de negócio, produtos e canais
- Operando: sócias + CIP Strategist
- O quê: receita 50/50 expert/coprodução, tráfego pago dividido 50/50;
  repasses à expert são financeiros e de informação/aprovação. Dois cursos
  na Hotmart (Alongamento de Cílios; Avançado Volume 3 em 1), vendas não
  iniciadas. Instagram do Studio (~10k) como canal principal; pessoal
  (~14k) com collabs pontuais. Depoimentos em vídeo de alunas presenciais
  no Studio. Expert disponível algumas tardes para gravar.
- Próximo efeito: brain.md reescrito com esses fatos.

## 2026-09-29 — [H] Possível descompasso entre audiência do Studio e público dos cursos
- Operando: CIP Strategist
- O quê: seguidores de um Studio tendem a ser clientes finais, não
  profissionais que compram curso. Se confirmado, vender curso só pelo
  Studio pode ter baixa conversão.
- Como validar: insights do Instagram + enquete nos stories ("você
  trabalha ou quer trabalhar com cílios?") nos dois perfis.
- Próximo efeito: define canal principal e se o primeiro movimento deve
  mirar ex-alunas presenciais.

## 2026-09-29 — [F] Mercado de cursos de cílios na Hotmart
- Operando: CIP Strategist
- O quê: busca web encontrou muitos cursos concorrentes na Hotmart, alguns
  a partir de R$ 16,57 (fonte: busca web). Páginas da Hotmart e do
  Instagram não acessíveis do ambiente (bloqueio de rede).
- Próximo efeito: [H] diferenciação precisa vir da autoridade presencial e
  da prova real; conteúdo dos cursos deve ser colado em inputs/.

## 2026-09-29 — [F] Páginas Hotmart dos cursos lidas
- Operando: sócias + CIP Strategist
- O quê: acesso à Hotmart liberado. Curso 1 se chama publicamente
  "Formação Lash Essencial by Ana Flávia Batista" (5 módulos, ~27 aulas,
  clássico fio a fio + intro volume). Curso 2 "Avançado de Volume 3 em 1"
  (3 em 1, russo, híbrido, mega volume; 8h; certificado). Garantia 7 dias
  nos dois. Preço não visível. Conta produtora "Estetica e Cia Ead";
  avaliações de fev/2023 (1 e 2 avaliações). Instagram segue inacessível
  (HTTP 429 / exige login).
- Por quê importa: avaliações de 2023 indicam vendas passadas — pode haver
  histórico, compradoras e questões de titularidade a esclarecer.
- Próximo efeito: brain.md atualizado; perguntas abertas sobre preço e
  histórico da conta.

## 2026-09-29 — [F] Expert afirma que o Studio é seguido por profissionais e alunas
- Operando: sócias
- O quê: a escolha do Studio como canal principal foi sugestão da expert,
  que afirma que muitos profissionais e alunas o seguem.
- Próximo efeito: a [H] de descompasso de público perde força; mantemos a
  decisão e validamos a proporção com enquete antes de investir em tráfego.

## 2026-09-29 — [F] Preços, base de ex-alunas e plano de páginas
- Operando: sócias + CIP Strategist
- O quê: básico R$ 297; volumes R$ 347; combo futuro R$ 497 (russo +
  híbrido + mega volume + bônus volumes tecnológicos + ebook campeonato +
  módulo preço/administrativo). Presencial ~R$ 1.500. 500+ alunas formadas
  no presencial. Só a Ana está vinculada às contas Hotmart. Páginas Hotmart
  serão reestruturadas e página de vendas criada após fechar a promessa.
- Próximo efeito: [H] ex-alunas presenciais são o primeiro público de
  venda (sem tráfego); [H] módulo administrativo pode ser o ângulo central
  da promessa. Questionário da expert anexado ainda não lido (falha de
  ferramenta).

## 2026-09-29 — [A] Hipótese refutada: ex-alunas presenciais não compram os cursos
- Operando: sócias + CIP Strategist
- O quê: sócias informaram que o presencial (~R$ 1.500) já cobre o
  conteúdo dos 2 cursos digitais. A [H] "ex-alunas são o primeiro público
  de venda" foi descartada.
- Aprendizado de processo: o Strategist assumiu que o presencial era só o
  básico sem verificar o escopo. Antes de propor público, confirmar o que
  cada produto (inclusive o presencial) já entrega.
- Próximo efeito: ex-alunas passam a ser ativo de prova e distribuição
  (depoimentos, indicação/afiliação). Público comprador do digital a
  definir: [H] quem não pode pagar R$ 1.500 ou se deslocar.

## 2026-09-29 — [F] Questionário de extração do método lido
- Operando: sócias + CIP Strategist
- O quê: questionário respondido pela expert salvo em
  `inputs/questionario-extracao-metodo.md`. Principais fatos: aprendeu
  com curso online porque não podia pagar o presencial; 3º lugar em
  campeonato internacional; método progressivo em 4 etapas; posições
  contrárias (sem fita no isolamento, sem cola em anel); dores da
  iniciante ("não vou conseguir", quanto cobrar, captar clientes) e da
  profissional (fans, volume em menos de 1h30); caso Aline.
- Próximo efeito: brain.md ganhou personas A (iniciante) e B
  (profissional), método e direções de promessa como [H].

## 2026-09-29 — [H] Duas ofertas por persona e risco do "pegar na mão"
- Operando: CIP Strategist
- O quê: (1) o método progressivo da expert sugere ofertas separadas para
  iniciante e profissional, não um combo único; (2) o diferencial dela
  ("pegar na mão") não existe no curso gravado → o online provavelmente
  precisa de um canal leve de correção; (3) a história de ter aprendido
  online é a principal prova contra a objeção "dá para aprender online?".
- Próximo efeito: validar com a expert na próxima reunião; definir qual
  oferta vai primeiro por experimento de demanda no Instagram.

## 2026-09-29 — [EXP] Teste de demanda — semana 1 (proposto, aguardando aprovação)
- Operando: sócias + CIP Strategist
- Hipóteses: (1) há demanda no Studio para vender sem tráfego; (2) uma
  persona (iniciante × profissional) responde claramente mais; (3) a
  história "aprendi online" reduz a objeção ao online.
- Ação: 7 dias de stories (história → iniciante → profissional → lista de
  espera no WhatsApp com links COMEÇAR/EVOLUIR), enquetes e caixa de
  perguntas. Custo zero; uma tarde de gravação.
- Critério (provisório): inscrições ≥ 5% das views médias = sinal forte;
  < 2% = rever promessa/canal; vencedora com ≥ 1,5× a outra.
- [D proposta] Não revelar preço na semana 1.
- Entrega: `work/teste-demanda-semana-1.md`. Status: precisa aprovação da expert.
- Resultado: _pendente_.
