# MyDeck — MVP de Flashcards (V16)

Versão demonstrativa do projeto MyDeck, com interfaces para alunos e professores.

## Abrir o protótipo
- `index.html`: entrada para testar os dois perfis.
- `aluno.html`: interface do aluno.
- `professor.html`: interface do professor.

## Publicar no GitHub Pages
1. Crie um repositório público no GitHub, por exemplo `mydeck`.
2. Adicione os arquivos desta pasta **extraída** à raiz do repositório, usando `Add file` → `Upload files`.
3. Confirme em `Commit changes`.
4. Em `Settings` → `Pages`, escolha `Deploy from a branch`.
5. Selecione `main` e `/(root)` e clique `Save`.
6. Quando a publicação terminar, compartilhe o endereço mostrado em `Settings` → `Pages`.

Endereço típico: `https://SEU-USUARIO.github.io/mydeck/`

## Limitações atuais
- O login e o código de verificação são **demonstrativos**.
- Os dados são armazenados localmente no navegador (`localStorage`).
- Não existe sincronização entre computadores, contas ou integrantes do grupo.
- Esta versão não está ligada ao Firebase.
- Não use dados pessoais reais durante a demonstração.

## Próximo passo técnico
Conectar Firebase Authentication e Cloud Firestore, modelar usuários, turmas,
decks, tags, matrículas e resultados, e implementar regras de segurança.

**Segurança:** nunca publique chaves privadas, senhas, contas de serviço
nem arquivos `.env` com segredos no GitHub.
