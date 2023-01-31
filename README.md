após executar ansible:

1. configurar jenkins com initialPassword print console
2. criar usuário
3. instalar plugins recomendados
4. instalar extensões:
	4.1 Docker
	4.2 Docker Commons
	4.3 Docker Pipeline
	4.4 Kubernetes CLI
5. Baixar, instalar e reiniciar servidor
6. Gerenciar Jenkins
	6.1 Criar credencial DockerHub
	6.2 Criar credencial secretfile -> kube_config.yaml
7. Criar uma pipe jenkins
	7.1 Adicionar repositório com url
	7.2 Selecionar importar Jenkinsfile do repositório
8. Executar a pipe

kubectl port-forward svc/web 8080:80 -> disponibiliza porta para acessar SB do cluster