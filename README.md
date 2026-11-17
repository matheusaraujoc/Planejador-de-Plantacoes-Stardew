# 🌾 Planejador de Plantação

Ferramenta web simples para planejar plantações no estilo de Stardew Valley: onde colocar aspersores e espantalhos, quais tiles ficam regados e quais estão protegidos dos corvos.

## Funcionalidades

- Grade de tiles com solo arado, aspersores (comum, qualidade, irídio) e espantalhos (comum e deluxe)
- Prévia da área de atuação ao passar o mouse, antes de colocar o item
- Destaque colorido das áreas regadas (azul) e protegidas (amarelo)
- Opção de bocal de pressão (+1 de alcance nos aspersores)
- Contagem de tiles plantáveis, regados, secos e sem espantalho
- Zoom, modo mover e layout responsivo (funciona no celular)
- Presets salvos no navegador (localStorage) e salvamento automático

## Regras usadas

| Item | Área |
|---|---|
| Aspersor | 4 tiles (cima, baixo, esquerda, direita) |
| Aspersor de Qualidade | 3×3 (8 tiles) |
| Aspersor de Irídio | 5×5 (24 tiles) |
| Bocal de pressão | +1 anel no alcance |
| Espantalho | distância < 9 (raio 8, 248 tiles) |
| Espantalho Deluxe | distância < 17 (raio 16) |

## Como usar

Abra `index.html` no navegador, ou acesse a versão publicada no GitHub Pages.

### Imagens próprias (opcional)

Crie uma pasta `img/` com PNGs chamados `basic.png`, `quality.png`, `iridium.png`, `scare.png`, `deluxe.png`, `soil.png` ou `erase.png` para substituir os sprites padrão.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie esta pasta.
2. No repositório, vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
4. Após alguns minutos o site estará em `https://<seu-usuario>.github.io/<repositorio>/`.

---

Projeto de fã, sem fins comerciais e sem vínculo com a ConcernedApe. Stardew Valley é marca de seus respectivos donos. Os sprites deste projeto são desenhos originais.
