# agrinho-2026
🌬️ Jogo de Energia Eólica - Agrinho 2026
Tema: Sustentabilidade e Energia Limpa no Campo
Este é um jogo educativo interativo que simula a geração de energia limpa em uma fazenda usando turbinas eólicas. O jogador controla a velocidade do vento para otimizar a produção de energia e abastecer a fazenda de forma sustentável.

🎯 Objetivo do Jogo
O objetivo é acumular 100% de energia limpa para abastecer a fazenda, gerando energia de forma eficiente com turbinas eólicas. O jogador deve manter o vento dentro da faixa ideal de 10 km/h a 35 km/h para que as turbinas funcionem corretamente.

🕹️ Como Jogar
Controle do vento: Mova o mouse horizontalmente para aumentar ou diminuir a velocidade do vento.
Janela ideal de vento:
Muito fraco (<10 km/h): turbinas paradas
Ideal (10–35 km/h): produção máxima de energia
Muito forte (>35 km/h): freio de emergência das turbinas ativado
Progresso: A energia acumulada é mostrada em uma barra de progresso.
Conquista: Quando atingir 100% de energia, a tela de vitória será exibida.
Reiniciar o jogo: Pressione a tecla ESPAÇO após a vitória para jogar novamente.

🎨 Elementos Visuais
Cenário dinâmico: O céu muda de cor de acordo com a velocidade do vento.
Fazenda e natureza: Inclui montanhas, grama, e uma casa que acende suas janelas quando há energia.
Turbinas eólicas: Turbinas animadas com pás giratórias, velocidade dependente do vento.
Interface: Mostra velocidade do vento, status do sistema e barra de energia acumulada.

⚙️ Tecnologias Utilizadas
Linguagem: JavaScript
Biblioteca: p5.js – para gráficos, animação e interação.

💻 Executando o Jogo
Certifique-se de ter um navegador moderno (Chrome, Firefox ou Edge).
Baixe ou clone este repositório.
Abra o arquivo index.html ou execute em um ambiente que suporte p5.js.
O jogo começará automaticamente. Controle o vento com o mouse para gerar energia.

📝 Estrutura do Código
setup() → inicializa o canvas.
draw() → loop principal do jogo: atualiza cenário, turbinas e interface.
Funções de desenho:
desenharCenario()
desenharFazenda()
desenharAerogerador()
desenharInterface()
desenharVitoria()
Variáveis principais:
anguloRotacao → controle de rotação das pás
energiaGerada → acumula energia produzida
metaEnergia → define objetivo de energia para vencer
jogoConcluido → indica se o jogo terminou

🌱 Educação Ambiental
Este jogo tem caráter educativo, ensinando conceitos básicos de:
Energia eólica
Sustentabilidade no campo
Produção de energia limpa e renovável
É ideal para escolas e atividades de conscientização ambiental.

📌 Autor
Agrinho 2026 – Projeto de educação e tecnologia voltado para a sustentabilidade no meio rural.
