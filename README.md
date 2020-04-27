# apprentissage-node

![master](https://github.com/ComteZero/apprentissage-node/workflows/Node.js%20CI/badge.svg?branch=master)

![develop](https://github.com/ComteZero/apprentissage-node/workflows/Node.js%20CI/badge.svg?branch=develop)

projet d'apprentissage node + github

## presentation

quelle lib pour le js ? react+

## service

service rendu par une image docker nginx
pour adresser une problématique x-site

### static

dist/ dans /var/www

distribution dans cdn ?

### backend

adhérence à un backend gérée par une variable d'environnement

APPRENTISSAGE_BACKEND=http://url:port

authn user génér par le back-end

- session partagée ?
- sso?

## contributing

<https://www.conventionalcommits.org/en/v1.0.0/>

## releasing

<https://itnext.io/how-to-automate-versioning-and-publication-of-an-npm-package-233e8757a526>

Trigger a release

Once a commit reaches master, to perform a release just needs one command: npm run release