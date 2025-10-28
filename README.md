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

## 📸 Screenshots e Testes

### Interface Principal
<img width="235" height="533" alt="image" src="https://github.com/user-attachments/assets/5d7c055f-2c69-44f0-8f26-87b5c9f3d520" />


### Teste de Cálculo - Peso Ideal
<img width="233" height="535" alt="image" src="https://github.com/user-attachments/assets/4849bb5f-26e4-4d6d-aca0-fb8c638c7ead" />

### Teste de Cálculo - Levemente acima do peso
<img width="235" height="530" alt="image" src="https://github.com/user-attachments/assets/41d28ab1-def8-43a0-9346-fc5164f14e29" />

### Teste de Cálculo - Obesidade
<img width="235" height="523" alt="image" src="https://github.com/user-attachments/assets/fa9371da-1a43-491f-b095-f629dab847a5" />


### Teste de Cálculo - Abaixo do Peso
<img width="241" height="527" alt="image" src="https://github.com/user-attachments/assets/00e13c93-a538-4101-ae40-69d5b1715980" />
