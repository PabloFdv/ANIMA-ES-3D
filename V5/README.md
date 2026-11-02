# Física 3D V5 — pipeline por skills

A V5 foi reconstruída a partir das regras encontradas em skills comunitárias de Blender, Three.js, Remotion e explainer 3D.

## Mudanças
- Aproximadamente 30 planos em 180 s, em vez de poucas cenas longas.
- Personagens com hierarquia procedural: pelve, coluna, pescoço, cabeça, ombro, cotovelo, mão, quadril, joelho e pé.
- Rosto com olhos, pupilas, sobrancelhas, boca e variações simples de fala/expressão.
- Estética cartoon 3D assumida, evitando o semi-realismo estranho da V4.
- Planos de detalhe, médios, reação e ambientes distintos.
- Visualizações de cargas na ponte, fluxo de ar, campo magnético, GPS/tempo e pêndulo.
- Áudio reescrito, cinco vozes separadas, EQ/compressão/normalização, trilha e SFX.
- MP4 com H.264, AAC estéreo, legenda pt-BR e capítulos.

## Skills usadas como referência
- EL4CTEO/blender-skills: character rigging, facial shape keys, animation, lighting/lookdev, rendering.
- artemnovitckii/claude-animation-skills: explainer 3D, cortes de 2–4 s, captions curtas e review de stills.
- OpenSenseNova/SenseNova-Skills sn-code-video: render determinístico, áudio separado e verificação do MP4.
- Remotion skills: composição/captions/pós por código.
- ProkStudio blender rigging-and-animation: joint placement, blocking → spline → polish e QA.

## Limites
Este render não foi feito no Blender porque o Blender não estava instalado no ambiente de execução. A V5 aplica os princípios dessas skills no motor procedural disponível. Portanto, ainda não tem mesh humano orgânico/retopologizado, Rigify completo, ARKit 52 ou Cycles. A voz continua baseada em sintetizador local processado e não equivale a TTS neural de estúdio.
