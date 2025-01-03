# 📱 **Trilhar** - App de Educação Financeira

<div align="center">
    <img src="https://github.com/user-attachments/assets/30d481bf-772a-4faf-ba3e-8bc9231a9802" width="150" alt="Trilhar Logo">
</div>

**Trilhar** é um aplicativo desenvolvido como parte do Projeto Integrador, focado em educação financeira. O objetivo do aplicativo é ajudar usuários a gerenciar despesas, metas financeiras e aprender sobre finanças pessoais por meio de vídeos e gráficos interativos.

---

## 🚀 **Principais Funcionalidades**

- **Gerenciamento de despesas**:
  - Cadastro e visualização de despesas armazenadas localmente no SQLite.
  - Relatórios gráficos para análise financeira.

- **Definição de metas financeiras**:
  - Configuração de objetivos financeiros.
  - Acompanhamento de progresso.

- **Módulos educacionais**:
  - Aulas em vídeo organizadas em diferentes níveis.
  - Seção interativa para aprendizado financeiro.

- **Login e autenticação**:
  - Login seguro utilizando Firebase Authentication.

---

## 🛠️ **Tecnologias Utilizadas**

### **Front-end (Aplicativo Android)**:
- **Linguagem**: Java
- **Interface de usuário**: 
  - AndroidX Libraries (Material Design, ConstraintLayout, RecyclerView, ViewPager2).
  - Customização com temas para compatibilidade e responsividade.

### **Back-end e Armazenamento**:
- **Firebase**:
  - **Autenticação**: Login com e-mail/senha e integração com Google.
- **SQLite**:
  - Banco de dados local utilizado para armazenar despesas, metas e outros dados do usuário.

### **Gráficos e Relatórios**:
- **MPAndroidChart**: Para geração de gráficos interativos.

---

## 📋 **Estrutura do Projeto**

### **Principais Componentes**:
1. **Atividades (Activities)**:
   - `atv_login`: Tela de login inicial.
   - `atv_menu`: Tela principal com acesso às funcionalidades.
   - `grafico.AtvGraph`: Tela de relatórios gráficos.
   - `Despesa.atv_despesa`: Tela de gerenciamento de despesas.
   - `atv_metas`: Tela para definição e acompanhamento de metas.

2. **Módulos Educacionais**:
   - `Videos.TelaVideo` até `Videos.TelaVideo5`: Seções de aprendizado em vídeo.

3. **Recursos Visuais**:
   - Ícones e logos personalizados.
   - Tema visual definido em `Theme.TelaPi`.

---

## 🕐 **Como Executar o Projeto**

### Pré-requisitos:
- **Android Studio**: Certifique-se de ter o Android Studio instalado (versão 2022.3 ou superior).
- **Firebase**: Configure um projeto no [Firebase Console](https://console.firebase.google.com/) e baixe o arquivo `google-services.json`.

### Passos:
1. Clone o repositório:
   ```bash
   git clone https://github.com/lucasbor1/Projeto-Trilhar.git
   ```
2. Abra o projeto no Android Studio.
3. Sincronize as dependências do Gradle.
4. Configure o arquivo `google-services.json` no diretório `app/`.
5. Execute o aplicativo em um dispositivo Android físico ou emulador.

---

## 🎨 **Exemplos Visuais**

### Telas do Aplicativo
<div align="center">
    <img src="https://github.com/user-attachments/assets/e461232a-018e-4c8d-a7b1-00588d3cf92d" width="30%" alt="Tela Login">
    <img src="https://github.com/user-attachments/assets/9f89fed2-b1d7-4f90-a4e1-6c22ae51941d" width="30%" alt="Tela Menu">
    <img src="https://github.com/user-attachments/assets/dcbce549-5cf5-4b81-ba7e-3f5c609498ef" width="30%" alt="Tela Despesas">
</div>

---

## 📚 **Aprendizados e Futuras Melhorias**
- **Aprendizados**:
  - Uso do Firebase para autenticação.
  - Armazenamento de dados local com SQLite.
  - Criação de gráficos interativos com MPAndroidChart.
  - Design responsivo e compatível com múltiplas versões de Android.

- **Futuras Melhorias**:
  - Implementação de notificações push.
  - Adição de mais módulos educacionais.
  - Suporte a idiomas.

---
