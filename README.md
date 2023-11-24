# Sistema de cadastro de Corridas.

## Descrição do Projeto

Este projeto em Java foi desenvolvido com o objetivo de treinar e aplicar conceitos fundamentais de programação, especialmente no contexto de desenvolvimento de aplicativos desktop. O sistema é uma aplicação simples para gerenciar corridas, envolvendo usuários, motoristas e informações sobre as corridas realizadas.

## Funcionalidades

1. **Cadastro de Corridas:**
   - Permite cadastrar novas corridas, associando usuários e motoristas.
   - Armazena informações como origem, destino e os envolvidos na corrida.

2. **Edição de Corridas:**
   - Possui funcionalidade para editar informações de corridas existentes.

3. **Listagem de Corridas:**
   - Apresenta uma lista de todas as corridas cadastradas.
   - Exibe detalhes como origem, destino, usuário e motorista associados.

4. **Consulta por ID:**
   - Permite consultar informações detalhadas de uma corrida específica com base no seu ID.

5. **Exclusão de Corridas:**
   - Possui a capacidade de excluir corridas do sistema.

6. **Integração com Usuários e Motoristas:**
   - Utiliza classes DAO para a integração com as entidades `Usuario` e `Motorista`.
   - Garante a consistência das informações ao associar corretamente usuários e motoristas às corridas.

## Estrutura do Projeto

- `CorridaDAO.java`: Classe responsável pela manipulação dos dados relacionados às corridas. Implementa operações como inserção, edição, exclusão e seleção.
- `UsuarioDAO.java` e `MotoristaDAO.java`: Classes semelhantes à `CorridaDAO`, responsáveis pela integração com as entidades `Usuario` e `Motorista`, respectivamente.
- `Corrida.java`, `Usuario.java` e `Motorista.java`: Classes que modelam as entidades do sistema.
- `ConnectionFactory.java`: Classe para estabelecer a conexão com o banco de dados.

## Instruções de Configuração

1. **Banco de Dados:**
   - Faça o download do [arquivo zip](https://drive.google.com/file/d/1x81rApU2cEXzvP0z12pofrlAo_bWkmct/view?usp=sharing) contendo o backup do banco de dados.
   - Descompacte o arquivo e importe o banco de dados utilizando o backup fornecido.
   - Feito isso apenas execute o usbw. 
   - Certifique-se de inserir o login "root", e a senha "usbw".

2. **Compilação e Execução:**
   - Utilize um ambiente de desenvolvimento Java, como Eclipse ou IntelliJ.
   - Compile e execute a classe principal associada à interface gráfica.

3. **Personalização:**
   - Adapte as consultas e operações DAO conforme necessário.
   - Personalize a interface gráfica de acordo com os requisitos do projeto.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para reportar problemas, sugerir melhorias ou enviar pull requests.
