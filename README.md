# exercicio-final-python PretaLabs

# 📚 Exercício: Biblioteca em Python com NumPy

Este projeto é um exercício prático de programação em Python com foco em orientação a objetos, listas, arrays NumPy, boolean masking e funções. Ele simula uma pequena biblioteca com funcionalidades de empréstimo de livros, filtragem por número de páginas e cálculo da média de anos de publicação.

---

## 🧩 Estrutura do Exercício

### ✅ Parte 1: Classe `Livro`
- Define uma classe `Livro` com os atributos:
  - `titulo` (string)
  - `autor` (string)
  - `disponivel` (boolean), iniciado como `True`
- Possui um método:
  - `emprestar()`: altera `disponivel` para `False` e exibe uma mensagem

---

### ✅ Parte 2: Lista de Livros
- Criação de uma lista `biblioteca` com 3 livros:
  - "Dom Casmurro"
  - "Alice no País das Maravilhas"
  - "O Pequeno Príncipe"
- Utiliza um loop para emprestar um dos livros e exibe o status de todos.

---

### ✅ Parte 3: NumPy - Boolean Masking
- Um array com o número de páginas dos livros: `np.array([150, 108, 26])`
- Utiliza Boolean Masking para filtrar e exibir os livros com mais de 100 páginas.

---

### ✅ Parte 4: Função com NumPy
- Um array com anos fictícios de publicação dos livros: `np.array([1899, 1865, 1946])`
- Função `mediaAnos()` que retorna a média dos anos de publicação utilizando `np.mean()`.

---

## 💡 Como executar

1. Instale o NumPy (caso ainda não tenha):
```bash
pip install numpy


