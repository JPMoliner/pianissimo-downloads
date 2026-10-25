# Créditos e licenças

## Salamander Grand Piano (`packs-v1/salamander-pro.zip`)

- Salamander Grand Piano V3 — **Alexander Holm**, licença
  [Creative Commons Attribution 3.0](https://creativecommons.org/licenses/by/3.0/)
  (texto em `LICENSES/CC-BY-3.0.txt`).
- Versão SFZ+FLAC montada pelo projeto **FreePats** (freepats.zenvoid.org).
- Alterações do Pianissimo: amostras convertidas para OGG Vorbis (q8), cortadas em 8 s, e um
  `soundpack.toml` (16 camadas de velocidade, release, ressonância de corda e ruídos de pedal).

## Steinway B (`packs-v1/steinway-b.zip`)

- Grand Piano, Steinway B — **Versilian Community Sample Library (VCSL)**, Versilian Studios
  LLC, [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (domínio público; texto em
  `LICENSES/CC0-1.0.txt`).

## Juiz de acordes ByteDance (`models-v1/bytedance-onset-fp16.onnx`)

- Modelo de transcrição de piano de alta resolução de **Qiuqiang Kong et al. (ByteDance)**,
  pesos em [zenodo.org/records/4034264](https://zenodo.org/records/4034264), convertidos para
  ONNX fp16 e reduzidos à saída de ataques (`reg_onset`).
- Treinado no conjunto **MAESTRO** (Google Magenta), licença
  [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) (texto em
  `LICENSES/CC-BY-NC-SA-4.0.txt`).
- **Aviso: uso não comercial.** Este arquivo não pode ser usado nem redistribuído com fins
  comerciais. Uma redistribuição precisa manter esta mesma licença.

## Pacote OMR (`omr-v1.0.0/omr-*.zip`)

Os dois motores rodam como processos separados do app Pianissimo. Cada zip traz, em `licenses/`,
os textos completos e um `SOURCES.txt` com o link para o código-fonte exato.

- **Audiveris 5.11.0** — [GNU AGPL-3.0](LICENSES/Audiveris-AGPL-3.0.txt). Código-fonte desta
  versão: <https://github.com/Audiveris/audiveris/tree/5.11.0>
  (commit `9e1e55cd2746037d059345881c53e6a6754bffbd`).
- **homr 0.7.0** (código e pesos) — [GNU AGPL-3.0](LICENSES/homr-LICENSE.txt). Código-fonte
  desta versão: <https://github.com/liebharc/homr/tree/v0.7.0>
  (commit `8b5dcf7d7bdd1a47911dc0c661c573b957271eab`). O projeto avisa que os dados de treino
  (por exemplo Camera-PrIMuS, CC BY-NC) podem restringir o uso comercial
  ([LICENSE_FAQ](https://github.com/liebharc/homr/blob/main/LICENSE_FAQ.md)).
- **Temurin JDK** (runtime reduzido com jlink) — GPL-2.0 com Classpath Exception.
- **Tesseract `eng.traineddata`** — Apache-2.0.
- Dependências Python do homr (numpy, onnxruntime, OpenCV…) — ver `licenses/python/INDEX.txt`
  dentro do zip.
