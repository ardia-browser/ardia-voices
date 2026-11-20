# Ardia voices

Files the Ardia app downloads on demand, kept out of the app itself.

## Phonon 31M, English (`phonon-31m-en-v0.7.1`)

Talk to Me on iPhone reads Browse for Me answers aloud with this voice, on the phone.

- `phonon-31m-en.aar`: an Apple Archive (LZFSE) holding `TalkToMe/`: Phonon 31M's three Core ML models compiled to
  `.mlmodelc`, its tokenizer and host weights, `bundle.json`, and six voices (Harper, Juniper, Miles, Preston, Maeve, Hugh).
- SHA-256 `f72408f24f92dd92682819709aaca0d525d5f2fcea26243be90063e9d9df6579`, 132,936,282 bytes.
- Built by `apps/phone/ios/AssetPacks/talk-to-me-phonon-31m-en/build-pack` in ardia-browser/ardia from Gradium's
  `phonon-31m-en-coreml.zip` (xn-ptts v0.7.1), which it checks against its pinned SHA-256.

Phonon 31M is copyright Gradium, Apache-2.0: https://huggingface.co/gradium/phonon-31m-en. Its voices are from
https://huggingface.co/gradium/phonon-voices (Apache-2.0). The runtime is https://github.com/gradium-ai/xn-ptts.
Nothing here is modified beyond compiling the models.
