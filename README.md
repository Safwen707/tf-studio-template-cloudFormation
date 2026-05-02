terraform-studio-setup.yaml (celui qui contient le Rôle IAM et le Bucket S3 unifiés)  pour l’onboarding d utilisateur de TerraformStudio  :

Guider le client pas à pas pour qu’il connecte son compte AWS de manière sécurisée

Lui faire créer (via CloudFormation) le rôle IAM et le bucket S3 nécessaires

Récupérer automatiquement les identifiants (ARN du rôle, nom du bucket)

Stocker ces informations en base pour permettre les appels STS ultérieurs
