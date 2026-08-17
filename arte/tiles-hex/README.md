# Tiles hexagonais — onde salvar cada arquivo

Salve os PNG/JPG finais direto nessas pastas (pode sobrescrever o nome, não precisa ser exatamente
igual — só mantenha a extensão do arquivo). Quando terminar, me avisa aqui na conversa.

## Nomeação (não é obrigatório seguir à risca, mas ajuda)

Dentro de cada pasta, se tiver mais de uma variação (o roteiro pede 2-3 por categoria pra não
repetir visualmente), salve como `variacao-1.png`, `variacao-2.png`, `variacao-3.png` etc.
Se só tiver uma por enquanto, `variacao-1.png` já resolve — dá pra completar depois.

- `base/azul/` — cluster de **3 hexágonos numa imagem só** (cunha triangular: 1 hexágono de ponta
  + 2 vizinhos dele voltados pro centro do mapa), bandeirinha na cor azul do time.
- `base/carmim/` — mesma cena, bandeirinha carmim.
- `ponto-invocacao/` — roda de carro + cabos elétricos em círculo, brilho verde tênue no centro
  (a imagem da roda com fios que você já mandou serve perfeitamente aqui).
- `ponto-mana/` — rachadura com energia verde do cataclisma vazando (a imagem que você mandou
  serve aqui).
- `anel-habitado/` — vielas com roupa no varal, telhado de zinco remendado, azulejo quebrado —
  ainda "vivido", não abandonado.
- `ferragem-obstaculo/` — estrutura abandonada, vigas retorcidas, sem tecido/sinal de gente —
  essa é a casa BLOQUEADA (funciona como obstáculo no tabuleiro).
- `grama-sucata/` — mato alto tomando conta de peças mecânicas.
- `wasteland/` — terreno mais hostil/seco, centro do mapa.
- `transicoes/` — tiles de "remendo" pensados pra ficar sobre a costura entre dois hexágonos
  diferentes (entulho espalhado, rachadura de terra, tufo de grama, cascalho) — servem pra suavizar
  a quebra visual entre tiles vizinhos de tipos diferentes. Não precisa ser hexágono fechado, pode
  ser um elemento solto/irregular que eu recorto e posiciono por cima na hora de desenhar.

## Sobre os arquivos que você já mandou na conversa

Não consigo salvar sozinho as imagens que você colou no chat — preciso que você exporte/baixe e
solte nos caminhos acima. As que já pareciam prontas pelo que você descreveu:

- Ponto de invocação (roda + fios) → `ponto-invocacao/variacao-1.png`
- Ponto de mana (rachadura verde) → `ponto-mana/variacao-1.png`
- A fortaleza circular com o símbolo → serve de referência de estilo pra regenerar como cluster de
  3 hexágonos (ver nota acima em `base/`), não precisa salvar essa versão isolada.
- As demais (terreno com entulho/azulejo espalhado) → dá pra reaproveitar como `transicoes/` ou
  `anel-habitado/`, dependendo de qual close mais com a descrição de cada categoria acima.
