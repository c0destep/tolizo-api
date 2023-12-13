### Passo 1: Faça um fork do repositório

- Acesse o repositório principal do seu projeto no GitHub.
- Clique no botão "Fork" no canto superior direito da página. Isso criará uma cópia do seu projeto na sua conta do
  GitHub.

### Passo 2: Clone o repositório para sua máquina local

- Abra o terminal ou prompt de comando.
- Use o comando `git clone` seguido pelo URL do repositório fork que você acabou de criar. Isso fará o download do
  repositório para sua máquina local:

```bash
git clone https://github.com/seu-usuario/nome-do-seu-projeto.git
```

### Passo 3: Crie uma branch para suas alterações

- Mude para o diretório do projeto clonado:

```bash
cd nome-do-seu-projeto
```

- Crie uma nova branch para suas alterações:

```bash
git checkout -b nome-da-sua-branch
```

### Passo 4: Faça suas alterações

- Execute o comando do Composer para instalar as dependências:

```bash
composer install
```

- Faça as alterações necessárias no código-fonte do seu projeto.
- Adicione, modifique ou remova arquivos conforme necessário.

### Passo 5: Faça commit das suas alterações

- Verifique as mudanças realizadas no seu repositório local:

```bash
git status
```

- Adicione os arquivos modificados para o próximo commit:

```bash
git add nome-do-arquivo-modificado
```

- Faça um commit com uma mensagem descritiva e usando commits semânticos:

```bash
git commit -m "feat: Adiciona nova funcionalidade incrível"
```

### Passo 6: Envie as alterações para o GitHub

- Envie suas alterações para o seu repositório no GitHub:

```bash
git push origin nome-da-sua-branch
```

### Passo 7: Crie um Pull Request (PR)

- Vá para o repositório original no GitHub (aquele que você fez o fork inicialmente).
- Clique no botão "New pull request".
- Escolha a sua branch como base para a comparação.
- Adicione um título e uma descrição detalhada para explicar suas alterações.
- Clique em "Create pull request" para abrir o Pull Request.

### Passo 8: Aguarde a revisão e aceitação

Aguarde a revisão dos mantenedores do projeto. Eles poderão fazer comentários, solicitar mudanças ou mesclar suas
alterações ao projeto principal.
