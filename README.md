Todo:

- script d'installation du script d'installation (bin/bootstrap)
- Script d'installation des hooks (genre un git install-hook)
    - doit checker si phpcs est accessible, sinon bloquer et demande de l'installer
- Documentation sur la liste des paramètre possible
- 2 niveau de configuration (1 au niveau du fichier .git/hooks/config, autre au niveau du fichier .csconfig)

Configuration au niveau du user
PHP_BIN (normalement detecté automatiquement)
PHPCS_BIN (normalement detecté automatiquement)

Configuration au niveau du projet
- PHPCS_CODING_STANDARD (PSR2 par défaut)
- PHPCS_IGNORE regex avec la liste des fichiers a ignorer ("" par défaut)
- PHPCS_FILE_PATTERN format des fichiers a traiter (par défaut "\.php$"")
- PHPCS_ENCODING (encodage du code, "" par défaut)
- PHPCS_IGNORE_WARNINGS (permet de ne pas bloquer les commit si les erreurs ne sont - que des warnings, par exemple le nombre de caractère par ligne)


