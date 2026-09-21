# DBFortress

> Infrastructure de base de données sécurisée, sauvegardée et supervisée, déployée dans un lab VirtualBox.

## Objectif

Reproduire à petite échelle une infrastructure de base de données « de production » :
sauvegardes automatiques, supervision, réplication et sécurisation.
Projet réalisé dans le cadre de ma formation BTS SIO (option SISR).

## Architecture


| Machine      | Rôle                     | OS         |
|--------------|--------------------------|------------|
| `db-primary` | Base de données principale | Debian 12  |
| `db-replica` | Réplica (à venir)        | Debian 12  |

## Technologies

- Debian (sans interface graphique)
- PostgreSQL & MySQL
- VirtualBox
- [Grafana / Prometheus, Ansible... à ajouter au fur et à mesure]

## Avancement

- [x] Création du dépôt
- [X] Installation de la VM Debian
- [ ] Installation et configuration de la base de données
- [ ] Sauvegardes automatiques et test de restauration
- [ ] Supervision et alertes
- [ ] Réplication
- [ ] Automatisation (Ansible)
- [ ] Sécurisation et documentation finale

## Structure du dépôt

```
docs/      documentation, schémas, procédures
scripts/   sauvegardes, tests de restauration
docker/    fichiers Docker (si utilisés)
ansible/   playbooks de déploiement
```

## Installation et utilisation

non

## Ce que j'apprends

none

## Licence

MIT, voir le fichier [LICENSE](LICENSE).

## Auteur

Peyo Moinard, Allias PeyoKks, étudiant en bts, mon linkedin : https://www.linkedin.com/in/peyo-moinard-96b24b316/