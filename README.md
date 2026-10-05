# Studio.ly 🎸

**Studio.ly** é um assistente técnico e estação de utilitários em tempo real para guitarristas, baixistas e músicos. O app integra separação inteligente de hastes musicais (*stem splitting*), recomendações de timbres, ferramentas de treino e o assistente conversacional **Guitar Tech**, projetado para orientar na regulagem de instrumentos, cadeias de sinal e pedaleiras multi-efeitos.

---

## 🚀 Recursos Principais

- **Assistente Guitar Tech:** Chat técnico alimentado pela API Google Gemini para dúvidas de teoria musical, afinações e cadeias de ganho.
- **Processamento de Áudio Local:** Separação de faixas (voz, instrumentos) utilizando modelos neurais embutidos em tempo de execução via **ONNX Runtime** e **TensorFlow Lite**.
- **Player Multifaixa Sincronizado:** Mixer integrado construído sobre o ecossistema **AndroidX Media3 (ExoPlayer)**.
- **Autenticação Segura:** Login simplificado com Google via **AndroidX Credential Manager**.
- **Monetização Integrada:** Gerenciamento de assinaturas e recursos premium através da **Google Play Billing Library 8.0.0**.

---

## 🛠️ Stack Tecnológica

| Componente | Tecnologia |
| :--- | :--- |
| **Linguagem** | Kotlin (Corrotinas & Flow) |
| **Interface** | Jetpack Compose (Material Design 3) |
| **Arquitetura** | MVVM / Clean Architecture unidirecional |
| **Machine Learning** | ONNX Runtime Android & TensorFlow Lite |
| **Processamento de Áudio** | AndroidX Media3 / NDK C++ nativo |
| **IA em Nuvem** | Google Generative AI (Gemini Flash API) |
| **Scripting / Utilitários** | Chaquopy (Python runtime) |
| **Persistência** | DataStore Preferences |

---

## ⚙️ Requisitos do Ambiente

- **Android Studio:** Ladybug / Meerkat ou superior
- **JDK:** Java 17
- **Target SDK:** 36 (Android 16 Baklava)
- **Min SDK:** 26 (Android 8.0)
- **NDK:** Configurado para `arm64-v8a`, `armeabi-v7a` e `x86_64`

---

## 🔑 Configuração Local

1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/studioly.git](https://github.com/seu-usuario/studioly.git)
   cd studioly
