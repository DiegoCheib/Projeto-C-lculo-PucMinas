# Projeto-Calculo-PucMinas

Este projeto é uma ferramenta interativa para calcular e visualizar funções matemáticas, suas derivadas, pontos específicos e retas tangentes, utilizando a API do GeoGebra para renderizar gráficos.

## Funcionalidades

- **Entrada de Função**: Permite ao usuário inserir uma função matemática.
- **Cálculo de Derivada**: Calcula a derivada da função inserida.
- **Valor Funcional e Derivada no Ponto**: Calcula o valor da função e da derivada em um ponto específico.
- **Visualização de Função e Ponto**: Adiciona a função e um ponto específico ao gráfico do GeoGebra.
- **Reta Tangente**: Calcula e adiciona a reta tangente à função no ponto especificado ao gráfico do GeoGebra.
- **Centralização Automática**: Centraliza automaticamente o gráfico no ponto especificado.
- **Limpeza de Gráfico**: Limpa todas as funções e objetos existentes no gráfico antes de adicionar uma nova função.

## Tecnologias Utilizadas

- **HTML**: Para estrutura da página.
- **JavaScript**: Para manipulação da lógica, cálculo das funções e integração com a API do GeoGebra.
- **Math.js**: Para manipulações e cálculos matemáticos.
- **GeoGebra**: Para renderização dos gráficos.

## Como Utilizar

1. **Clone o Repositório**:
    ```bash
    git clone https://github.com/seu-usuario/Projeto-Calculo-PucMinas.git
    cd Projeto-Calculo-PucMinas
    ```

2. **Abra o arquivo HTML**:
    Abra o arquivo `index.html` no seu navegador preferido.

3. **Insira a Função**:
    Digite a função matemática no campo de entrada e clique no botão "Calcular".

4. **Calcule o Valor Funcional e Derivada no Ponto**:
    Siga as instruções nas janelas de prompt para inserir o valor de `a`.

5. **Visualize a Função e o Ponto no GeoGebra**:
    A função e o ponto especificado serão exibidos no gráfico do GeoGebra.

6. **Calcule e Visualize a Reta Tangente**:
    Siga as instruções nas janelas de prompt para calcular e visualizar a reta tangente no gráfico do GeoGebra.
   
## Exemplo de Uso

1. Digite a função `4x^4 + 3x^2 + 5x + 8` e clique em "Calcular".
2. Quando solicitado, insira `-3` como o valor de `a`.
3. O valor funcional `f(a)`, a derivada `f'(a)` e o ponto `(a, f(a))` serão calculados e exibidos no gráfico do GeoGebra.
4. Quando solicitado, insira `-3` novamente para calcular a reta tangente.
5. A reta tangente será exibida no gráfico do GeoGebra.

