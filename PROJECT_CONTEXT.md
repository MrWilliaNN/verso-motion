# Contexto do projeto — Verso Motion

## Objetivo
Manter e evoluir o Verso Motion, um editor web de letras animadas para uso em igrejas, especialmente projeção durante cultos, transmissões e publicações sociais.

## Estado importado
O arquivo `index.html` foi recuperado da implantação funcional atual da Vercel (HTTP 200) e enviado ao repositório. Ele é uma aplicação autocontida em HTML, CSS e JavaScript.

## Regras para a próxima IA/desenvolvedor
1. **Não reconstrua do zero.** Primeiro leia o `index.html` inteiro e mapeie os componentes, o estado e o sistema de renderização/exportação existentes.
2. Preserve as funcionalidades que já funcionam; faça mudanças pequenas e incrementais.
3. Antes de editar, identifique como a prévia e o renderizador de exportação implementam cada animação.
4. Teste criação/edição/divisão/exclusão de cenas, salvar e carregar JSON, reprodução, tela cheia e exportação completa e por cena.
5. Não diga que uma função foi testada se não foi executada.
6. Evite dependências externas desnecessárias; a aplicação atual foi concebida como arquivo independente.
7. Não inclua tokens, senhas, chaves privadas ou credenciais no repositório.
8. Não substitua o site de produção nem altere o domínio `verso-motion.vercel.app` sem validação explícita e plano de reversão.

## Funcionalidades identificadas
- Gerenciamento de cenas (criar, editar, dividir, adicionar e excluir).
- Controles de texto, fontes, cores, destaques e animações.
- Fundos animados e prévia.
- Modo tela cheia e avanço automático.
- Player de áudio.
- Salvar/carregar projeto em JSON.
- Exportação WebM completa e exportação de cada cena separadamente.

## Limitações conhecidas
- O áudio do player não está incorporado ao vídeo exportado.
- O renderizador de exportação pode não reproduzir exatamente todos os efeitos da prévia; investigar antes de prometer paridade.

## Publicação
Produção atual: https://verso-motion.vercel.app

O projeto de Vercel ligado ao GitHub deve ser tratado como ambiente novo até ser testado. Prefira primeiro uma implantação de preview; só depois de confirmar o resultado avalie a ligação ao domínio de produção.
