# themis-cryptographie-complexe
## https://github.com/cossacklabs/themis.git
Themis provides strong, usable cryptography for busy people

Themis provides strong, usable cryptography for busy people

Convient parfaitement aux applications multi-plateformes. Cache les détails cryptographiques. Fabriqué par des cryptographes pour les développeurscoeur_orange
Qu'est-ce que Themis
Themis est une bibliothèque de services cryptographiques open source de haut niveau pour la sécurisation des données pendant l'authentification, le stockage, la messagerie, l'échange réseau, etc. Themis résout 90% des cas d'utilisation typiques de protection des données qui sont communs à la plupart des applications.

Themis permet de créer facilement, rapidement et en toute sécurité des fonctionnalités cryptographiques simples et complexes. Themis permet aux développeurs de se concentrer sur l'essentiel: développer leurs applications.

Cas d'utilisation que Themis résout
Cryptez les secrets stockés dans vos applications et votre backend: clés API, jetons de session, fichiers.

Cryptez les champs de données sensibles avant de les stocker dans la base de données ( «chiffrement au niveau du champ côté application» ).

Prise en charge du cryptage interrogeable , de la tokenisation des données et du masquage des données à l'aide de Themis et Acra .

Échangez des secrets en toute sécurité: partagez des données sensibles entre les parties, créez une application de chat simple entre les patients et les médecins.

Créez des schémas de chiffrement de bout en bout avec une architecture centralisée ou décentralisée: chiffrez les données localement sur une application, utilisez-les chiffrées partout, déchiffrez uniquement pour l'utilisateur authentifié.

Maintenez des sessions sécurisées en temps réel : envoyez des messages chiffrés pour contrôler les appareils connectés depuis votre application, recevez des données sensibles en temps réel de vos applications vers votre backend.

Comparez les secrets entre les parties sans les révéler (authentification basée sur la preuve sans connaissance).

Une bibliothèque cryptographique qui leur convient à tous : Themis est la meilleure solution pour les applications multi-plateformes (par exemple, l'application iOS + Android + Electron avec le backend Node.js) car elle fournit une API 100% compatible et fonctionne de la même manière sur toutes les plates-formes prises en charge .

Cryptosystèmes
Themis fournit des blocs de construction prêts à l'emploi ( «cryptosystèmes» ) qui simplifient l'utilisation des principales opérations de sécurité cryptographique.

Themis fournit 4 services cryptographiques importants:

Secure Cell : un conteneur cryptographique multimode adapté pour stocker tout, des fichiers cryptés aux enregistrements de base de données et aux chaînes de format préservées. Secure Cell est construit autour de AES-256-GCM, AES-256-CTR.
Secure Message : unesolution de messagerie chiffrée simplepour le plus large éventail d'applications. Échangez les clés entre les parties et vous êtes prêt à partir. Deux paires de cryptosystèmes sous-jacents: ECC + ECDSA / RSA + PSS + PKCS # 7.
Secure Session : échange de données cryptées orienté session avec transfert de confidentialité pour de meilleures garanties de sécurité et des infrastructures plus exigeantes. Secure Session peut parfaitement fonctionner comme cryptage de socket, sécurité de session ou primitive de messagerie de haut niveau (avec une infrastructure supplémentaire comme PKI). Accord de clé ECDH, cryptage ECC & AES.
Comparateur sécurisé : protocole cryptographique basé sur des preuves sans connaissance pour l' authentification et la comparaison des secrets.
