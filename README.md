# 🧠 Turing Mods AV2 – Variações sobre a Máquina de Turing

Este repositório apresenta **implementações modificadas da Máquina de Turing** desenvolvidas como parte da **AV2 (Atividade Avaliativa de Segundo Bimestre)** nas disciplinas de **Linguagens Formais e Autômatos** e **Teoria da Computação**, do curso de Ciência da Computação – CESUPA.

## 🧾 Tema do trabalho

**Tema 5: Outras modificações sobre a Máquina de Turing**

> O objetivo é explorar variações que fogem do modelo clássico de Turing, mas ainda mantêm aspectos formais de computação.

---

## ⚙️ Implementações desenvolvidas

| Implementação          | Descrição                                                                                                                                          |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| `CircularTapeTM.ipynb` | Máquina com fita circular: o cabeçote retorna ao início ao ultrapassar o fim da fita. Ideal para simular contadores, rotações, inversões, buffers. |
| `JumpingHeadTM.ipynb`  | Máquina com cabeçote saltador: anda 2 casas por vez. Simula comportamento parcial, não-linear ou de acesso alternado.                              |

---

## 🔬 Exemplos incluídos

Cada implementação vem com **diversos testes** que ilustram aplicações práticas e teóricas:

* Inversão de bits
* Rotação de strings
* Contador binário com overflow (circular)
* Substituição seletiva com saltos
* Validação de padrão com acessos alternados

---

## 📁 Estrutura do projeto

```
.
├── CircularTapeTM.ipynb       # Implementação da Máquina com Fita Circular (Jupyter Notebook)
├── JumpingHeadTM.ipynb        # Implementação da Máquina com Cabeçote Saltador (Jupyter Notebook)
└── README.md
```

---

## 👨‍💻 Autores

**Cauã Maia**
**Giovanni Braga**
Ciência da Computação – CESUPA
Período: 5º
Professor responsável: Daniel Souza
Semestre: 2025.1

---

## 📘 Licença

Este repositório é disponibilizado apenas para fins acadêmicos. Você pode reutilizar o código livremente com os devidos créditos.
