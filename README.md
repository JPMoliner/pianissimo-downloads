# Pianissimo — downloads

Este repositório só hospeda os **pacotes opcionais** que o app Pianissimo baixa sob demanda
(pianos, o juiz de acordes do microfone e o pacote OMR). Não há código do app aqui.

O app confere cada arquivo pelo SHA-256 antes de instalar; os mesmos hashes estão abaixo e no
arquivo `.sha256` ao lado de cada asset.

## Releases

| Release | Arquivo | SHA-256 | Licença |
|---|---|---|---|
| `packs-v1` | `salamander-pro.zip` | `6d5e79249b651c8ef482bb39325ac9a6785ae31c77eef8db22acbfdce303ba0c` | CC-BY 3.0 |
| `packs-v1` | `steinway-b.zip` | `b5c28e5093b1af79675e90fd5c6af7b0442ff11442a9d48c2328c0163a210baa` | CC0 1.0 |
| `models-v1` | `bytedance-onset-fp16.onnx` | `843c201df19e108b7c12f84c4b010a3b711ea0248f362de58c1ef8f3d528e01e` | CC BY-NC-SA 4.0 (**não comercial**) |
| `omr-v1.0.0` | `omr-macos-arm64.zip` | `4ab57a608d97de0382745fe230bf9ffbee31deea3708108e4f6fc42ff68a484d` | AGPL-3.0 (Audiveris, homr) e outras |
| `omr-v1.0.0` | `omr-windows-x64.zip` | `9deb8268e4cea00e243f1dffde2d8d912ca17d13849b4b79d8030a8ac8794c05` | AGPL-3.0 (Audiveris, homr) e outras |

Créditos, licenças e links para o código-fonte: [NOTICE.md](NOTICE.md) e a pasta
[LICENSES/](LICENSES/).

## Instalar à mão

No app, cada card de pacote (Dispositivos & Áudio) e a janela do pacote OMR têm
**Importar arquivo…**: baixe o asset da release aqui e escolha o arquivo. O app confere o SHA-256.
