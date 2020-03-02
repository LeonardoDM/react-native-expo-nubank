## Interface Mobile do App Nubank

Esse projeto é uma versão alternativa do aplicativo apresentado em vídeo aula da [Rocketseat](https://github.com/Rocketseat/youtube-react-native-nubank), mas agora utilizando Expo.
Algumas ferramentas/frameworks apresentados no vídeo durante o desenvolvimento da aplicação, não foram utilizadas nesta versão.

Vídeo da Rocketseat replicando a interface do Nubank com React Native: https://youtu.be/DDm0M_rZLJo

### Requisitos

- NodeJS (para a instalação de pacotes pelo npm)
- Expo v36+

### Executando o projeto

- Instale o Expo globalmente - `npm install -g expo-cli`
- Instale as dependências - `npm i` ou `expo i`
- Execute o projeto - `expo start`

Para mais detalhes, acesse a [documentação](https://docs.expo.io/versions/v36.0.0/get-started/installation/).

### Observações 

Pode ocorrer o seguinte erro ao tentar rodar o app pela primeira vez:

![package-error](https://user-images.githubusercontent.com/27246482/75368725-e9dfee80-58a0-11ea-9123-29e908da1fe3.png)

#### Como Resolver

- Desinstale o react-native-svg - `npm un react-native-svg`
- Execute o projeto (resultará em erro ao tentar encontrar o módulo react-native-svg) - `expo start`
- Interrompa a execução do mesmo - `Ctrl+C`
- Instale o react-native-svg novamente utilizando expo - `expo install react-native-svg`
- Execute o projeto novamente - `expo start`

Caso os passos acima não tenham solucionado o problema, [clique aqui](https://github.com/react-native-community/react-native-svg/issues/1273#issuecomment-583109771) para mais informações.
