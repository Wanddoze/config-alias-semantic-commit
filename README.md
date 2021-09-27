# config-alias-semantic-commit


# Instalação
 - Baixar [.gitconfig](https://github.com/Wanddoze/config-alias-semantic-commit/blob/main/.gitconfig).
 - Adicionar a nova configuração  utilizando commando ``git config --global -e``
 - Alterar o campo Email e User do .config costumizado
 - Fechar e Abrir terminal
 
Agora você terás estes alias disponiveis lá:
   ```bash
commit-style = "!f() { git commit -m \"style ${1}\"; }; f"                 #style melhorar a estrutura/formato do código;
commit-feature = "!f() { git commit -m \"feature ${1}\"; }; f"               #feature incluir nova funcionalidade/código;
commit-perf = "!f() { git commit -m \"perf ${1}\"; }; f"                  #perf melhorar a performance;
commit-leak = "!f() { git commit -m \"leak ${1}\"; }; f"                  #leak memory leaks;
commit-doc = "!f() { git commit -m \"doc ${1}\"; }; f"                   #doc escrever alguma documentação;
commit-log = "!f() { git commit -m \"log ${1}\"; }; f"                   #log adicionar log na aplicação;
commit-fix = "!f() { git commit -m \"bug ${1}\"; }; f"                   #bug corrigir um bug;
commit-fix-ci = "!f() { git commit -m \"fix-ci ${1}\"; }; f"                #fix-ci corrigir uma build no CI;
commit-tests = "!f() { git commit -m \"tests ${1}\"; }; f"                 #tests adicionar testes;
commit-deps-up = "!f() { git commit -m \"deps-up ${1}\"; }; f"               #deps-up upgrade em dependências;
commit-deps-down = "!f() { git commit -m \"deps-down ${1}\"; }; f"             #deps-down downgrade em dependências;
commit-fix-lint = "!f() { git commit -m \"fix-lint ${1}\"; }; f"              #fix-lint remover problemas com linter;
commit-fix-typo = "!f() { git commit -m \"fix-typo ${1}\"; }; f"              #fix-typo corrigir algo simples (ex. typo, nome de variável...);
commit-omg = "!f() { git commit -m \"omg ${1}\"; }; f"                   #omg m***a forte!
commit-security = "!f() { git commit -m \"security ${1}\"; }; f"               #security melhorar a segurança;
commit-die = "!f() { git commit -m \"die ${1}\"; }; f"                    #die remover códigos ou arquivos;
commit-help = "!f() { echo 'style commit-style => melhorar a estrutura/formato do código'; echo 'feature commit-feature => incluir nova funcionalidade/código'; echo 'perf commit-perf => melhorar a performance'; echo 'leak commit-leak => memory leaks'; echo 'doc commit-doc => escrever alguma documentação'; echo 'log commit-log => adicionar log na aplicação'; echo 'bug commit-fix => corrigir um bug'; echo 'die commit-die => remover códigos ou arquivos'; echo 'fix-ci commit-fix-ci => corrigir uma build no CI'; echo 'tests commit-tests => adicionar testes';  echo 'security commit-security => melhorar a segurança';  echo 'deps-up commit-deps-up => upgrade em dependências';  echo 'deps-down commit-deps-down => downgrade em dependências';  echo 'fix-lint commit-fix-lint => remover problemas com linter';  echo 'fix-typo commit-fix-typo => corrigir algo simples (ex. typo, nome de variável...)'; echo 'omg commit-omg => m***a forte'; }; f"
```

code **Wanddoze**!