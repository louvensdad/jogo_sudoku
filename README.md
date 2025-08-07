# Jogo de Sudoku em Java (Terminal)

Este é um jogo de Sudoku interativo implementado em Java para o terminal. O objetivo deste projeto é demonstrar habilidades em programação orientada a objetos, manipulação de dados, métodos e classes, além de lidar com entrada e saída no terminal.

## Funcionalidades

*   **Tabuleiro de Sudoku:** Representação do tabuleiro como uma matriz 9x9.
*   **Entrada do Usuário:** Permite que o usuário insira valores nas células do tabuleiro.
*   **Validação de Jogada:** Verifica se a jogada do usuário é válida de acordo com as regras do Sudoku.
*   **Impressão do Tabuleiro:** Exibe o tabuleiro atualizado no terminal após cada jogada.
*   **Verificação de Solução:** Checa se o Sudoku foi resolvido corretamente.
*   **Geração de Tabuleiro (Opcional):** Utiliza um solucionador de Sudoku para gerar tabuleiros válidos (não implementado nesta versão base).
*   **Interface Interativa no Terminal:** O jogo é jogado diretamente no terminal, com instruções claras para o usuário.

## Como Jogar

1.  **Pré-requisitos:**
    *   Java Development Kit (JDK) instalado no seu sistema.
2.  **Compilação:**
    *   Abra o terminal ou prompt de comando.
    *   Navegue até o diretório onde os arquivos `.java` estão localizados.
    *   Compile os arquivos usando o comando: `javac SudokuBoard.java SudokuSolver.java Main.java`
3.  **Execução:**
    *   Execute o jogo com o comando: `java Main`
4.  **Instruções:**
    *   O tabuleiro será exibido no terminal.
    *   O jogo solicitará que você insira a linha, coluna e valor que deseja inserir.
    *   Siga as instruções e insira os valores correspondentes.
    *   O jogo informará se a jogada é válida ou não.
    *   Continue jogando até resolver o Sudoku ou até que decida sair.

## Estrutura do Código

O projeto é composto pelas seguintes classes:

*   **`SudokuBoard`:** Representa o tabuleiro do Sudoku e contém métodos para acessar, modificar, imprimir e validar o tabuleiro.
*   **`SudokuSolver`:** (Opcional) Responsável por resolver o Sudoku ou gerar tabuleiros válidos.
*   **`Main`:** Classe principal que contém o método `main` para iniciar o jogo, interagir com o usuário e coordenar as ações.

## Implementação Futura (Roadmap)

*   Implementar um algoritmo de backtracking na classe `SudokuSolver` para gerar tabuleiros de Sudoku aleatórios.
*   Adicionar diferentes níveis de dificuldade (fácil, médio, difícil).
*   Permitir que o usuário desista do jogo.
*   Melhorar a interface do usuário no terminal com cores e formatação mais avançada.

## Autor

*   Louvensdad Constantin

## Contribuições

Contribuições são bem-vindas! Se você tiver alguma sugestão de melhoria ou correção de bug, sinta-se à vontade para abrir uma issue ou enviar um pull request.
