# Quiz dos chalés — versão final

Esta versão final consolida o quiz aprovado e as indicações de leitura: 18 livros principais e 14 alternativas jovens, com os hiperlinks extraídos dos títulos no DOCX. A beta 1.1 permanece salva separadamente em `quiz-chales-beta-1.1.zip` como ponto de retorno.

Esta versão foi refeita com a identidade visual enviada em `identidade_visual_quiz_imagens.zip`. A abertura usa a paisagem noturna e o emblema laranja do Acampamento Meio-Sangue fornecido posteriormente; as perguntas e o desempate usam pergaminho; o resultado aplica a paleta do chalé e mostra seu banner ilustrado. Os 18 banners em `assets/banners/` foram reconstruídos em alta resolução com base nos painéis em `reference/`, preservados sem alteração. Os nomes e números dos chalés são texto vivo da interface.

Os 18 banners da versão final usam WebP para carregar mais rápido na web. As dimensões e proporções foram preservadas; os PNGs originais continuam no pacote beta 1.1 e no arquivo `quiz-chales-final-antes-otimizacao.zip`.

A assinatura discreta da Livraria Leitura aparece no rodapé da abertura e do resultado. A arte branca da logo foi extraída do guia de aplicação da marca fornecido no computador.

## Abrir no navegador

1. Extraia o ZIP inteiro para uma pasta.
2. Dê dois cliques em `index.html`.

Não é necessário instalar Node.js, executar comandos ou iniciar servidor. O quiz abre localmente e também pode ser publicado como site estático. Os links para os produtos na Livraria Leitura exigem internet quando acionados. Mantenha as pastas `assets/` e `reference/` ao lado do HTML.

## O que está incluído

- As 13 perguntas, a matriz de pontuação e os 18 resultados oficiais do pacote de dados anterior.
- Desempate por pontuação total, quantidade de `+3`, perguntas estruturais e pergunta final dinâmica quando necessário.
- Temas cromáticos dos 18 chalés, aplicados somente após a revelação, com cabeçalho centralizado no resultado.
- Moldura de pergaminho em nove partes para manter os ornamentos proporcionais quando a pergunta ou o resultado ocupa mais altura; ilustrações exibidas com recorte proporcional, sem esticar.
- Cabeçalhos e ação de refazer centralizados; parágrafos longos alinhados à esquerda para leitura confortável também no celular.
- Fontes locais e imagens incluídas no pacote. A paisagem de abertura e a base de pergaminho foram criadas para adaptar a composição das referências ao conteúdo real do quiz; o selo vem das imagens fornecidas e os banners são reconstruções detalhadas dessas referências.
- Código-fonte legível em JavaScript e CSS, com os dados originais também em `source-data/`.
- Recomendações editoriais em `recommendations.js`, separadas da pontuação: título, autor, ISBN, URL e justificativa por chalé.
- As alternativas jovens de Ares, Íris, Nêmesis e Nike mantêm o status editorial apenas nos dados internos, sem aviso na interface.
- As 32 indicações exibem imagens locais das capas associadas aos ISBNs do briefing, sem esticar ou recortar as imagens. Os cartões mantêm o pergaminho, os ornamentos e as cores do chalé. As URLs de origem estão em `assets/covers/sources.json`; a edição do produto deve ser conferida na página da Leitura.
- Nenhuma classificação etária numérica ou aviso de conteúdo foi inventado; esses dados podem ser adicionados depois de verificação editorial.

Os arquivos PNG de `reference/` são referências visuais fornecidas para este projeto. As imagens geradas em `assets/` são componentes da interface desta versão.
