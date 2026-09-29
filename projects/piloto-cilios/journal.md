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
