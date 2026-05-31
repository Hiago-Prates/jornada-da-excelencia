# 🚀 Jornada da Excelência — Treinamento Gamificado | Mercado Livre

> Game interativo de treinamento desenvolvido para o time de Inventário do hub BRSP06 do Mercado Livre. Transforma conteúdo técnico-operacional em uma experiência gamificada, competitiva e engajante — rodando direto no browser, sem instalação.

---

## 🎯 O Problema

Em times operacionais grandes, garantir que todos os colaboradores dominam os processos corretos é um desafio constante. Treinamentos tradicionais são passivos, fáceis de esquecer e difíceis de mensurar.

A necessidade era criar algo que:
- Engajasse o time de forma ativa e divertida
- Testasse o conhecimento de forma prática e competitiva
- Identificasse pontos de oportunidade de melhoria por colaborador
- Reforçasse os DNAs organizacionais do Mercado Livre
- Funcionasse sem instalação — acessível de qualquer dispositivo

---

## 💡 A Solução

Um **game interativo completo** com sistema de pontuação, disputa entre grupos, roubo de pergunta e ranking histórico — tudo desenvolvido do zero com HTML, CSS e JavaScript puro.

---

## 🔧 Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura e semântica do game |
| **CSS3** | Animações, efeitos 3D, glassmorphism, partículas |
| **JavaScript (Vanilla)** | Lógica do game, pontuação, estado e ranking |
| **Canvas API** | Background animado com partículas e hexágonos |
| **LocalStorage** | Persistência do ranking histórico entre sessões |

> Sem frameworks. Sem dependências externas. Zero instalação.

---

## 🎮 Como Funciona

### Dinâmica de Jogo
- **2 grupos** disputam: ⭐ *Executo com Excelência* vs 🔥 *Dou o Máximo e me Divirto*
- **41 perguntas** embaralhadas aleatoriamente a cada partida
- **3 níveis de dificuldade** com pontuações diferentes:
  - ✅ **OK** — até 3 pontos
  - 🔥 **Difícil** — até 4 pontos
  - 💀 **HARD** — até 5 pontos
- **Sistema de Roubo de Pergunta** — se o grupo da vez errar, o grupo rival pode tentar responder e ganhar metade dos pontos
- **Avaliação qualitativa** — o mediador pontua com base na qualidade da resposta (Completa / Estruturada / Parcial / Errada)

### Placar em Tempo Real
- Barra de progresso animada para cada grupo
- Pontuação com animação de destaque a cada acerto
- Indicador visual de qual grupo está na vez

### DNAs do Mercado Livre
- Cada pergunta está associada a um DNA organizacional
- Popups animados exibem qual DNA foi ativado a cada resposta correta
- Tela "Nossa Cultura" com cards interativos flip 3D mostrando todos os 6 DNAs

### Ranking Histórico
- Todas as partidas ficam salvas automaticamente
- Histórico das últimas 10 partidas com data, vencedor e placar

---

## 🖼️ Capturas de Tela

### Tela Inicial
![Tela inicial](imagens/home.png)

### Nossa Cultura — DNAs do Mercado Livre
![Nossa Cultura](imagens/cultura.png)

### Ranking Histórico
![Ranking](imagens/ranking.png)

---

## ✨ Destaques Técnicos

- **Background generativo** com Canvas API — partículas conectadas e hexágonos giratórios animados em loop
- **Animações CSS puras** — foguetes voando, efeitos de glow, scanlines, respiração de gradiente
- **Cards com flip 3D** na tela de cultura usando `transform-style: preserve-3d`
- **Sistema de estado completo** — salva progresso da partida em memória, permitindo pausar e retomar
- **Responsivo** — funciona em desktop e mobile
- **Embaralhamento Fisher-Yates** para ordem aleatória das perguntas a cada partida

---

## 🧠 Por que esse projeto importa no portfólio?

Este projeto vai além de análise de dados: mostra capacidade de **identificar um problema real, propor uma solução criativa e executar do zero**. Conectar conhecimento técnico com necessidade real de negócio é o diferencial de um bom profissional de dados.

O game foi criado por iniciativa própria e é utilizado ativamente pelo time de Inventário do hub BRSP06.

---

## ▶️ Como Rodar

1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` no browser
3. Pronto — nenhuma instalação necessária

```bash
git clone https://github.com/Hiago-Prates/jornada-da-excelencia.git
cd jornada-da-excelencia
# Abra o index.html no seu browser
```

> Também pode ser hospedado gratuitamente no **GitHub Pages** para acesso via link direto.

---

## 📁 Estrutura do Projeto

```
jornada-da-excelencia/
│
├── index.html        ← Game completo (HTML + CSS + JS em um único arquivo)
├── imagens/          ← Capturas de tela para o README
│   ├── home.png
│   ├── cultura.png
│   └── ranking.png
└── README.md
```

---

## 👨‍💻 Autor

**Hiago Prates** — Analista Operacional | Estudante de Ciência de Dados  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hiago-prates-a3a295400)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Hiago-Prates)
