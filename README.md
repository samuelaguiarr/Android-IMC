# 📱 Calculadora IMC - Android App

## 📋 Descrição
Aplicativo Android desenvolvido em Kotlin com Jetpack Compose para cálculo do Índice de Massa Corporal (IMC). O app oferece uma interface moderna e intuitiva para que os usuários possam calcular seu IMC e receber a classificação correspondente.

## 👥 Equipe
- **Samuel Schaeffer Aguiar** - RM: 550212
- **Rafael Bueno Villela** - RM: 550275
- **Cesar Iglesias** - RM: 98007

## ✨ Funcionalidades
- 🧮 Cálculo automático do IMC
- 📊 Classificação do resultado em categorias:
  - Abaixo do peso (< 18.5)
  - Peso Ideal (18.5 - 24.9)
  - Levemente acima do peso (25.0 - 29.9)
  - Obesidade Grau I (30.0 - 34.9)
  - Obesidade Grau II (35.0 - 39.9)
  - Obesidade Grau III (≥ 40.0)
- 🎨 Interface moderna com Material Design 3
- 📱 Layout responsivo e otimizado para smartphones

## 🛠️ Tecnologias Utilizadas
- **Kotlin** - Linguagem de programação
- **Jetpack Compose** - Framework de UI
- **Material Design 3** - Sistema de design
- **Android Studio** - IDE de desenvolvimento
- **Gradle** - Sistema de build

## 📱 Requisitos do Sistema
- Android 7.0 (API 24) ou superior
- Compile SDK: 36
- Target SDK: 36
- Min SDK: 24

## 🚀 Como Executar
1. Clone o repositório
2. Abra o projeto no Android Studio
3. Sincronize as dependências do Gradle
4. Execute o app em um emulador ou dispositivo físico

## 📁 Estrutura do Projeto
```
app/
├── src/main/
│   ├── java/samuelaguiarr/com/github/androidimc/
│   │   ├── MainActivity.kt          # Activity principal com UI
│   │   ├── CalculoImc.kt           # Funções de cálculo do IMC
│   │   └── ui/theme/               # Arquivos de tema e cores
│   ├── res/
│   │   ├── drawable/               # Recursos de imagem
│   │   ├── values/                 # Strings, cores e temas
│   │   └── mipmap/                 # Ícones do app
│   └── AndroidManifest.xml         # Manifesto do Android
└── build.gradle.kts                # Configurações de build
```

## 🎨 Design
O app utiliza uma paleta de cores personalizada com destaque para o vermelho FIAP (#FFED145B), criando uma identidade visual moderna e profissional. A interface é composta por:

- **Header**: Banner com logo e título do app
- **Formulário**: Card com campos de entrada para peso e altura
- **Resultado**: Card inferior exibindo o IMC calculado e sua classificação

## 📐 Fórmula do IMC
```
IMC = Peso (kg) / (Altura (m))²
```

## 🔧 Configurações de Build
- **Namespace**: `samuelaguiarr.com.github.androidimc`
- **Application ID**: `samuelaguiarr.com.github.androidimc`
- **Version Code**: 1
- **Version Name**: 1.0

## 📄 Licença
Este projeto foi desenvolvido para fins educacionais como parte do curso de desenvolvimento Android.

## 📞 Contato
Para dúvidas ou sugestões, entre em contato com a equipe de desenvolvimento.

---
*Desenvolvido com ❤️ pela equipe FIAP*
