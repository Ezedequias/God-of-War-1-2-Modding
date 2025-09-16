# Aplicativos Nescessarios

- HxD (Editor Hexadecimal como você já viu)
- Uma ISO (Acho que isso è meio Obvio)


# God of War I & II - Cutscenes Puláveis (Sempre Ligado)

## God of War I
- **Offset na ISO:** 000117660
- **Velocidade do Skip (Rápido):** 00011766C
- **Instrução em MIPS:** `24 00 40 10` (Beq)
- **Duração no ELF:** 8A661

<img width="913" height="688" alt="GitHuub" src="https://github.com/user-attachments/assets/9953084e-4aee-47f2-887b-d22822058da6" />




- Em vermelho é o que faz realmente o skip, em vermelho, é um loop que vamos quebrar colocando Zeros (00 00 00 00)
- Isso fará com que seu jogo naturalmente tenha a opção de pular cenas e ira pular rápido, parecido com a versão de PS3

**Como aplicar:** Zerar os 4 bytes dos offsets indicados (`00 00 00 00`)

## God of War II 
- **Offset na ISO:** 00011F718
- **Velocidade do Skip (0 OFFSET):** 00011F724
- **Instrução em MIPS:** `24 00 40 10` (Beq)
- **Duração HXD:** 92718 (Correto, Versão USA)

**Como aplicar:** Zerar os 4 bytes dos offsets indicados (`00 00 00 00`)
