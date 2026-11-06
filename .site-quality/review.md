# Revisão — Comfy ErgoMax

Navegador real (Chromium, 1440x900 e 390x844). Capturas em `.site-quality/evidence/`.

- `d-hero.png`, `m-hero.png`: cadeira grande (foto real do cliente), título legível, botão dentro da primeira tela. No celular o menu quebrava e o título vazava: corrigido.
- `d-s1.png` a `d-s4.png`, `m-s1.png`: rolagem com zoom da câmera nas partes (tela mesh, alumínio, braços, lombar). Movimento confirmado: a posição e o zoom mudam com a rolagem e voltam ao rolar para cima.
- `d-dark.png`, `m-dark.png`: faixa azul com a imagem da coluna; antes ela cortava o texto da imagem, corrigido.
- `d-adj.png`, `m-adj.png`: regulagens. Antes a foto aparecia gigante (atributo height); corrigido.
- `d-spec.png`, `d-close.png`: ficha e fechamento.

Sem rolagem lateral nos dois tamanhos. Sem erros no console.
Não feito: cena 3D em WebGL (não há modelo 3D da cadeira; mantive a foto real) e deploy na Netlify (falta autorizar a conta).
Pendente do cliente: número de WhatsApp (botão flutuante só aparece quando o número entra em `config/site.json`).
