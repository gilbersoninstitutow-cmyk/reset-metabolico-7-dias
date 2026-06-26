# ARCHITECTURE.md — reset-metabolico-7-dias

LP Reset Metabólico 7 Dias — Versão HTML Legada (v1).

> ⚠️ ATENÇÃO: Este repo contém a VERSÃO LEGADA (v1) da LP.
> A versão ATUAL em produção está em:
> `institutow-web` → `/reset-metabolico-7-dias/` (Next.js App Router)
> URL: lp.institutow.com/reset-metabolico-7-dias/

---

## Versões da LP

| Versão | Stack | Repo | Status | WhatsApp |
|--------|-------|------|--------|---------|
| v1 (legado) | HTML/CSS puro | reset-metabolico-7-dias (este repo) | ⚠️ LEGADO | número legado |
| v2 (atual) | Next.js 14 App Router | institutow-web | ✅ LIVE | 5521972393434 (⚠️ a corrigir) |
| v3 (ideal) | institutow-lps HTML | institutow-lps | ⏳ planejado | 5521998463434 (padrão) |

---

## Estrutura v1 (este repo)

```
reset-metabolico-7-dias/
├── index.html          ← LP completa (HTML/CSS inline)
├── assets/
│   └── ...             ← Imagens e recursos
├── docs/
│   ├── ADS.md          ← Estratégia de anúncios
│   ├── LANDING.md      ← Briefing da landing page
│   └── OFFER.md        ← Estrutura da oferta
└── README.md           ← Brief do produto
```

---

## Produto

**Reset Metabólico 7 Dias** é um produto low-ticket do ecossistema W Metabolic Performance 360°.

**Público:** pessoas cansadas, inchadas, inflamadas, sem energia.

**Proposta:** plano simples e prático para mudança perceptível em 7 dias.

**Entrega:** guia PDF via WhatsApp após preenchimento do formulário.

---

## Relacionamentos

- → `institutow-web` — contém a versão v2 em produção (Next.js)
- → `w-metabolic-performance-360` — repositório de estratégia do programa
- → `institutow-lps` — receberá a v3 (LP HTML padrão do ecossistema)
- → `COREX_INSTITUTO_W` — CRM que recebe os leads gerados

---

## Pendências

- [ ] Decidir se v1 (HTML) será substituída definitivamente pela v2 (Next.js)
- [ ] Corrigir número WhatsApp na v2 (5521972393434 → 5521998463434)
- [ ] Ativar indexação na v2 quando pronta para tráfego
- [ ] Criar v3 em institutow-lps (HTML padrão do ecossistema)
