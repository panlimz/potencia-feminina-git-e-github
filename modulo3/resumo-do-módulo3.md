## Notas de conteúdo do módulo 3

### Branchs
São eparações de código, que possibilitam trabalho em grupo de forma independente.

- **Develop** é a branch para uso em tempo de desenvolvimento. Depois de testar o código localmente, ele é disponibilizado nesse ambiente;
- **Homolog** é o ambiente onde o código é enviado após o desenvolvimento para mais testes e validação;
- **Master** é branch principal de todo projeto, o código disponibilizado aqui são os códigos para produção (disponibilizados ao público).

*git branch →* lista as branchs disponíveis no repositório

**Criar/alterar branch pelo terminal**

*git checkout -b [nomedabranch] → a branch é criada e o ambiente setado para essa branch automaticamente*

*git checkout [nome da branch] →* direciona os comandos pra branch nomeada

**Criar/alterar branch pelo Github**

Na parte superior esquerda dentro do repositório, no botão onde tem a branch principal, basta escrever o nome da nova branch.

*git push —set-upstream origin [nomedabranch] →* sincroniza a branch criada localmente com o repositório remoto

**Merge local**

*git checkout [nomedabranch]
git pull*

*git merge [nomedabranch]* 

*git push*
