# Pipeline récent
Ce dossier contient le pipeline pour obtenir les différentes figures de l'article avec des images Docker récentes (versions actuelles).

## Prérequis : 

- Docker
- Git
- Architecture Linux/AMD64 pour les CPU
- Nextflow

### Installation de Nextflow 
Commandes bash à rentrer si Nextflow n'est pas présent sur la machine : 
```bash
sudo apt update
sudo apt install -y openjdk-21-jdk
curl -s https://get.nextflow.io | bash
chmod +x nextflow
sudo mv nextflow /usr/local/bin/
nextflow -version
```

### Fichiers nécessaires
- **`main.nf`**, **`nextflow.config`**, **`Data/`**

### Lancer le pipeline

```bash
nextflow run main.nf
```

### Configuration testée : 
VM sur le Cloub IFB : 
- 8 vCPU
- 32 Go de RAM

