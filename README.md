Sistema de Gerenciamento de Estoque - Autopeças

Aplicação mobile desenvolvida para a gestão interna e controle de estoque de uma loja especializada em volantes e autopeças. O aplicativo foi projetado exclusivamente para o gerenciamento do proprietário, permitindo o cadastro de produtos, controle de quantidades, categorias e armazenamento de dados de forma local e segura.

Tecnologias Utilizadas

* **Framework:** React Native com Expo (Managed Workflow)
* **Linguagem:** JavaScript
* **Banco de Dados:** SQLite (através do `expo-sqlite`)
* **Navegação:** React Navigation (Stack)
* **Manipulação de Mídias:** Expo Image Picker

---

Funcionalidades Principais

* **Cadastro e Edição de Produtos:** Registro detalhado de peças com foto, categoria e quantidade.
* **Banco de Dados Local:** Persistência de dados offline utilizando SQLite para garantir agilidade e segurança das informações.
* **Upload de Imagens:** Integração com a galeria do dispositivo para associar fotos aos produtos cadastrados (com fallback para URL).
* **Interface Dinâmica:** Seleção de categorias via Picker e fluxo fluído de navegação entre telas.

---

Como Executar o Projeto

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em sua máquina.

Clonar o repositório
```bash
git clone [https://github.com/seu-usuario/nome-do-seu-repositorio.git](https://github.com/seu-usuario/nome-do-seu-repositorio.git)
cd nome-do-seu-repositorio
Expo Catalog App - Estruturado (Managed)
---------------------------------------

Instruções rápidas:

1) Instale o Expo CLI se precisar:
   npm install -g expo-cli

2) Dentro da pasta do projeto:
   npm install
   expo install expo-sqlite @react-native-picker/picker expo-image-picker react-native-screens react-native-safe-area-context @react-navigation/native @react-navigation/native-stack

3) Rodar:
   expo start

Observações:
- App em JavaScript
- Banco local com expo-sqlite
- Navegação entre telas via react-navigation (stack)
- Upload de imagem via expo-image-picker (opcional; ainda mantém campo URL)
