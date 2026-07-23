Tap Dance (aba "Tap Danc" no Vial)

A ideia é simples: a mesma tecla física faz coisas diferentes dependendo de quantas vezes (ou como) você aperta ela, dentro de uma janela curta de tempo.
Cada Tap Dance tem até 4 comportamentos configuráveis:
•	On tap (1 toque rápido) → ação A
•	On hold (segurar sem soltar) → ação B
•	On double tap (2 toques rápidos) → ação C
•	On tap + hold (tocar e depois segurar) → ação D
Exemplo prático
Imagine configurar a tecla Caps Lock assim:
•	Tap único → Escape
•	Segurar → ativa a Layer 1
•	Duplo tap → Caps Lock de verdade
Assim você recupera uma tecla física pra fazer 3 coisas diferentes, sem gastar 3 posições separadas no teclado.
Como configurar no Vial
1.	Clique na aba "Tap Danc" (Tap Dance)
2.	Escolha um número de slot (ex: TD(0), TD(1), etc.)
3.	Preencha os campos "On tap", "On hold", "On double tap", "On tap+hold" com as ações desejadas
4.	Vá até o layout do teclado (aba Keymap) e coloque essa tecla TD(0) na posição física que você quiser usar
________________________________________
Combos (aba "Combo" no Vial)

A ideia aqui é: apertar 2 ou mais teclas ao mesmo tempo produz um resultado diferente do que cada uma faria sozinha.
Exemplo prático
•	Apertar A + S juntos → dispara Escape
•	Apertar J + K juntos → dispara Enter
•	Apertar D + F juntos → ativa um Layer específico
Isso é muito usado em teclados pequenos/split para conseguir teclas extras sem precisar de mais posições físicas — bem popular pra Escape, Enter, Tab, símbolos, etc.
Como configurar no Vial
1.	Clique na aba "Combo"
2.	Escolha um slot vazio
3.	Marque as 2 (ou mais) teclas físicas que, juntas, vão disparar o combo (usando o teclado virtual desenhado ali)
4.	Defina qual ação/tecla deve ser produzida quando esse combo for detectado

Detalhe importante — o tempo
Existe um "tempo limite" (chamado timeout, geralmente uns 150ms por padrão) dentro do qual as teclas precisam ser apertadas quase juntas para o combo ser reconhecido. Isso fica configurável na aba "QMK Setting", procurando por algo relacionado a "Combo term" ou parecido.

