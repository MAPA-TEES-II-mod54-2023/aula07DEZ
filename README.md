# aula07DEZ
exemplificar IC

# **Sobre integração contínua**
> Você pode criar fluxos de trabalho de integração contínua (CI) personalizados diretamente no repositório do GitHub com o GitHub Actions.

## **Sobre integração contínua**

A integração contínua (*CI, Continuous Integration*) é uma prática de software que exige commits frequentes de códigos para um repositório compartilhado. Fazer commits de códigos com frequência detecta erros com mais antecedência e reduz a quantidade de código necessária para depuração quando os desenvolvedores chegam à origem de um erro. As atualizações frequentes de código também facilitam o merge de alterações dos integrantes de uma equipe de desenvolvimento de software. Assim, os desenvolvedores podem se dedicar mais à gravação de códigos e se preocupar menos com erros de depuração ou conflitos de merge.

Ao fazer commit do seu repositório, você pode continuamente compilar e testar o código para garantir que o commit não insira erros. Seus testes podem incluir linters de código (que verificam formatação de estilo), verificações de segurança, cobertura de código, testes funcionais e outras verificações personalizadas.

Para compilar e testar seu código, é necessário usar um servidor. Você pode criar e testar atualizações no local antes de fazer push do código para um repositório, ou pode usar um servidor de CI que verifica os novos commits de código em um repositório.

Fonte: [GitHub - Sobre Integração Contínua](https://docs.github.com/pt/actions/automating-builds-and-tests/about-continuous-integration)
