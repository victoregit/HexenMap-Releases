# Hexen Map

[Português](#português) · [English](#english) · [Download / Releases](https://github.com/victoregit/HexenMap-Releases/releases/latest)

## Português

**Seu companheiro de exploração no Genshin Impact.** Hexen Map mostra marcadores sobre o minimapa e o mapa do jogo, ajuda a acompanhar coletados, exibe fotos dos pontos e permite importar progresso do AppSample. Este repositório distribui os instaladores e as atualizações para Windows 10/11 de 64 bits.

### Como usar e por quê

1. Baixe o instalador `.exe` na [última release](https://github.com/victoregit/HexenMap-Releases/releases/latest), instale e procure **Hexen Map** no menu Iniciar.
2. Autorize o pedido de administrador. Ele vem antes do launcher porque o overlay precisa interagir com a janela do jogo quando ela está elevada.
3. O launcher verifica atualizações, instala uma versão nova quando disponível e abre o aplicativo automaticamente. Sem conexão, tenta abrir a versão instalada.
4. Escolha os itens no painel. Com o mapa aberto, **Ctrl + clique** em um marcador abre seu cartão com fotos e a opção de marcar/desmarcar a coleta.

O alinhamento usa captura de imagem e reconhecimento visual: o aplicativo não lê a memória do jogo, não injeta código e não controla o personagem. Isso permite desenhar uma camada externa sobre os mapas já exibidos pelo jogo.

### Seus dados

Coletas e preferências ficam **no seu PC**, na pasta `userData` da instalação; não há backup em nuvem. Atualizações e reinstalações na mesma pasta preservam arquivos existentes, e a desinstalação também mantém essa pasta. Faça seu próprio backup. Ao migrar de uma versão portátil, feche o overlay e copie a `userData` antiga para a nova instalação.

### Riscos e limites

- Projeto independente, sem afiliação com HoYoverse ou AppSample. Não prometemos risco zero ao usar uma ferramenta de terceiros nem garantia contra medidas do jogo/anticheat.
- O reconhecimento pode perder o alinhamento; cobertura, resolução e idioma influenciam o resultado. **AutoMark continua beta**, vem desligado e pode errar. Confira suas marcações.
- O programa executa com privilégios de administrador. Baixe apenas deste repositório. A build ainda não tem assinatura digital própria; avisos do Windows não devem ser ignorados automaticamente. O `.sha256` permite conferir a integridade do arquivo.
- Mapas, fotos e serviços externos podem mudar ou ficar indisponíveis. Seus conteúdos pertencem aos respectivos autores; a distribuição do aplicativo não transfere direitos sobre eles.

Encontrou um problema? Abra uma [issue](https://github.com/victoregit/HexenMap-Releases/issues) com a versão, resolução e passos para reproduzir. Não envie senhas, cookies, tokens ou arquivos pessoais de progresso.

## English

**Your exploration companion for Genshin Impact.** Hexen Map overlays markers on the minimap and in-game map, tracks collected items, displays location photos, and imports AppSample progress. This repository distributes installers and updates for 64-bit Windows 10/11.

### How to use it and why

1. Download the `.exe` installer from the [latest release](https://github.com/victoregit/HexenMap-Releases/releases/latest), install it, and find **Hexen Map** in the Start menu.
2. Approve the administrator prompt. It appears before the launcher because the overlay needs to interact with the game window when the game runs elevated.
3. The launcher checks for updates, installs a newer version when available, and opens the app automatically. If offline, it attempts to open the installed version.
4. Select items in the panel. With the map open, **Ctrl + click** a marker to see its photos and mark or unmark it as collected.

Alignment relies on screen capture and visual recognition. The app does not read game memory, inject code, or control your character. It draws an external layer over the maps already displayed by the game.

### Your data

Collected items and preferences stay **on your PC**, in the installation's `userData` folder; there is no cloud backup. Updates and reinstalls in the same folder preserve existing files, and uninstalling also retains that folder. Keep your own backup. When migrating from a portable build, close the overlay and copy your old `userData` into the new installation.

### Risks and limitations

- Independent project, not affiliated with HoYoverse or AppSample. We do not promise risk-free use of a third-party tool or protection against game/anti-cheat enforcement.
- Visual recognition can lose alignment; coverage, resolution, and language affect results. **AutoMark remains beta**, is disabled by default, and can make mistakes. Review your collected markers.
- The app runs with administrator privileges. Download only from this repository. The build does not yet have its own digital signature; do not automatically dismiss Windows warnings. The `.sha256` file lets you check download integrity.
- Maps, photos, and external services may change or become unavailable. Their content belongs to its respective owners; distributing the app does not transfer those rights.

Found a problem? Open an [issue](https://github.com/victoregit/HexenMap-Releases/issues) with your version, resolution, and reproduction steps. Do not share passwords, cookies, tokens, or personal progress files.
