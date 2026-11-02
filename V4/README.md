# Física 3D V4

Esta versão substitui o piloto anterior e foi produzida com foco em história, atuação, câmera, ambientes e áudio — não apenas em resolução.

## Saída
- 1min55s
- 1280x720
- H.264, 24 fps
- áudio AAC estéreo
- faixa de legendas pt-BR no MP4
- 9 capítulos incorporados

## Melhorias
- Personagens Lia, Davi, Raul e Helena reconstruídos com hierarquia articulada de cabeça, torso, braços, cotovelos, mãos, quadris, joelhos e pés.
- Ambientes novos: cozinha, abstração molecular, mesa de projeto, ponte, aeroporto, cidade em apagão, ressonância magnética, laboratório e encerramento.
- Câmera com planos diferentes por cena e movimentos sutis.
- Narração e diálogos separados por personagem, com processamento de pitch, EQ, compressor e normalização.
- Música e SFX separados: copo, transição, ponte, avião, rede elétrica, MRI e pêndulo.
- Pós-produção em FFmpeg com interpolação, upscale Lanczos, color grade e sharpening.

## Referências de pipeline
Para uma evolução futura em Blender, foram pesquisados rigs/loops humanoides CC0 de Quaternius/KayKit. A biblioteca Universal Animation Library oferece 120+ clips em FBX/glTF/GLB/Blend. A V4 atual, porém, ainda usa os modelos procedurais originais porque Blender e os assets binários externos não puderam ser incorporados diretamente ao ambiente de render.

## Limites
- O render-base é 960x540/8 fps e a saída é convertida para 720p/24 fps.
- As vozes partem do sintetizador local e são tratadas no pós; ainda não equivalem a um TTS neural profissional.
- Blender não estava instalado no ambiente usado para este render.
