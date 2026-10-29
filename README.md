# ANAGNOSIS

Estudo de grego e hebraico bíblicos voltado para a exegese, com diagnóstico de nível e revisão espaçada.

**Abrir o app:** https://eneas-ena.github.io/anagnosis/

## Como funciona

- App feito em página web; pode ser instalado na tela inicial do iPad, iPhone ou Mac.
- Os dados ficam salvos no Supabase, por isso aparecem iguais em todos os aparelhos.
- Os serviços externos, como a inteligência artificial, passam pelos Workers `atlas-profecias`, `promptflow-ia` e `tkl-api` no Cloudflare; as chaves secretas ficam guardadas lá, nunca neste código.

## Observações

- Usa os dados do InterTextus (repositório `interlinear`).

## Como publicar uma nova versão

1. Nesta página do repositório, clique em **Add file → Upload files**.
2. Arraste os arquivos novos, com os mesmos nomes dos antigos.
3. Clique em **Commit changes**.

Em um ou dois minutos a nova versão está no ar no mesmo endereço.

---
Desenvolvido por Bispo Enéas Araújo.
