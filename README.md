# ALIC3 WORLD

Um jogo 3D low poly em terceira pessoa que roda direto no navegador.

Você acorda num planeta desbotado, ao lado da sua nave quebrada. Pelo chão brilham fragmentos de código. Recolha-os, acorde os quatro monólitos e aprenda as linguagens deste mundo: **Sinal, Sequência, Repetição e Escolha**. A cada linguagem aprendida, o mundo recupera suas cores e uma voz fica mais clara: **ALIC3**, a mente do planeta.

No fim, você decide: consertar a nave e partir, ou ficar e reescrever o mundo.

Os quebra-cabeças não exigem saber programar. Cada um apresenta, com situações do dia a dia, uma ideia básica da computação: código binário, algoritmos, laços de repetição e condicionais.

## Como jogar

Abra o `index.html` em qualquer navegador moderno. Não há nada para instalar.

O progresso e os ajustes ficam salvos no navegador.

## Controles

| Ação | Teclado e mouse | Controle (PS5 / gamepad) | Toque |
|---|---|---|---|
| Andar | WASD ou setas | Analógico esquerdo | Círculo na tela |
| Girar a câmera | Arrastar o mouse | Analógico direito | Arrastar a tela |
| Zoom | Rolagem do mouse | L2 afasta · R2 aproxima | — |
| Interagir | E | ✕ | Botão Usar |
| Avançar diálogo | E, espaço ou clique | ✕ ou ◯ | Tocar no diálogo |
| Navegar em menus | Tab e Enter, ou mouse | Direcional e ✕ | Tocar |
| Sortear nome | — | △ (na criação) | — |
| Pausar | Esc ou P | Options | Botão ‖ |

Para usar um controle, conecte-o ao computador por Bluetooth ou cabo e aperte ✕ com o jogo aberto. O navegador só reconhece o controle depois do primeiro botão pressionado.

## Menu de pausa

- **Objetivo:** a tarefa atual e o progresso de cada linguagem.
- **Controles:** com um controle conectado, mostra um mapa dos botões que acende ao vivo.
- **Ajustes:** sensibilidade da câmera, inversão de eixos, vibração e itens na tela.
- **Ajuda:** dicas rápidas.

## Tecnologia

- Um único arquivo `index.html`, com HTML, CSS e JavaScript puros.
- Gráficos 3D com [Three.js](https://threejs.org/) r128, carregado do cdnjs.
- Gamepad API do navegador para o controle, com vibração quando o navegador oferece suporte.
- Fontes Chakra Petch, Literata e IBM Plex Mono, do Google Fonts.

## Publicar no GitHub Pages

Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`. Depois de alguns minutos, o jogo fica disponível em `https://devtas.github.io/alic3-world/`.
