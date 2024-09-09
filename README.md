
=> Déploiement d'une appli via "Kustomize"
		** Exemple de structure d'un projet "wordpress" :
			wordpress-datascientest
			├── kustomization.yaml
			├── mysql
			│   ├── deployment.yaml
			│   ├── kustomization.yaml
			│   ├── secret.yaml
			│   └── service.yaml
			├── patch.yaml
			└── wordpress
				├── deployment.yaml
				├── kustomization.yaml
				└── service.yaml
			