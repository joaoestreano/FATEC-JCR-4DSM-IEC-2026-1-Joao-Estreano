📓 AULA 07 - Testes Avançados
Objetivo
Criar testes de integração, mocks e workflow de segurança.
Passo a Passo
1. Criar Teste de Integração
Crie tests/processamento.test.js:
javascript
12345678910111213141516
2. Criar Teste de Integração Combinado
Crie tests/integracao.test.js:
javascript
12345678
3. Verificação de Segurança Local
bash
12
4. Criar Workflow de Segurança
Crie .github/workflows/security.yml:
yaml
12345678910111213141516171819202122232425
5. Gerar Relatório de Cobertura
bash
1
6. Commit e PR
bash
1234
Abra PR no GitHub
Verifique pipelines (CI + Security)
Verificação
Testes de integração criados
Mocks configurados
npm audit sem vulnerabilidades críticas
Workflow security.yml criado
Relatório de cobertura gerado
PR com pipelines verdes
