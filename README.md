# 🎬 AI Transcriber Studio

**Transcreva vídeos e compacte arquivos no seu computador — de graça, sem anúncios e sem enviar nada para a internet.**

### ⬇️ [**BAIXAR PARA WINDOWS**](../../releases/latest) ⬅️ clique aqui

*Windows 10 ou 11 (64 bits). Não precisa instalar mais nada — nem Python, nem FFmpeg, nem contas.*

---

## O que o programa faz

### 📝 Transcrever
Arraste um vídeo ou áudio e receba o texto completo em **4 formatos**:

| Arquivo | Para que serve |
|---|---|
| `.txt` | Texto com o tempo de cada fala: `[00:00:12] Olá pessoal...` |
| `.srt` | Legenda pronta para o YouTube, VLC, Premiere, CapCut |
| `.vtt` | Legenda para sites e players web |
| `.json` | Dados estruturados para programadores |

Também aceita **link do YouTube** — cole o endereço e o programa baixa e transcreve.

### 🗜️ Compactar
Reduza o tamanho de **vídeos e fotos** perdendo o mínimo de qualidade, em 3 níveis
(Alto, Médio e Baixo). Antes de começar, o programa mostra a **estimativa do
tamanho final**.

Exemplos reais medidos:

- Vídeo de **2,6 GB → 134 MB** (95% menor)
- Vídeo de **372 MB → 74 MB** (80% menor)
- Foto de **11 MB → 0,4 MB** (97% menor)

O arquivo original **nunca é apagado ou alterado** — o compactado é salvo ao lado,
com `_compactado` no nome.

---

## Como instalar

1. Clique em **[BAIXAR PARA WINDOWS](../../releases/latest)** e baixe o arquivo `.exe`
2. Dê dois cliques no arquivo baixado
3. O Windows vai mostrar um aviso azul: **"O Windows protegeu o seu PC"**
   → clique em **"Mais informações"** e depois em **"Executar assim mesmo"**
4. Siga a instalação normalmente e abra o programa pelo atalho criado

> **Por que aparece esse aviso?** Porque o programa é novo e não tem uma
> assinatura digital paga (custa centenas de dólares por ano). O aviso não
> significa vírus — o Windows mostra isso para qualquer programa pouco conhecido.

---

## Perguntas frequentes

**Meus vídeos são enviados para algum servidor?**
Não. Todo o processamento acontece no seu computador. A internet só é usada em
duas situações: baixar links do YouTube (se você usar) e baixar o "cérebro" da
inteligência artificial na primeira transcrição.

**Preciso de internet para usar?**
Para **compactar**, não — funciona offline desde o primeiro uso. Para
**transcrever**, o programa baixa o modelo de IA uma única vez (com barra de
progresso); depois disso, funciona offline para sempre.

**Funciona sem placa de vídeo?**
Sim, funciona no processador. Se você tiver uma placa **NVIDIA**, o programa
oferece ativar a aceleração nas configurações (fica até 5× mais rápido).

**Quantos idiomas reconhece?**
Mais de 90, com detecção automática — incluindo português brasileiro.

**É pago? Tem anúncio? Tem limite?**
Não, não e não. Sem cadastro, sem assinatura, sem limite de arquivos ou de
duração.

**Posso transcrever vários vídeos de uma vez?**
Sim. Arraste vários arquivos e eles entram em uma fila automática.

---

## Requisitos

- Windows 10 ou 11 (64 bits)
- ~2 GB de espaço livre em disco
- 8 GB de memória RAM (recomendado)
- Placa NVIDIA — **opcional**, apenas para acelerar

---

*Feito com Electron, React e Faster-Whisper. Se encontrar algum problema, abra uma
[issue](../../issues) descrevendo o que aconteceu.*
