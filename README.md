# Compilador_L
Compilador funcional para a linguagem fictícia "L" desenvolvido para a matéria de Compiladores da PUC-MG.
Todas as especificações da linguagem podem ser encontradas no documento **Especificações**. A especificação completa da linguagem encontra-se em **Especificações/tp_final.pdf**

## Etapas do Processamento

**1 - Análise Léxica:** todos os tokens encontrados no programa fonte serão encontrados e validados, respeitando as regras impostas pela linguagem e criadas por um autômato finito determinista, especificado em **automato.png**.

**2 - Análise Sintática:** validação da ordem de comandos prevista pela gramática da linguagem, especificada no documento **Esquema_de_Tradução.txt**.

**3 - Análise Semântica:** adição do esquema de tradução à gramática da linguagem como a verificação de unicidade de identificadores, correspondência de tipos, atribuição de valores a constantes. A especificação do analisador semântico encontra-se no documento **Esquema_de_Tradução.txt**.

**4 - Geração de código:** com a leitura do programa fonte, seus comandos são traduzidos para linguagem de máquina, gerando um arquivo **saida.asm**. A documentação da geração de código está especificada no documento **GeraçãoCódigo/GC64.pdf** onde utilizaremos a arquitetura 80x86/x64 do assembly.
