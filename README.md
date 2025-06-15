# ⚔️ RPG Battle Simulator: Um Estudo de Estruturas de Dados

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jjulinha/simulador-batalha-rpg/blob/main/Simulador_de_Batalha_de_RPG.ipynb) 
> **Status do Projeto:** Concluído ✔️

### 📝 Descrição do Projeto

Este projeto implementa um simulador de batalha por turnos com temática de fantasia medieval. O objetivo principal foi aplicar e integrar três estruturas de dados fundamentais da ciência da computação para gerenciar a lógica do jogo: **Listas, Filas e Pilhas**.

### ✨ Funcionalidades

- **Batalha por Turnos:** Heróis e inimigos se enfrentam em uma arena.
- **Gerenciamento de Turnos com Fila:** Um sistema justo (FIFO) que determina a ordem de ação dos personagens.
- **Histórico de Ações com Pilha:** Cada jogada é salva, permitindo a funcionalidade de "desfazer" a última ação (LIFO).
- **Lógica de Combate:** Personagens possuem atributos de vida (HP) e ataque, e a batalha prossegue até que uma equipe seja completamente derrotada.

### 🛠️ Estruturas de Dados e Tecnologias

- **Python:** Linguagem principal do projeto.
- **Listas (`list`):** Utilizadas para armazenar as equipes de heróis e inimigos.
- **Filas (`collections.deque`):** Empregadas para gerenciar a ordem dos turnos de forma eficiente (O(1) para adicionar/remover).
- **Pilhas (`list`):** Usadas para implementar o histórico de ações e a função de desfazer.
- **Google Colab:** Ambiente de desenvolvimento interativo.
- **Git & GitHub:** Para controle de versão e hospedagem do código.

---

### 🚀 Como Executar

Este projeto foi desenvolvido como um notebook e pode ser executado diretamente no navegador.

1.  **Clique no botão "Open in Colab"** no topo deste README.
2.  O projeto será aberto no ambiente do Google Colab.
3.  No menu superior, clique em `Ambiente de execução` > `Executar tudo`.
4.  A simulação da batalha será processada e o resultado exibido no final do notebook.

---

### 📈 Análise de Complexidade

Uma operação crítica analisada foi o **processamento de um turno completo**. A complexidade de tempo foi determinada como **O(H + E)**, onde `H` é o número de heróis e `E` o número de inimigos. Essa complexidade linear, dominada pela necessidade de filtrar as listas de personagens vivos a cada turno, é altamente eficiente para a escala do simulador.

### 👤 Autores

| Nome                                     | Papel no Projeto                  | GitHub                                    |
| ---------------------------------------- | --------------------------------- | ----------------------------------------- |
| Júlia Oliveira Dias                 | Desenvolvedor e Gerente de Projeto | [[link para seu perfil no GitHub](https://github.com/jjulinha)]          |


### 🔗 Links do Projeto

- **Repositório:** `(https://github.com/jjulinha/simulador-batalha-rpg)`

### 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
