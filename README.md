# ♟️ Xadrez em Terminal

Um programa de console criado em C# / .NET com o propósito de praticar e solidificar os alicerces da Programação Orientada a Objetos (POO) e a lógica de programação aplicada a um jogo de xadrez completo.

---

 📌 Detalhes do Projeto

Este projeto envolve a modelagem e a execução de uma partida de xadrez no terminal, cuidando da validação das regras do jogo, do manuseio de matrizes e da gestão dos turnos.

A ideia principal foi usar os conceitos básicos da programação orientada a objetos de um jeito claro e organizado.

---

 🧠 Princípios de POO Empregados

*   Classes e Objetos: Organização das entidades relevantes do jogo, como `Tabuleiro`, `Peca`, `Posicao` e `PartidaDeXadrez`.
*   Herança: Desenvolvimento de uma classe base `Peca` com características e atributos gerais, a qual é herdada pelas peças individuais (`Torre`, `Bispo`, `Cavalo`, `Rei`, `Rainha`, `Peao`).
*   Encapsulamento: Salvaguarda dos dados internos das classes (como o status das peças e as dimensões do tabuleiro) para assegurar a consistência das informações e prevenir alterações não autorizadas.
*   Polimorfismo: Reescrever métodos para definir os movimentos específicos de cada tipo de peça no tabuleiro.
*   Lógica de Matrizes e Tratamento de Exceções: Gerenciamento bidimensional do tabuleiro e tratamento de erros para movimentos inválidos ou que ultrapassem os limites permitidos.

---

 🛠️ Ferramentas Empregadas

*   Linguagem: C#
*   Plataforma: .NET
*   Tipo de Aplicação: Aplicação de Console
