# NavegacaoApp

Aplicativo de navegação desenvolvido com React Native e TypeScript.

## 🚀 Tecnologias

- React Native
- TypeScript
- Expo
- React Navigation

## 📋 Pré-requisitos

Antes de começar, você precisa ter instalado em sua máquina:

- Node.js (versão 18 ou superior)
- npm (vem junto com o Node.js)
- Git
- Expo CLI (instale globalmente com `npm install -g expo-cli`)

## 🔧 Instalação

1. Clone o repositório
```bash
git clone [URL_DO_REPOSITÓRIO]
cd NavegacaoApp
```

2. Instale as dependências
```bash
npm install
```

3. Inicie o projeto
```bash
npm start
```

Após executar `npm start`, o Expo Developer Tools será aberto no seu navegador. Você terá algumas opções:
- Pressione `w` para abrir na web
- Pressione `a` para abrir no Android (requer Android Studio e um emulador configurado)
- Pressione `i` para abrir no iOS (requer macOS e Xcode)
- Escaneie o QR Code com o app Expo Go no seu celular

## 📱 Executando o App

### Web
```bash
npm run web
```

### Android
1. Certifique-se de ter o Android Studio instalado
2. Configure um emulador Android ou conecte um dispositivo físico
3. Execute:
```bash
npm run android
```

### iOS (apenas macOS)
1. Certifique-se de ter o Xcode instalado
2. Execute:
```bash
npm run ios
```

## ⚠️ Solução de Problemas

Se encontrar algum erro durante a instalação ou execução:

1. Certifique-se de que todas as dependências estão instaladas corretamente:
```bash
npm install
```

2. Limpe o cache do npm:
```bash
npm cache clean --force
```

3. Delete a pasta node_modules e o arquivo package-lock.json:
```bash
rm -rf node_modules package-lock.json
npm install
```

4. Se estiver usando Windows, execute o PowerShell como administrador

5. Se o erro persistir, verifique se todas as versões das dependências no package.json são compatíveis entre si 