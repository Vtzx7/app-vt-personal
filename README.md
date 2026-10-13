[readme_vt_personal.md](https://github.com/user-attachments/files/33401394/readme_vt_personal.md)
# 🏋️‍♂️ VT Personal — Seu Treino Inteligente

O **VT Personal** é um aplicativo web completo de acompanhamento e geração de treinos de academia, desenvolvido com foco em personalização, design moderno e facilidade de uso. 

O aplicativo conta com integração de **Inteligência Artificial (Google Gemini API)** para gerar fichas de treino automatizadas com base no perfil físico de cada usuário, além de sincronização em tempo real na nuvem através do **Firebase Firestore**.

---

## 🎨 Paleta de Cores e Identidade Visual

O projeto foi construído utilizando uma paleta moderna e elegante baseada em tons de **Roxo (Violet/Brand)** e **Branco**, oferecendo um visual dinâmico e agradável para uso na academia:

* **Roxo Primário:** `#7C3AED` (`brand-600`)
* **Roxo Escuro / Header:** `#2E1065` / `#4C1D95` (`brand-950` / `brand-900`)
* **Destaques & Acentos:** `#A78BFA` / `#C4B5FD` (`brand-400` / `brand-300`)
* **Fundo / Neutros:** `#F8FAFC` (Slate-50) & `#FFFFFF` (White)

---

## 🚀 Funcionalidades Principais

* **👤 Perfil Físico Completo:**
  * Cadastro de nome, idade, gênero, peso, altura, nível de experiência e frequência semanal.
  * Cálculo automático de **IMC (Índice de Massa Corporal)**.

* **🤖 Gerador de Treino com Inteligência Artificial (Gemini API):**
  * Monta uma rotina semanal completa (Segunda a Domingo) adaptada às características físicas e objetivos do usuário (Emagrecimento, Hipertrofia, Força ou Condicionamento).
  * Define automaticamente séries, repetições, tempo de descanso recomendado e dicas de execução para cada exercício.

* **📅 Agenda e Calendário de Treinos:**
  * Visualização organizada por dias da semana ou visão geral ("Todos os dias").
  * Checkbox interativo para marcar exercícios concluídos.
  * Barra de progresso percentual por treino.

* **⏱️ Timer de Descanso Interativo:**
  * Timer flutuante em tempo real para controle do descanso entre as séries.
  * Botões de atalho (+15s, +30s) e sinal sonoro (*beep*) ao finalizar o tempo.

* **✍️ Criador Manual de Treinos:**
  * Permite criar fichas de treino 100% personalizadas do zero, adicionando exercícios, séries, repetições e tempos de descanso manualmente.

* **☁️ Sincronização na Nuvem (Firebase):**
  * Salva automaticamente o perfil e as fichas de treino no banco de dados Firestore para que o usuário não perca suas informações ao fechar o navegador.

---

## 🛠️ Tecnologias Utilizadas

* **Frontend:**
  * HTML5 Semântico
  * [Tailwind CSS](https://tailwindcss.com/) (CDN) — Estilização responsiva e customizada
  * [Phosphor Icons](https://phosphoricons.com/) — Iconografia moderna
* **Backend & Cloud:**
  * [Firebase Firestore](https://firebase.google.com/docs/firestore) — Banco de dados NoSQL em tempo real
  * [Firebase Authentication](https://firebase.google.com/docs/auth) — Autenticação de usuários
* **Inteligência Artificial:**
  * [Google Gemini API (`gemini-3-flash-preview`)](https://ai.google.dev/) — Geração inteligente de fichas de treino com saída JSON estruturada

---

## 📁 Estrutura de Arquivos

O projeto foi arquitetado sob o modelo de **Single File Application**, permitindo rápida implantação sem a necessidade de etapas complexas de compilação (*build step*):

```
├── index.html        # Arquivo principal contendo HTML, Tailwind, JS e lógica do Firebase/Gemini
└── README.md         # Documentação do repositório
```

---

## 💻 Como Executar o Projeto

Como o aplicativo é construído em um único arquivo HTML Client-Side:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/vt-personal.git
   cd vt-personal
   ```

2. **Abra o arquivo:**
   * Basta dar um duplo clique no arquivo `index.html` ou abri-lo em qualquer navegador moderno.
   * Se utilizar o VS Code, você pode utilizar a extensão **Live Server** para rodar localmente.

---

## 📄 Licença

Este projeto é livre para fins de estudo e uso pessoal.

---

<p center="text-center">
  Desenvolvido com 💜 por <strong>VT Personal</strong>
</p>
```
eof
```

Espero que este README ajude a deixar seu repositório no GitHub super organizado e profissional! Se precisar de mais ajustes no texto ou nas seções, é só avisar.
