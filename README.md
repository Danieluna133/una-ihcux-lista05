# una-ihcux-lista05
- Explicação em resumo
  
<img width="899" height="107" alt="image" src="https://github.com/user-attachments/assets/8e3476ff-a812-472e-af89-6833471b5c45" />


Como apliquei as Heurísticas de UX no meu código
Para deixar o sistema mais amigável e fácil de usar, foquei em três pontos principais baseados nas Heurísticas de Nielsen:

1. Visibilidade do Status do Sistema (O usuário sempre sabe o que está acontecendo)
Em vez de deixar o programa "congelado" enquanto calcula, adicionei feedbacks visuais como a mensagem de conexão e os pontinhos de carregamento. Isso evita que o usuário ache que o software travou. É como uma barra de progresso simples, que dá segurança de que o processo está rolando.

2. Prevenção de Erros (Evitando problemas antes que eles aconteçam)
Programas costumam fechar quando o usuário digita algo errado (como uma letra no lugar de um número). Usei um tratamento de erro (try-catch) para capturar esses deslizes. Em vez de uma tela preta cheia de código técnico, o usuário recebe um aviso amigável explicando exatamente o que aconteceu e como corrigir.

3. Estética e Design Minimalista (Foco no que importa)
O visual do console foi limpo para não confundir o usuário. Usei cores diferentes para separar o que é título, o que é o resultado final e o que é um erro. O uso de linhas separadoras ajuda a organizar a tela, garantindo que o valor convertido (a informação principal) salte aos olhos imediatamente.
