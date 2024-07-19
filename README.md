# formFulltreina

# Formulário de Cadastro de Alunos

Este projeto é um formulário web para coleta de dados de alunos. Os dados são enviados para uma API externa e os usuários podem optar por receber comunicações de empresas parceiras. O projeto inclui uma página modal que fornece informações adicionais sobre essas empresas.

## Estrutura do Projeto

O projeto contém os seguintes arquivos:

- `index.html`: Página principal com o formulário para coleta de dados.
- `style.css`: Folha de estilos para a página do formulário e o modal.
- `script.js`: Script JavaScript para a funcionalidade do modal.
- `bg.png`: Imagem de fundo para o site (opcional, conforme necessário).

## Arquivos

### `index.html`

Este arquivo contém a estrutura HTML do formulário de cadastro e a implementação do modal. Os principais componentes são:

- **Formulário**: Coleta o nome, e-mail, e número de documento (RG) dos alunos. Inclui dois checkboxes para consentimento.
- **Modal**: Exibe informações sobre empresas parceiras quando o usuário clica no link "Saiba mais sobre as empresas."

### `style.css`

Esta folha de estilos é responsável pelo design do formulário e do modal. Inclui:

- **Estilos Básicos**: Reset básico e estilos gerais para o corpo e container.
- **Formulário**: Estilização dos campos de entrada, botões e layout geral.
- **Modal**: Estilos para a janela modal, incluindo visibilidade, layout e estilização dos botões.

### `script.js`

Este arquivo contém o JavaScript necessário para a funcionalidade do modal. O código é responsável por abrir e fechar a janela modal quando o usuário interage com o link "Saiba mais sobre as empresas."

## Como Usar

1. **Clone o repositório** (se aplicável):

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. **Configure o servidor**:

   - O formulário envia dados para uma API externa (`https://api.sheetmonkey.io/form/iMegcpWoX7U8VHSC5DyL1R`). Certifique-se de que esta URL está configurada corretamente para receber os dados.
   - Se você deseja usar o formulário em um ambiente local, você pode hospedar os arquivos em um servidor local ou serviço de hospedagem.

3. **Abra o arquivo `index.html`**:

   Navegue até a URL onde o formulário está hospedado ou abra o arquivo `index.html` no seu navegador para visualizar e testar o formulário.

4. **Interaja com o modal**:

   - Clique no link "Saiba mais sobre as empresas" para abrir a janela modal e visualizar informações sobre empresas parceiras.
   - Feche o modal clicando no ícone de fechar (×) ou clicando fora da janela modal.

## Personalização

- **Para alterar o texto ou os campos do formulário**: Modifique o arquivo `index.html`.
- **Para ajustar a aparência do formulário e do modal**: Atualize o arquivo `style.css`.
- **Para adicionar mais empresas ao modal**: Edite a lista no arquivo `index.html`.

## Contribuição

Se você deseja contribuir para este projeto:

1. Faça um fork do repositório.
2. Crie uma branch para sua feature ou correção (`git checkout -b feature/nova-feature`).
3. Faça suas alterações e teste-as.
4. Envie um pull request descrevendo suas alterações.
