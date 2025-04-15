# Documentação do codigo

Diretório da Documentação de Estilos CSS – Projeto Final Este diretório contém todos os estilos do projeto, tornando-o modular e claro por meio da metodologia B.E.M. Específica grade e otimizada para manutenção e escalabilidade. Metodologia: B.E.M Estrutura: bloco – componente principal bloco bloco__elemento – partes do bloco bloco bloco–modificador – vários templates

♿ Accessibilidade

Foco visível: todos os elementos interativos têm o :focus personalizado com um outline.

Unidade relativas: rem é usado para permitir o escalonamento da fonte.

Cores acessíveis: contraste adequado que segue os padrões WCAG 2.1 no nível AA.

Nenhum conteúdo é escondido com display: none, exceto onde semanticamente correto.

O.visually-hidden é adotado para manter os textos úteis apenas para os leitores de tela, sendo opcional a sua utilização.

🚀 Performance

As folhas de estilos de cada componente estão divididas em carregamentos futuros com base no demanda.

Não são levados em conta os seletores CSS longos para otimizar o cube-parsing e a renderização do DOM.

A minificação automática é solicitada na build com as ferramentas cssnano.

As variáveis CSS são recomendadas para o reuso facilitado e, consequentemente, a redução da redundância.

Os estilos críticos são pré-carregados com a tag para desencadear a execução de algumas propriedades antes de o navegador chegasse e solicitá-lo no DOM.
