# Aplicativos Nescessarios

- HxD (Editor Hexadecimal como você já viu)
- Uma ISO (Acho que isso è meio Obvio)


# God of War I & II - Cutscenes Puláveis

## God of War I - Sempre Ligado
- **Offset na ISO:** 000117660
- **Velocidade do Skip (Rápido):** 00011766C
- **Instrução em MIPS:** `24 00 40 10` (Beq)
- **Duração no ELF:** 8A661

**Como aplicar:** Zerar os 4 bytes dos offsets indicados (`00 00 00 00`)

## God of War II - Sempre Ligado
- **Offset na ISO:** FF2F3F18
- **Velocidade do Skip (0 OFFSET):** FF2F3F24
- **Instrução em MIPS:** `24 00 40 10` (Beq)
- **Duração HXD:** 92718

**Como aplicar:** Zerar os 4 bytes dos offsets indicados (`00 00 00 00`)
