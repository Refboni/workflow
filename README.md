
### Validação da Parte 3
Stage  Job ID             Job name           Workflow name       Events
0      setup-e-lint       setup-e-lint       Pipeline Principal  push
1      testes-unitarios   testes-unitarios   Pipeline Principal  push
1      scan-de-seguranca  scan-de-seguranca  Pipeline Principal  push
2      build-e-deploy     build-e-deploy     Pipeline Principal  push

### Validação da Parte 4
Com base na saída do terminal, é possível comprovar que o Job 2 e o Job 3 rodaram em paralelo porque o act executou as linhas de log de ambos os jobs intercaladas na mesma tela, o que indica que as tarefas estavam ocorrendo ao mesmo tempo em contêineres Docker distintos.
