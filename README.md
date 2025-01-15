# Projeto WEATHER_CITY

Este projeto utiliza uma chave de API (`API_KEY`) para realizar requisições. A chave deve ser configurada diretamente no arquivo `config.js` para uso local.

## Como Rodar o Projeto

1. **Pré-requisitos**:
   - Certifique-se de ter o VSCode instalado.
   - Instale a extensão **Live Server** no VSCode.

2. **Configurar a API_KEY**:
   - Crie o arquivo `config.js`.
   - Escreva o código abaixo e substitua o texto `'sua_chave_aqui'` pela sua chave de API válida:
     ```javascript
     const API_KEY = 'sua_chave_aqui';
     export { API_KEY };
     ```

3. **Iniciar o projeto**:
   - Clique com o botão direito no arquivo `index.html` no VSCode.
   - Selecione a opção **"Open with Live Server"**.
   - O navegador será aberto automaticamente com o projeto rodando.

## Observações

- Esta abordagem é apenas para testes locais.
- Não compartilhe sua chave de API publicamente ou suba para repositórios públicos.