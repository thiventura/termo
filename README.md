# Termo
Criando uma IA para resolver o jogo Termo

Jogo: https://term.ooo/

A ideia do algoritmo é:
1. Obter a lista de todas as palavras com 5 letras da língua portuguesa
2. Dar uma peso para cada palavra, considerando sua classe gramatical, popularidade (o quanto cada uma aparece em textos) e caracteres existentes (alguns caracteres aparecem mais que outros, então é melhor utilizá-los)
3. Selecionar uma das palavras usadas como primeiro palpite
4. Filtrar as possíveis novas palavras dependendo dos feedbacks das tentativas anteriores (letras certas, letras existentes mas na posição errada e letras que não aparecem na resposta)
5. Das palavras possíveis, verificar qual tem o maior peso e escolhê-la como próximo palpite
6. Se errar, repita a partir do passo 4
