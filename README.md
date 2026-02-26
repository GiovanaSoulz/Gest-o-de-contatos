# Gestao de contatos
Aplicativo mobile simples para gestão de contatos, desenvolvido com Expo + React Native + TypeScript.

O app permite cadastrar informações básicas como:

👤 Nome completo

📞 Telefone

📧 Email

📝 Informações adicionais

🖼️ Foto

✅ Status (Ativo/Inativo)

🚀 Tecnologias Utilizadas

Expo

React Native

TypeScript

Expo Go

▶️ Como Executar o Projeto 
- ABRE O CMD
1️⃣ Criar a pasta do projeto
mkdir nome-do-projeto
cd nome-do-projeto
2️⃣ Criar o projeto com template TypeScript
npx create-expo-app nome-do-projeto --template blank-typescript
3️⃣ Acessar a pasta
cd nome-do-projeto
4️⃣ Executar no Android
npm run android

É necessário ter o Android Studio configurado ou usar o aplicativo Expo Go no celular.

📂 Substituir o arquivo principal

Após criar o projeto:

Abra o arquivo App.tsx

Copie o código disponível neste repositório

Cole no seu App.tsx

Salve o projeto

🖼️ Configuração da Imagem

Coloque a imagem dentro da pasta:

/assets/gatito_bonito.jpg

E utilize:

<Image source={require('./assets/gatito_bonito.jpg')} />

⚠️ Evite espaços no nome da imagem.

🎨 Layout

O app possui:

Cabeçalho estilizado

Formulário com ScrollView

Switch para status do contato

Botão para salvar contato

Alert de confirmação

📌 Observações

Projeto simples com foco educacional

Ideal para iniciantes em React Native

Pode ser expandido para salvar dados com AsyncStorage ou banco de dados
