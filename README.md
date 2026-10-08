# ♟️ Xadrez em Terminal
<img width="1067" height="1008" alt="Imagem-Terminal" src="https://github.com/user-attachments/assets/06fdc479-6aaa-4f66-94cd-fa37a8a03291" />

Programa de console feito em C# / .NET com o propósito de treinar e solidificar os pilares da Programação Orientada a Objetos (POO) e a lógica de programação usada num jogo de xadrez completo.

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
