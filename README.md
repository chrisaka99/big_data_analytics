# Système de recommandation de véhicule pour des clients

### Contexte
Vous avez été contacté par un concessionnaire automobile afin de l'aider à mieux cibler les véhicules
susceptibles d'intéresser ses clients. Pour cela il met à votre disposition :
- Son catalogue de véhicules
- Son fichier clients concernant les achats de l'année en cours
- Un accès à toutes les informations sur les immatriculations effectuées cette année


Votre client sera satisfait si vous lui proposez un moyen afin :
- Qu'un vendeur puisse en quelques secondes évaluer le type de véhicule le plus susceptible
d'intéresser des clients qui se présentent dans la concession
- Qu'il puisse envoyer une documentation précise sur le véhicule le plus adéquat pour des clients
sélectionnés par son service marketing


- Immatriculations.csv : informations sur les immatriculations effectuées cette année [Télécharger ici](https://drive.google.com/file/d/1dJHJ72xnrLBpW59VbIh4msYRX91r2WtE/view?usp=sharing)
- Catalogue.csv : catalogue de véhicules
- Clients_N.csv : fichier clients concernant les achats de l'année en cours
- Marketing.csv : clients sélectionnés par le service marketing

L'objectif est de prédire pour chacun de ces clients la catégorie de véhicules qui lui correspond le mieux.
Pour cela il faut d'abord identifier les types de catégories possible à l'aide du fichier Catalogue.csv, ensuite choisir le meilleur modèle Machine Learning possible sur l'assemblage des fichiers Clients et Immatriculations. Enfin choisir le meilleur modèle et générer des prédictions sur le fichier Marketing.csv
