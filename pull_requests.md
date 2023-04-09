# Pull Requests

Em uma tradução livre, podemos dizer que pull request significa solicitação de puxar, o que parece não significar muito, mas é algo importante em projetos de software colaborativo, como os que vocês irão fazer na Rede_.
Para começar, vocês já entenderam o que é uma branch e como é necessário que cada pessoa crie suas features em suas próprias branches, mas, para o projeto final, todo o código deve estar na branch principal, é aí que entram os pull requests, é por meio desse canal que um **desenvolvedor pode sinalizar que concluiu o desenvolvimento de uma feature**, e que esse trecho de código pode ser enviado para a branch principal.

Aqui abaixo pode-se ver um template exemplo de pull request:

# Description

Please include a summary of the change and which issue is fixed. Please also include relevant motivation and context. List any dependencies that are required for this change.

Fixes # (issue)

## Type of change

Please delete options that are not relevant.

- [ ] Bug fix 🐛 (non-breaking change which fixes an issue)
- [ ] New feature ✨ (non-breaking change which adds functionality)
- [ ] Refactor 🔨 (changed topology or functionality names)
- [ ] Documentation 📖 (updated the documentation of the code)

# How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. Please also list any relevant details for your test configuration

- [ ] Test A
- [ ] Test B

**Test Configuration**:
* Firmware version:
* Hardware:
* Toolchain:
* SDK:

# Checklist:

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] My changes generate no new warnings
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published in downstream modules

### Referências

- https://coodesh.com/blog/dicionario/o-que-e-pull-request-pr/
- https://embeddedartistry.com/blog/2017/08/04/a-github-pull-request-template-for-your-projects/