# 🎮 2D Platformer Game (Unity)

Este projeto consiste em um jogo de plataforma 2D desenvolvido na Unity Engine, utilizando Tilemap, física 2D e scripts em C# para implementação de mecânicas clássicas de jogos de plataforma.

O projeto foi desenvolvido com fins acadêmicos, com foco no estudo de sistemas de movimentação, colisão, animação, coleta de itens e gerenciamento de estados de jogo.

# 🧱 Tecnologias Utilizadas
Unity Engine (2D)
C# (MonoBehaviour)
Tilemap System (Unity)
Unity Physics 2D
Animator Controller
# ⚙️ Sistemas Implementados
🕹️ Player Controller
Movimentação horizontal baseada em input do teclado
Sistema de pulo com controle de força
Implementação de double jump (pulo duplo)
Detecção de chão via colisão (ground check)
# 🎞️ Sistema de Animação
Integração com Animator Controller
Estados implementados:
Idle (parado)
Run (correndo)
Jump (pulando)
Transições baseadas em parâmetros de movimento
# 🧩 Tilemap Level Design
Construção de fases utilizando o sistema Tilemap da Unity
Colisão automática com Tilemap Collider 2D
Organização modular de cenários
# $ Sistema de Coleta (Coins/Pickups)
Objetos coletáveis com trigger collider
Incremento de pontuação ao coletar moedas
Remoção do objeto após coleta
# 💀 Sistema de Morte e Respawn
Detecção de colisão com áreas de morte (death zones)
Reset da posição do jogador em ponto de spawn
Reinicialização de estado do player
# 🎮 Game Manager / UI Manager
Controle básico de fluxo do jogo
Gerenciamento de estados (jogando / reiniciando)
Atualização de interface (UI)
# 🎯 Controles
A / D ou Setas: movimentação horizontal
Espaço: pulo
Espaço no ar: pulo duplo
R: reiniciar fase (se habilitado)
# ▶️ Como Executar
Clonar ou baixar o repositório
Abrir o projeto na Unity (versão compatível com 2D)
Localizar a cena principal do jogo
Executar a cena com o botão Play
# 🧪 Problemas Conhecidos
Algumas moedas podem não ser coletadas corretamente caso:
O collider não esteja configurado como Trigger
Tags/layers não estejam corretamente atribuídos
Possíveis inconsistências em cenas secundárias devido à configuração de prefabs
# 📚 Aprendizados do Projeto

Este projeto permitiu a aplicação prática de conceitos fundamentais de desenvolvimento de jogos, incluindo:

Programação de mecânicas de movimento em 2D
Sistema de colisões e triggers na Unity
Estruturação de scripts em C#
Uso de Animator Controller para animações
Implementação de lógica de coleta e respawn
Organização de cenários com Tilemap
# 📌 Observação Final

Este projeto tem caráter acadêmico e serve como base para evolução futura, podendo ser expandido com:

Sistema de inimigos com IA simples
Menu inicial e sistema de fases
Sistema de pontuação global
Power-ups e habilidades especiais

# link youtube
https://youtu.be/6jbJXkObfFo
