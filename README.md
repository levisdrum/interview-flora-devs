# Interview Flora - Design System

PAIR PROGRAMMING DESIGN SYSTEM GB

Bem-vindo ao teste prático de pair programming para candidatos a vagas frontend do Design System do Grupo Boticário.

## 🎯 OBJETIVO

Nosso objetivo com esta etapa do processo seletivo é conhecer melhor suas habilidades técnicas.

Com isso, selecionaremos quais desafios passaremos para você e em quais precisaremos prepará-lo melhor para enfrentar.

## 📋 REQUISITOS DO TESTE

Desenvolver um componente de um Design System de cada frente: **React**, **React Native** e **Flutter**.

### Boas Práticas Obrigatórias:

- ✅ **Reutilização de componente** para o foco em DS
- ✅ **Design Tokens** (cores, espaçamentos, tipografia, border radius)
- ✅ **Acessibilidade básica** (ARIA labels, roles, suporte a teclado) com voiceOver ou NVDA
- ✅ **Eventos e ações** disponíveis nos componentes (callbacks, props)

### Componentes Principais:

1. **Button** - Componente de botão (foco principal do teste)

---

## 🏗️ ESTRUTURA DO PROJETO

Você deve criar um dos projetos abaixo conforme a tecnologia escolhida:

### Opção 1: React Web (Vite + JavaScript)

```
react-web/
├── src/
│   ├── design-system/
│   │   ├── tokens/           # Design Tokens
│   │   │   ├── colors.js
│   │   │   ├── spacing.js
│   │   │   ├── typography.js
│   │   │   ├── borderRadius.js
│   │   │   └── index.js
│   │   └── components/
│   │       └── Button/
│   │           ├── Button.jsx
│   │           ├── Button.css
│   │           └── index.js
│   └── App.jsx
└── package.json
```

### Opção 2: React Native (Expo + Metro)

```
react-native-mobile/
├── src/
│   ├── design-system/
│   │   ├── tokens/           # Design Tokens
│   │   │   ├── colors.js
│   │   │   ├── spacing.js
│   │   │   ├── typography.js
│   │   │   ├── borderRadius.js
│   │   │   └── index.js
│   │   └── components/
│   │       └── Button/
│   │           ├── Button.jsx
│   │           ├── Button.styles.js
│   │           └── index.js
│   └── App.js
└── package.json
```

### Opção 3: Flutter (Dart)

```
flutter_mobile/
├── lib/
│   ├── design_system/
│   │   ├── tokens/
│   │   │   ├── colors.dart
│   │   │   ├── spacing.dart
│   │   │   ├── typography.dart
│   │   │   └── border_radius.dart
│   │   └── components/
│   │       └── button/
│   │           ├── button.dart
│   │           └── button_types.dart
│   └── main.dart
└── pubspec.yaml
```

---

## 🎨 DESIGN REFERENCE

Siga o Figma para direcionar a aparência dos componentes:

**Link:** [Figma Design System Flora](https://www.figma.com/design/6V16GN9NjSSipRG5kz0VvF/Teste-dev-flutter?node-id=850-373&t=9HxNJMdMnfYtIwUH-0)

---

## 🚀 COMPONENTE BUTTON - ESPECIFICAÇÕES

O componente **Button** deve ser implementado seguindo estas diretrizes do handoff

---

## 📦 TECNOLOGIAS

Escolha **uma** das opções abaixo:

### Opção 1 - React Web:
- **Vite** (build tool)
- **React** (JavaScript - sem TypeScript)
- **CSS** ou **CSS-in-JS**
- Design Tokens

### Opção 2 - React Native:
- **Expo** (framework)
- **Metro** (bundler)
- **React Native** (JavaScript - sem TypeScript)
- **StyleSheet API**
- Design Tokens

### Opção 3 - Flutter:
- **Dart** (linguagem)
- **Flutter SDK**
- Design Tokens

---

## ✅ CRITÉRIOS DE AVALIAÇÃO

1. **Design Tokens**: Uso correto e consistente dos tokens
2. **Componentização**: Código limpo, reutilizável e bem organizado
3. **Tipagem Forte**: Tipagem correta e uso de interfaces/tipos
4. **Acessibilidade**: Implementação de recursos básicos de a11y
5. **Boas Práticas**: Nomenclatura, estrutura de pastas, separação de responsabilidades
6. **Testes**: Testes unitários (opcional, mas diferencial)

---

## 🎯 FOCO DO TESTE

Neste momento, o foco principal é criar um **componente Button** robusto e reutilizável.

---

## 📝 INSTRUÇÕES DE IMPLEMENTAÇÃO

### Passo 1: Criar o projeto base

Entenda com no pair pramming qual será seu foco e use os templates sugeridos no teste.

**Opção 1 - React Web (Vite + JavaScript):**

ou

**Opção 2 - React Native (Expo + Metro):**

ou

**Opção 3 - Flutter (Dart):**


### Passo 2: Rodar o projeto

**React Web:**
```bash
npm run dev
```

**React Native (Expo):**
```bash
# Web
npm run web

# iOS (necessita macOS e Xcode)
npm run ios

# Android (necessita Android Studio)
npm run android
```

**Flutter:**
```bash
flutter run
```

### Passo 3: Implementar Design Tokens
- Criar tokens de cores, espaçamentos, tipografia e border radius
- Garantir que os tokens sejam compartilháveis entre web e mobile

### Passo 4: Implementar o componente Button
- Criar interface/tipos TypeScript
- Implementar lógica do componente
- Implementar estilos usando tokens
- Adicionar acessibilidade
- Testar todas as variantes e estados

### Passo 5: Criar exemplos de uso
- Demonstrar diferentes variantes
- Demonstrar diferentes tamanhos
- Demonstrar estados (loading, disabled)
- Demonstrar com ícones

---

## 🤝 PAIR PROGRAMMING

Durante a sessão de pair programming:

1. Compartilhe sua tela
2. Explique seu raciocínio enquanto codifica
3. Faça perguntas quando tiver dúvidas
4. Aceite sugestões e discuta diferentes abordagens
5. Foque em código limpo e boas práticas

---

## 📞 DÚVIDAS

Se tiver dúvidas durante o teste, não hesite em perguntar.

Boa sorte! 🚀

