🎬 Cenna — Movie & Series Social Network

<p align="center">
  <img src="./assets/images/iconlogo.png" width="160" alt="Cenna Logo" />
</p><p align="center">
  <img src="https://img.shields.io/badge/Expo-54-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo 54" />
  <img src="https://img.shields.io/badge/React_Native-0.81-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native 0.81" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React 19" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-NativeWind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="NativeWind" />
</p><p align="center">
  <strong>A ponte entre o cinema e conexões reais.</strong><br/>
  <sub>The bridge between cinema and real connections.</sub>
</p><p align="center">
  <a href="#-sobre-o-projeto">🇧🇷 Português</a> •
  <a href="#-about-the-project">🇺🇸 English</a> •
  <a href="#-technical-highlights">🛠 Technical</a> •
  <a href="#-setup">🚀 Setup</a>
</p>
---

🇧🇷 Sobre o Projeto

O Cenna não é apenas um rastreador de filmes — é uma rede social cinematográfica.
O projeto combate a fadiga da escolha ao substituir algoritmos genéricos por curadoria humana colaborativa, promovendo interação social em torno de filmes e séries.

✨ Diferenciais

🎬 Curadoria Colaborativa
Listas dinâmicas onde a comunidade adiciona e organiza conteúdos.

🌐 Social-First
Críticas em texto, reviews em vídeo e enquetes interativas.

🌙 Experiência Fluida
Interface premium com Glassmorphism, Blur e Haptics.

⚙️ Arquitetura de Ponta
Um dos primeiros apps brasileiros a utilizar React 19 e a Nova Arquitetura do React Native (Fabric / TurboModules).



---

🇺🇸 About the Project

Cenna is a collaborative social ecosystem for cinema enthusiasts.
It eliminates choice fatigue by replacing generic recommendation algorithms with human-driven curation, social interaction, and thematic discovery.

✨ Key Highlights

🎥 Crowdsourced Curation
Dynamic lists enriched by the community.

💬 Full Social Suite
Text reviews, video snippets, and interactive polls.

🎨 Premium UX
High-end interface featuring Blur effects and tactile feedback.

🚀 Cutting-Edge Stack
Built with React 19 and the New Architecture for maximum performance.



---

🎥 Demonstração / Demo

<p align="center">
  <img 
    src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJueW94bnd6Z3R4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4JmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCZjdD1n/PLACEHOLDER_GIF_1/giphy.gif" 
    width="300" 
    style="border-radius: 20px"
  />
</p>
---

🛠 Technical Highlights

Este projeto foi concebido como um desafio de engenharia focado em performance nativa.

⚙️ Nova Arquitetura
newArchEnabled: true, utilizando o motor de renderização Fabric.

🧵 Worklets & Multithreading
Uso intensivo de react-native-worklets-core para processamento em threads secundárias, mantendo 60fps constantes.

🔗 Integração Híbrida
Backend distribuído entre Supabase (PostgreSQL, Auth) e Firebase (funcionalidades em tempo real).

🧠 Type Safety & Smart Detection
Detecção inteligente de metadados do TMDB, diferenciando dinamicamente Movies e TV Shows.



---

🚀 Setup

1️⃣ Requisitos

Node.js 18+

Expo CLI

Chaves de API:

TMDB

Supabase

Firebase



2️⃣ Instalação

# Clone o repositório
git clone https://github.com/joaozzin-dev/bros.git

# Instale as dependências
# (Obrigatório o uso de legacy-peer-deps devido ao React 19)
npm install --legacy-peer-deps

3️⃣ Variáveis de Ambiente (.env)

EXPO_PUBLIC_TMDB_API_KEY=sua_chave
EXPO_PUBLIC_SUPABASE_URL=seu_url
EXPO_PUBLIC_SUPABASE_ANON_KEY=sua_chave_anon


---

🤝 Contribuição

1. Fork o projeto


2. Crie uma branch (git checkout -b feature/AmazingFeature)


3. Commit (git commit -m 'Add AmazingFeature')


4. Push (git push origin feature/AmazingFeature)


5. Abra um Pull Request




---

📄 License

Distribuído sob a licença MIT.
Veja o arquivo LICENSE para mais detalhes.




<p align="center">
  <strong>João Pedro (@joaozzin-dev)</strong><br/>
  <a href="https://linkedin.com/in/SEU_LINKEDIN">LinkedIn</a> •
  <a href="mailto:seuemail@exemplo.com">Email</a>
</p>
