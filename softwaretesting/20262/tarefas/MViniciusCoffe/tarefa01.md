# Tarefa 01 - Teste de Unidade, Integração, Cobertura e CI
### Aluno: Marcus Vinícius de Souza Azevedo.
### User: MViniciusCoffe
### E-mail: vinicius.azevedo.123@ufrn.edu.br
---

## Questões objetivas:
1. Quando colocamos uma aplicação no mundo real, na maioria das vezes não conseguimos prever quais serão todas as interações o usuário terá com ele, o sistema pode não conseguir responder como deveria a partir de um uso inesperado, causando falhas catastróficas de segurança, quebra da integridade das informações, corrupção de arquivos e entre outros bugs. Os testes surgiram justamente para mitigar esse "tiro no escuro" no lançamento de seu software, pois é a partir dele que testamos quais entradas devem ser possíveis ou não (inputs), e quais saídas são esperadas (outputs) ou não, fazemos isso tanto de forma automatizada como manual, onde a forma automatizada simula várias interações, corretas ou incorretas (caixa preta/partição) ou simula também de forma a testar cada linha do código individualmente (caixa branca/estrutural). Esses testes se subdividem em 3 categorias principais, testes de unidade, integração e de sistemas, como forma de pirâmide (Ou troféu em versões mais atualizadas), onde os testes de unidade ficam na base, e os testes de sistema no topo. Os testes de unidade servem para testar a menor unidade do sistema: Os módulos (como funções/métodos de classes, ou as próprias classes específicas), servindo como base das funcionalidades mais avançadas que iremos montar. Testes de unidade podem ser tanto caixa branca ou de caixa preta, e devem ser automatizados ao máximo, dependências externas devem ser "mockadas". Para isso foram criados frameworks de testes, como Jest. A partir dos testes de unidade, testamos como eles se integram em uma funcionalidade maior por meio de testes de integração.
2. A linguagem de programação escolhida foi Javascript, principalmente por ser o padrão global para desenvolvimento web e pelos seus frameworks flexíveis e poderosos. O Javascript é acompanhado de uma stack formada por:
- Frontend:
  - React
  - Vercel (Hospedagem)
  - Cors
  - Express
  - dotEnv
  - jsonWebToken
  - pg
- Backend:
  - postgreSQL
  - Node.js
  - Vercel (Hospedagem, antes era AWS por meio do AWS RDS)
- Testes:
  - Jest
- Monitoramento:
  - Github Actions (Pipeline ci/cd)
  - Sonar (Monitoramento da cobertura de testes)
- DevDependencies
  - Nodemon
  - Prettier
