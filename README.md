# Compilador_L
Este projeto é uma recriação funcional de um compilador para uma linguagem de programação fictícia.
Todas as especificações da linguagem podem ser encontradas no documento tp_final.pdf.
O Compilador conta com as seguinte etapas:

1 - Análise Léxica: todos os tokens encontrados no programa fonte serão encontrados e validados, respeitando as regras impostas pela linguagem e criadas por um autômato.

2 - Análise Sintática: validação da ordem de comandos prevista pela gramática da linguagem, especificada no documento Esquema_de_Tradução.txt.

3 - Análise Semântica: adição do esquema de tradução à gramática da linguagem como a verificação de unicidade de identificadores, correspondência de tipos, atribuição de valores a constantes. A especificação do analisador semântico encontra-se no documento Esquema_de_Tradução.txt.

4 - Geração de código: com a leitura do programa fonte, seus comandos são traduzidos para assembly, gerando o arquivo saida.asm.
