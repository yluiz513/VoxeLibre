# RustCraft

**RustCraft** é um sandbox voxel para explorar, construir e sobreviver, com Android como plataforma prioritária.

Este repositório é uma cópia de desenvolvimento baseada no projeto [VoxeLibre](https://github.com/VoxeLibre/VoxeLibre), executado sobre o motor [Luanti](https://www.luanti.org/). O objetivo é preservar a experiência sandbox da base, desenvolver uma identidade visual própria e, gradualmente, adicionar modos originais.

## Estado do projeto

**Versão:** 0.1.0-alpha  
**Estado:** início da personalização. Ainda não é uma versão final nem uma build Android validada.

Veja [RUSTCRAFT_ROADMAP.md](RUSTCRAFT_ROADMAP.md) para o plano das versões Alpha.

## Créditos e licenças

Este projeto deriva de VoxeLibre e inclui contribuições de seus autores e colaboradores. Os créditos originais estão em [CREDITS.md](CREDITS.md). O README original foi preservado em [VOXELIBRE_UPSTREAM_README.md](VOXELIBRE_UPSTREAM_README.md).

O código de VoxeLibre é licenciado sob GPL-3.0-or-later, salvo componentes com licenças próprias. Texturas, sons e outros arquivos de mídia podem ter licenças diferentes; consulte [LEGAL.md](LEGAL.md), os arquivos de licença e os avisos presentes em cada mod antes de redistribuir.

As modificações específicas do RustCraft serão identificadas neste repositório. A distribuição deverá cumprir a GPL e as licenças individuais dos recursos incluídos, incluindo disponibilizar o código-fonte correspondente quando exigido.

## Desenvolvimento

A branch `master` mantém a cópia-base. O desenvolvimento do RustCraft acontece em branches próprias, começando por `rustcraft/0.1-alpha-foundation`.

Antes de declarar uma versão pronta, é necessário testar o jogo no Luanti e em um dispositivo Android real.


## Android build

The `RustCraft Android APK` GitHub Actions workflow builds a debug ARM64 APK with this game bundled into the Luanti Android engine. Open the repository's Actions tab to inspect the build and download the `RustCraft-0.1.0-alpha-Android-arm64` artifact after a successful run.
