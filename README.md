# 📱 App Android - Controle de Vendas e Estoque

Este é um aplicativo Android desenvolvido como parte de um projeto de extensão do curso de Análise e Desenvolvimento de Sistemas. O app tem como objetivo auxiliar pequenos comerciantes no controle de vendas e gerenciamento de estoque de forma simples e eficiente.

## 🚀 Funcionalidades

- Autenticação de usuário com Firebase (email e senha)
- Cadastro de produtos (nome, quantidade, validade, preço)
- Registro de vendas e atualização automática do estoque
- Listagem de produtos e histórico de vendas
- Interface simples e intuitiva

## 🛠️ Tecnologias utilizadas

- **Kotlin**
- **Android Studio**
- **Firebase Authentication**
- **Firebase Firestore**
- **Jetpack (ViewModel, LiveData, Navigation)**

## 📁 Estrutura do Projeto

```bash
.
├── data/
│   ├── Product.kt
│   └── Sale.kt
├── ui/
│   ├── LoginActivity.kt
│   ├── MainActivity.kt
│   ├── RegisterProductActivity.kt
│   ├── RegisterSaleActivity.kt
│   ├── ProductListFragment.kt
│   └── SaleListFragment.kt
├── utils/
│   └── ValidationUtils.kt
└── res/layout/
    └── *.xml
