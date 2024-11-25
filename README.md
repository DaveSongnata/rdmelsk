# Gu!de - Seu Guia Turístico Digital 🗺️

Um aplicativo React Native que conecta você aos melhores pontos turísticos de Manaus, Presidente Figueiredo e Rio Preto da Eva.

<div align="center">
  <img src="./assets/screenshots/home.png" width="250" alt="Tela Inicial"/>
  <img src="./assets/screenshots/map.png" width="250" alt="Mapa"/>
  <img src="./assets/screenshots/details.png" width="250" alt="Detalhes"/>
</div>

## 🌟 Destaques
- +600 Pontos Culturais cadastrados
- Interface intuitiva e moderna
- Suporte a múltiplos idiomas
- Integração com Google Maps
- Sistema de eventos e agenda
- Notificações em tempo real

## 🛠️ Tecnologias Principais
- React Native com Expo
- Firebase (Auth & Firestore)
- Styled Components
- React Navigation
- i18next para internacionalização
- date-fns para formatação de datas

## 📱 Dependências Principais
```json
{
  "dependencies": {
    "@react-navigation/bottom-tabs": "^6.5.11",
    "@react-navigation/native": "^6.1.9",
    "@react-navigation/stack": "^6.3.20",
    "expo": "~50.0.5",
    "expo-location": "~16.1.0",
    "expo-notifications": "~0.27.6",
    "firebase": "^10.7.1",
    "i18next": "^23.7.19",
    "react": "18.2.0",
    "react-native": "0.73.2",
    "react-native-maps": "1.10.0",
    "styled-components": "^6.1.8",
    "date-fns": "^3.3.1"
  },
  "devDependencies": {
    "@babel/core": "^7.20.0",
    "@types/react": "~18.2.45",
    "typescript": "^5.1.3"
  }
}
```

## 📱 Funcionalidades
- Autenticação de usuários
- Exploração de pontos turísticos
- Sistema de favoritos
- Agenda de eventos culturais
- Feed de notícias locais
- Integração com mapas
- Suporte offline parcial
- Notificações personalizadas

## 🌍 Idiomas Disponíveis
- Português (Brasil)
- English
- Español

## ⚙️ Configuração do Ambiente

### Pré-requisitos
- Node.js (versão 16 ou superior)
- Expo CLI
- Conta Firebase ativa
- Git

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/DaveSongnata/guide.git
```

2. Instale as dependências:
```bash
cd guide
npm install
```

3. Configure o Firebase:
   - Crie um arquivo `firebase-config.json` em `src/services/`
   - Adicione suas credenciais do Firebase

4. Inicie o projeto:
```bash
npx expo start
```

## 🤝 Como Contribuir
1. Faça um Fork
2. Crie sua Feature Branch (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## 🎨 Paleta de Cores
- Primária: `#FFE929` (Amarelo Guide)
- Secundária: `#171717` (Preto Guide)
- Sucesso: `#4CAF50`
- Alerta: `#FFA000`
- Erro: `#F44336`

## 📱 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Contato
Dave Songnata - [LinkedIn](https://linkedin.com/in/seu-perfil) - email@exemplo.com

Link do Projeto: [https://github.com/DaveSongnata/guide](https://github.com/DaveSongnata/guide)
