# Central de Operação

Painel de gestão de clientes, rotina diária e financeiro. Uma única página, sem servidor e sem build.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub.
2. Envie os arquivos `index.html` e `README.md` para a raiz do repositório.
3. Vá em **Settings → Pages**.
4. Em *Source*, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`. Salve.
5. Em um ou dois minutos o painel fica no ar em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

No celular, abra esse endereço e use "Adicionar à tela de início". Ele passa a abrir em tela cheia, como um aplicativo.

## Onde ficam os dados

Os dados são gravados no `localStorage` do navegador, no seu aparelho. Nada é enviado para o GitHub nem para qualquer servidor — o repositório guarda apenas o código da página.

Consequências práticas:

- Cada navegador e cada aparelho mantém a sua própria base. O que você registra no notebook não aparece no celular.
- Limpar dados de navegação do site apaga os registros.
- Use o botão **Backup** com frequência: ele baixa um arquivo `.json` com tudo e restaura em qualquer aparelho.

Para levar os dados de um aparelho para outro: **Backup → Baixar backup** no primeiro, **Backup → Restaurar arquivo** no segundo.

## Atualizar o painel

Substitua o `index.html` no repositório. O GitHub Pages republica sozinho e os seus dados continuam intactos, porque ficam no navegador e não no arquivo.
