# ⚡ DevClub - Criador de Sites com IA

Este é um projeto de um gerador de páginas da web utilizando Inteligência Artificial. Com apenas uma breve descrição do negócio, a aplicação se conecta à API da **Groq** (utilizando o modelo *Llama 3*) e gera o código HTML e CSS de uma página profissional em poucos segundos.

## 🚀 Funcionalidades

- **Geração Automática**: Recebe um *prompt* do usuário sobre um negócio (ex: "Cafeteria", "Mercado") e solicita a criação da página para a Inteligência Artificial.
- **Visualização do Código**: Exibe o código-fonte (HTML/CSS) gerado pela IA.
- **Preview em Tempo Real**: Renderiza a página criada diretamente na tela, ao lado do código, usando um `iframe`.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura da aplicação.
- **CSS3**: Estilização do sistema de geração, com design responsivo e visual moderno.
- **JavaScript (Vanilla)**: Lógica de integração com a API, captura de eventos e manipulação do DOM (DOM).
- **[Groq API](https://groq.com/)**: Plataforma que disponibiliza modelos de IA ultra-rápidos.
- **Llama 3 (llama-3.3-70b-versatile)**: O modelo de linguagem (LLM) configurado para atuar como um programador web e gerar as páginas.

## 📁 Estrutura do Projeto

- `index.html`: Arquivo principal contendo a interface do usuário.
- `style.css`: Arquivo com todos os estilos da página do gerador.
- `script.js` (ou `scripts.js`): Lógica de programação para consultar a IA e exibir os resultados na tela.

## ⚙️ Como usar

1. **Clone ou baixe o projeto** para o seu computador.
2. **Obtenha uma Chave de API (API Key)**:
   - Crie uma conta na plataforma da [Groq](https://console.groq.com/keys).
   - Gere uma nova chave de API (API Key).
3. **Configure a sua chave no projeto**:
   - Abra o arquivo `script.js` em um editor de código.
   - Encontre a linha onde está escrito `"Authorization": "Bearer <SUA CHAVE AQUI>"`.
   - Substitua `<SUA CHAVE AQUI>` pela chave real fornecida pela Groq.
   
   *Exemplo:*
   ```javascript
   "Authorization": "Bearer gsk_1234567890abcdef..."
   ```

4. **Execute o projeto**:
   - Você pode utilizar uma extensão como o *Live Server* do VS Code, ou simplesmente abrir o arquivo `index.html` diretamente em seu navegador.
5. **Gere seu site**:
   - Digite o tema ou ramo do seu negócio na caixa de texto.
   - Clique em **"⚡️ Gerar"**.
   - Aguarde alguns segundos para que o código seja gerado à esquerda e a prévia do site renderizada à direita!

---
*Projeto desenvolvido como parte dos estudos no **DevClub**.*
