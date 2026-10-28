# Operar este fork

Este fork preserva o projeto e a licença upstream. O README principal documenta parâmetros das imagens e implantação; não faz parte da stack OpenShift GitOps.

Antes de publicar uma instância, confira package.json, variáveis documentadas e o provedor de hospedagem escolhido. Tokens de API pertencem ao armazenamento de secrets desse provedor, sem exposição em URLs, imagens ou commits.

Valide a suíte definida no package.json em ambiente local. Teste o endpoint com usuário público sintético e confira limites da API e cache antes de atribuir uma resposta antiga a erro de implantação. Para atualizar a origem, compare alterações com upstream e preserve a configuração específica do fork.

O perfil thiagobotelho consome as imagens desta aplicação; alterar a URL no perfil não implanta uma nova instância. Resultados pessoais de execução devem permanecer fora destes guias.
