# Sprint 3 - Computational Thinking With Python

## Integrantes do Grupo
- **Luan Orlandelli** - 554747
- **Igor Medeiros** - 555337
- **Jorge Luiz** - 554418
- **Arthur Bobadilla** - 555056

# Documentação do Sistema de Corrida e Loja de Produtos

Este código implementa um sistema interativo para simular corridas, calcular métricas relacionadas ao desempenho de veículos e gerenciar uma loja virtual de produtos.

## Funções Principais

### 1. `obter_tempos_corridas(quantidade_corridas: int)`
- **Descrição**: Solicita ao usuário os tempos de corridas e os armazena em um dicionário.
- **Parâmetros**:
  - `quantidade_corridas`: Número de corridas que serão realizadas.
- **Retorno**: Dicionário com os tempos das corridas.

### 2. `media_corridas()`
- **Descrição**: Calcula a média de tempos de várias corridas de múltiplos pilotos.
- **Parâmetros**: Não recebe parâmetros.
- **Interação**: Solicita entrada do usuário para o número de pilotos, suas corridas e exibe a média dos tempos.

### 3. `calculadora_velocidade_media()`
- **Descrição**: Calcula a velocidade média com base na distância percorrida e o tempo levado.
- **Parâmetros**: Não recebe parâmetros.
- **Interação**: Solicita distância e tempo do usuário.

### 4. `verificador_capacidade_bateria()`
- **Descrição**: Verifica se a bateria do carro elétrico é suficiente para completar uma corrida, dado o consumo de energia.
- **Parâmetros**: Não recebe parâmetros.
- **Interação**: Solicita capacidade da bateria, consumo por km e distância da corrida.

### 5. `comparador_eficiencia_energetica()`
- **Descrição**: Compara o consumo de energia entre dois carros e determina qual deles é mais eficiente.
- **Parâmetros**: Não recebe parâmetros.
- **Interação**: Solicita os consumos de energia dos dois carros e exibe o resultado da comparação.

### 6. `simulacao_classificacao_corrida()`
- **Descrição**: Simula uma corrida com um número fixo de voltas entre 4 carros e exibe o vencedor.
- **Parâmetros**: Não recebe parâmetros.
- **Interação**: Solicita ao usuário para qual carro ele deseja torcer.

### 7. `menu_opcoes()`
- **Descrição**: Exibe um menu de opções interativas para o usuário escolher qual função deseja executar.

## Funções Auxiliares

### 1. `checa_numero(msg, msg_erro)`
- **Descrição**: Verifica se a entrada fornecida é um número.
- **Parâmetros**:
  - `msg`: Mensagem para solicitar o número.
  - `msg_erro`: Mensagem de erro caso a entrada não seja válida.

### 2. `forca_opcao(msg, conjunto_opcoes)`
- **Descrição**: Solicita uma escolha válida de um conjunto de opções.
- **Parâmetros**:
  - `msg`: Mensagem a ser exibida.
  - `conjunto_opcoes`: Lista de opções disponíveis.

### 3. `remover(dict, chave)`
- **Descrição**: Remove um item de um dicionário baseado em uma chave.

### 4. `cadastrar(dict)`
- **Descrição**: Cadastra novos elementos em um dicionário.

### 5. `atualizar(dict, chave)`
- **Descrição**: Atualiza informações de um item específico no dicionário.

### 6. `printa_dics(dict, qtd)`
- **Descrição**: Exibe de forma organizada o conteúdo de um dicionário.

### 7. `comprar(dict, chave)`
- **Descrição**: Realiza a compra de um produto e adiciona ao carrinho.

### 8. `manipular_database_piloto()`
- **Descrição**: Função para manipular o banco de dados de pilotos.

### 9. `manipular_database_produtos()`
- **Descrição**: Função para manipular o banco de dados de produtos.

## Estruturas de Dados

### `dados_pilotos`
- Dicionário contendo informações dos pilotos como nome, carro, tempo mínimo, posição, nacionalidade e idade.

### `dados_produtos`
- Dicionário contendo informações sobre os produtos, incluindo estoque e preço.

### `carrinho`
- Dicionário representando o carrinho de compras, contendo produtos e valores.

---

Este sistema oferece uma gama de funcionalidades que variam desde a simulação de corridas até a compra e manipulação de produtos, proporcionando uma experiência interativa ao usuário.
Documentação do Sprint 3 de Computional Thinking with Python
