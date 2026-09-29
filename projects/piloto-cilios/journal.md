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
