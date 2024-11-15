# Estrutura de Branches Recomendada
Para manter um fluxo de trabalho organizado, recomenda-se uma estrutura de branches que facilita o controle de versões e a colaboração entre a equipe. Abaixo, um exemplo com as principais branches e suas funções.
 1. **main ou master**
    - Contém a versão estável e pronta para produção do projeto. Somente PRs revisadas e aprovadas.
 2. **develop**
    - Branch de integração, onde novas funcionalidades são incorporadas antes de ir para a produção.
 3. **feature/**
    - Branches para o desenvolvimento de novas funcionalidades.
 4. **hotfix/**
    - Branches para correções urgentes em produção.
 5. **release/**
    - Branches preparatórias para uma nova versão, onde bugs e ajustes são realizados antes do deploy.
   
## Exemplo de Fluxo de Criação de Branches
1. Criar uma nova funcionalidade
   - A partir de **develop**, criar uma branch **feature/nome-da-funcionalidade**.
2. Lidar com um bug em produção
   - A partir de **main**, criar uma branch **hotfix/nome-do-bug**.
