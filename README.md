#  Calculadora de IMC (Índice de Massa Corporal)

Este é um aplicativo simples de **Calculadora de IMC** desenvolvido com **React Native**, que permite ao usuário calcular seu IMC a partir do peso e da altura inseridos. O app também exibe a **classificação do IMC** com base no resultado e uma tabela de referência.

---

##  Funcionalidades

* Entrada de peso (kg) e altura (m)
* Cálculo do IMC com validação dos dados
* Exibição do valor do IMC calculado
* Classificação do IMC de acordo com a faixa
* Tabela explicativa com todas as classificações
* Botão de reset para limpar os campos

---

##  Classificações do IMC

| IMC (kg/m²)    | Classificação      |
| -------------- | ------------------ |
| Abaixo de 18,5 | Abaixo do peso     |
| 18,5 a 24,9    | Peso normal        |
| 25 a 29,9      | Sobrepeso          |
| 30 a 34,9      | Obesidade grau I   |
| 35 a 39,9      | Obesidade grau II  |
| 40 ou mais     | Obesidade grau III |

---

##  Tecnologias Utilizadas

* [React Native](https://reactnative.dev/)
* Componentes básicos do React Native (`View`, `Text`, `TextInput`, `TouchableOpacity`, `StyleSheet`, `Keyboard`)
* State management com `useState`

---

##  Como Executar o Projeto

1. **Clone este repositório:**

```bash
git clone https://github.com/seu-usuario/imc-calculadora.git
```

2. **Instale as dependências:**

```bash
npm install
# ou
yarn install
```

3. **Execute o projeto:**

```bash
npx expo start
# ou com CLI puro:
npx react-native run-android
npx react-native run-ios
```

---

##  Estrutura do Projeto

```
IMCCalculator.js  // Componente principal com toda a lógica e interface do app
```

---

##  Validações Implementadas

* Campos obrigatórios
* Apenas números válidos (vírgula é convertida para ponto)
* Altura máxima permitida de 3 metros
* Valores maiores que zero para peso e altura

---

##  Captura de Tela
![image](https://github.com/user-attachments/assets/2325591e-8b56-4a7c-ae18-15be378c9e27) 

 


---
