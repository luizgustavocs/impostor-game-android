# Impostor Game (Android)

Offline social deduction word game for groups, built with React Native and Expo. Players receive a secret word, except the impostor, and the group has to find the impostor before they discover the word.

**Download (Android beta):** [APK](https://expo.dev/artifacts/eas/tRBggDfp26t44Vu2Vfu5DF.apk)

> The APK is distributed outside the Play Store, so Android may show an "unknown source" warning before installing.

## Features

- **Blind mode:** optional setting that hides the hint from the impostor, raising the difficulty.
- **Curated word list:** more than 100 words chosen for ambiguity, to spark discussion.
- **Offline persistence:** settings and already used words stored locally to avoid repetition.
- **Animated interface:** custom drag-to-reveal interaction built with the Animated API and PanResponder.
- Interface in Portuguese.

## Tech stack

| Concern | Technology |
|---|---|
| Framework | React Native, Expo |
| Navigation | React Navigation |
| Persistence | AsyncStorage |
| Icons | lucide-react-native |
| Builds | Expo Application Services (EAS) |

## Getting started

```bash
git clone https://github.com/luizgustavocs/impostor-game-android.git
cd impostor-game-android
npm install
npx expo start
```

Scan the QR code with the **Expo Go** app (Android or iOS).

## Author

Luiz Gustavo Costa e Silva · [GitHub](https://github.com/luizgustavocs) · [LinkedIn](https://www.linkedin.com/in/luizgustavocs)

<details>
<summary>Versão em português</summary>

### Impostor Game (Android)

Jogo de dedução social em grupo, offline, feito com React Native e Expo. Todos recebem uma palavra secreta, menos o impostor, e o grupo precisa descobri-lo antes que ele adivinhe a palavra.

**Funcionalidades:** modo cego (sem dica para o impostor), lista com mais de 100 palavras ambíguas, persistência local com AsyncStorage para evitar repetições e interação de "arrastar para revelar" com Animated API e PanResponder.

**Como executar:** `npm install`, `npx expo start` e escanear o QR Code com o Expo Go. Também é possível instalar o [APK](https://expo.dev/artifacts/eas/tRBggDfp26t44Vu2Vfu5DF.apk) da versão beta.
</details>
