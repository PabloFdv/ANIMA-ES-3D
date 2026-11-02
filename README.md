# E se a física não existisse?
Documentário 3D interativo sobre as leis da física e as consequências da perda de conhecimento científico. Uma experiência autoral, em português, construída com **Three.js**, sem modelos ou imagens externas.

## Como assistir
Abra [index.html](./index.html) com um servidor local (necessário para módulos JavaScript). Com Python: `python -m http.server 8000`, depois abra `http://localhost:8000`. Com VS Code, use Live Server. É necessária conexão para obter Three.js e a fonte do CDN.

## Publicação no GitHub Pages
Em **Settings → Pages → Build and deployment**, escolha **Deploy from a branch**, branch **main**, pasta **/(root)**. O site ficará disponível no endereço de Pages que o GitHub apresentar após publicar; a configuração deve ser ativada manualmente, se ainda não estiver habilitada.

## Recursos
- 10 capítulos, aproximadamente 7 min e 26 s, com cenas procedurais: Terra, desagregação metafórica, cidade, ponte, avião, distribuição elétrica, ressonância magnética, satélite/GPS, laboratório e final.
- Reprodução, pausa, barra de progresso, navegação por capítulos, legendas, velocidades 1×/1,25×/1,5×, fullscreen e teclado.
- Narração em português-BR por **SpeechSynthesis**, dependente do navegador e das vozes instaladas. Pode haver silêncio ou interrupções em alguns dispositivos.
- Trilha ambiente sintetizada por Web Audio. Nenhuma música externa.
- Botão de gravação **WebM** em tempo real com trilha ambiente; a voz do sistema **não é capturada**.
- Design responsivo e notas científicas em cada capítulo.

## Ciência e limitações
A ausência total de leis físicas não é um cenário simulável nem possui previsões cientificamente fundamentadas: os efeitos visuais são metáforas. O restante da narrativa imagina o desaparecimento de conhecimento científico, **sem** alterar as leis naturais. O documentário não reproduz simulações de engenharia quantitativas; cenas de risco são dramatizações ilustrativas.

Referências:
- [NASA: What is Lift?](https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/what-is-lift/)
- [NIST: How Does an MRI Machine Work?](https://www.nist.gov/how-do-you-measure-it/how-does-mri-machine-work)
- [NASA: Time and Relativity](https://spaceplace.nasa.gov/time-travel/en/)
- [Three.js manual](https://threejs.org/manual/#en/installation)

## Arquivos
- `index.html`: estrutura, interface e import map.
- `styles.css`: identidade visual e responsividade.
- `app.js`: cena 3D, capítulos, player e áudio.

## Qualidade e revisão
O código foi criado no GitHub através da conexão da conta. **Não houve execução de testes de navegador ou testes em dispositivos reais neste ambiente.** Deve-se verificar WebGL, disponibilidade de voz, gravação WebM, estabilidade em celulares e links antes de distribuir publicamente.
