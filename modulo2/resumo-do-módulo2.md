## Notas de conteúdo do módulo 2

### Repositório
- **Criar diretório local [pasta]**
    
    No git bash:
    
    *mk dir curso-git-e-github* 
    
    *cd [nomedodir]*
    
    *code .*
    
- **Conectar o repositório local ao remoto**
    
    Após criar um repositório no Github, é necessário adicionar a origem remota no repositório local: 
    
    *remote - v* → confirma se já existe uma origem remota
    
    *git remote add origin [nomedaorigem]* → copiado do Github
    
- **Clonar um repositório existente**
    
    Após criar um novo repositório, dentro dele é possível executar o seguinte comando: 
    
    git clone [endereço do repositório remoto]
    
- **Atualizar um repositório forkado com o projeto de origem**
    
    Pelo Github → No repositório forkado, é possível comparar mudanças e criar uma pull request. Criada, é possível usar o merge.
    
    Pelo terminal → *git remote add upstream [caminhodaorigem]*
    
    *git fetch upstream*
    
    *git rebase upstream/master*
