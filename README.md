# NavegacaoApp

Um aplicativo React Native com navegação entre telas usando React Navigation, focado em desenvolvimento web.

## Screenshots

### Home Screen

![Home Screen](screenshots/home.png)

### Details Screen
![Details Screen](screenshots/details.png)


## Tecnologias Utilizadas

- React Native Web
- TypeScript
- React Navigation
- Expo

## Pré-requisitos

- Node.js
- npm ou yarn
- Expo CLI

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/TiagosailE/NavegacaoApp.git
cd NavegacaoApp
```

2. Instale as dependências:
```bash
npm install
```

3. Instale as dependências específicas de navegação:
```bash
npm install @react-navigation/native
npx expo install react-native-screens react-native-safe-area-context
npm install @react-navigation/native-stack
npx expo install react-native-gesture-handler react-native-reanimated react-native-screens
```

## Executando o Projeto

### Web
```bash
npm run web
```

## Estrutura do Projeto

```
NavegacaoApp/
├── App.tsx              # Componente principal
├── assets/             # Imagens e recursos
├── src/
│   └── screens/        # Telas do aplicativo
├── app.json           # Configuração do Expo
└── package.json       # Dependências do projeto
```

## Funcionalidades

- Navegação entre telas usando React Navigation
- Interface responsiva para web
- Suporte a TypeScript
- Design moderno e limpo

## Contribuição

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3. Faça o Commit das suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Faça o Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
