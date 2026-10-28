# Prompts de imagem (Google Nano Banana)

Gere cada imagem, exporte em **WebP** (ou PNG/JPG, mas aí ajuste a extensão em `index.html`) e salve no caminho indicado. O deck usa a imagem automaticamente quando o arquivo existe e mostra o placeholder tracejado enquanto não existe.

**Estilo base (vale para todas; cole no começo de cada prompt):**
> Ilustração em aquarela e guache sobre papel envelhecido cor creme, estilo livro ilustrado (storybook), traço editorial quente. Paleta: azul azulejo (#24479a), verde folha (#3b7d3c), laranja (#e2702a), amarelo (#efa51f), roxo (#6b4a94), sobre fundo creme (#f4e6c8). Detalhes de azulejo português e estampa de chita nas bordas. Sem texto, sem letras, sem logotipos. Inspiração no Nordeste brasileiro (Maranhão), mas não um lugar real e identificável.

Cuidados (princípios do jogo): ninguém retratado como "doente", "perigoso" ou triste por causa de IST; nada sexualizado; adolescentes com aparência de 15–18 anos, vestidos de forma comum; diversidade de tons de pele, típica do Maranhão.

---

## IMG-01 · Jovens maranhenses (slide "O problema")
- **Arquivo:** `assets/gen/img-01-jovens.webp`
- **Formato:** vertical, **620 × 760** (proporção ~4:5)
- **Prompt:**
> [estilo base] Grupo de quatro adolescentes brasileiros do ensino médio, diversos (pretos, pardos, indígena, branco), conversando de forma descontraída numa praça de cidade nordestina no fim da tarde, mochilas nas costas, celulares na mão, casario colorido e palmeiras ao fundo. Expressões naturais e pensativas, nem alegres demais nem tristes. Composição vertical com espaço de papel creme vazio no topo. Luz quente, pinceladas visíveis.

## IMG-02 · A palestra que não engaja (slide "O que já existe")
- **Arquivo:** `assets/gen/img-02-palestra.webp`
- **Formato:** quase quadrado, **520 × 560**
- **Prompt:**
> [estilo base] Auditório de escola pública brasileira visto do fundo da sala: uma pessoa palestrando ao longe na frente de um projetor com slide genérico (sem texto legível), e adolescentes nas cadeiras dispersos — um olhando o celular, outro bocejando, dois cochichando. Tom levemente bem-humorado, sem caricatura ofensiva. Paleta dessaturada com acentos de azul e amarelo.

---

### Opcionais (se quiser enriquecer)

**IMG-03 · Médico do consultório** (para trocar o ícone de escudo no slide "Segurança", 420 × 420, salvar como `assets/gen/img-03-medico.webp` e me pedir para encaixar)
> [estilo base] Retrato meio corpo de um(a) médico(a) de unidade básica de saúde (UBS) brasileira, jaleco branco com estetoscópio, sorriso acolhedor, cerca de 40 anos, pele parda, segurando uma prancheta. Fundo de azulejos azuis desfocado. Expressão de quem escuta sem julgar.

**Fotos da equipe:** use **fotos reais** (não geradas por IA). Salve em `assets/team/` e preencha `EQUIPE` no topo do script do `index.html`.
