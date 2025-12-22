# 🎬 CennaVerso

<p align="center">
  <img src="./assets/images/iconlogo.png" width="200" alt="CennaVerso Logo" />
</p>

<p align="center">
  <strong>Rede social de cinema com feed</strong><br/>
  <sub>Curadorias colaborativas • Vídeos • Enquetes • Descoberta inteligente</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/React_Native-0.81-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Expo-54-000020?style=for-the-badge&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/TMDB-01D277?style=for-the-badge&logo=themoviedatabase&logoColor=white" />
</p>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 📱 Feed Social
- **Scroll vertical** em tela cheia
- **Vídeos** com tap to play
- **Posts de texto** premium
- **Enquetes** em tempo real
- **Double tap** para curtir 🔥

</td>
<td width="50%">

### 🎬 Descoberta
- **Curadorias colaborativas**
- **Roleta Cenna** (obras em alta)
- **Sistema de Bolts** (gamificação)
- **Busca** TMDB integrada
- **Comentários** e reações

</td>
</tr>
</table>

---

## 🛠️ Tech Stack
```javascript
{
  "frontend": "React 19 + React Native 0.81 (Nova Arquitetura)",
  "runtime": "Expo 54 (Router, AV, Haptics, Blur)",
  "backend": "Firebase (Firestore, Auth, Storage)",
  "api": "TMDB API v3"
}
```

**Otimizações:**
- ⚡ Fabric + TurboModules
- 🎯 FlatList otimizado (60fps)
- 🧠 Controle exclusivo de vídeo
- 🎨 Glassmorphism + Haptics

---

## 🚀 Quick Start

### 1️⃣ Pré-requisitos

- Node.js 18+
- Expo CLI
- [TMDB API Key](https://www.themoviedb.org/settings/api)
- [Firebase Project](https://console.firebase.google.com)

### 2️⃣ Instalação
```bash
# Clone o repositório
git clone https://github.com/joaozzin-dev/cennaverso.git
cd cennaverso

# Instale dependências (obrigatório --legacy-peer-deps)
npm install --legacy-peer-deps

# Configure variáveis de ambiente
cp .env.example .env
```

### 3️⃣ Configure `.env`
```env
EXPO_PUBLIC_TMDB_API_KEY=sua_chave_tmdb

EXPO_PUBLIC_FIREBASE_API_KEY=sua_chave
EXPO_PUBLIC_FIREBASE_AUTH_DOMAIN=seu-projeto.firebaseapp.com
EXPO_PUBLIC_FIREBASE_PROJECT_ID=seu-projeto
EXPO_PUBLIC_FIREBASE_STORAGE_BUCKET=seu-projeto.appspot.com
EXPO_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=123456789
EXPO_PUBLIC_FIREBASE_APP_ID=1:123456789:web:abcdef
```

### 4️⃣ Execute
```bash
npx expo start

# Opções específicas
npx expo start --ios      # iOS
npx expo start --android  # Android
npx expo start --web      # Web (experimental)
```



## 🎯 Roadmap

| Feature | Status |
|---------|--------|
| ✅ Feed estilo TikTok | Concluído |
| ✅ Curadorias colaborativas | Concluído |
| ✅ Sistema de Bolts | Concluído |
| 🚧 Notificações push | Em desenvolvimento |
| 📋 Stories 24h | Planejado |
| 📋 Live streaming | Planejado |
| 📋 Sistema de badges | Planejado |

---

## 🤝 Contribuir

Contribuições são bem-vindas!

1. **Fork** o projeto
2. Crie sua branch (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Add: MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um **Pull Request**

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja [LICENSE](LICENSE) para mais informações.

---

## 🎥 Demo

<p align="center">
  <img src="https://via.placeholder.com/280x560/7209B7/FFFFFF?text=Feed+Vertical" width="280" />
  <img src="https://via.placeholder.com/280x560/F72585/FFFFFF?text=Curadorias" width="280" />
  <img src="https://via.placeholder.com/280x560/4361EE/FFFFFF?text=Enquetes" width="280" />
</p>

<p align="center">
  <sub>📹 GIFs e vídeos de demonstração serão adicionados em breve</sub>
</p>

---

<p align="center">
  <img src="https://github.com/joaozzin-dev.png" width="100" style="border-radius: 50%" /><br/>
  <strong>João Pedro</strong><br/>
  <sub>Full Stack Developer</sub>
</p>

<p align="center">
  <a href="https://github.com/joaozzin-dev">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/joaozzin-dev">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

<p align="center">
  <sub>⭐ Se este projeto te ajudou, considere dar uma estrela!</sub>
</p>

---

<p align="center">
  Feito com ❤️ e ☕ por <strong>@joaozzin-dev</strong>
</p>
