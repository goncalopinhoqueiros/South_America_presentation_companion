ATUALIZAÇÃO DO WEBSITE — NOVA APRESENTAÇÃO + FIGURA S8

Este pacote substitui a apresentação anterior pela nova versão PDF de 11 diapositivos, atualiza as 11 imagens usadas no visualizador e corrige/acrescenta a Figura S8 na secção de Resultados suplementares.

CONTEÚDO
- index.html: HTML atualizado. Mantém o layout e as descrições existentes, adaptadas à nova sequência de 11 diapositivos. Corrige o erro JavaScript na lista de figuras suplementares, acrescenta o cartão da Figura S8 e usa o nome exato figure-S8.png.
- presentation.pdf: nova apresentação (11 páginas).
- assets/: imagens dos 11 diapositivos extraídas do novo PDF.
- supplementary/: Figuras S1–S8, incluindo a nova Figura S8.

COMO ATUALIZAR O GITHUB
1. Descompacte este ZIP.
2. No repositório, substitua index.html e presentation.pdf pelos ficheiros deste pacote.
3. Atualize a pasta assets com os 11 ficheiros slide-01.jpg a slide-11.jpg.
4. Atualize a pasta supplementary com os oito ficheiros figure-S1.png a figure-S8.png.
5. Apague os ficheiros antigos assets/slide-12.jpg e assets/slide-13.jpg, se ainda existirem. Não são usados na nova apresentação.
6. Faça Commit changes na branch main.
7. Aguarde a publicação e atualize o website com Ctrl+F5.

NOTA: Não substitua o conteúdo da pasta supplementary por apenas a Figura S8: o website continua a usar as Figuras S1–S7.
