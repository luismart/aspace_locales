Localizations
=============

**Target version:** v1.1.1 [/2]

Work in progress localizations for ArchivesSpace. To use:

- clone this repository on the ArchivesSpace server and `cd` into `more_locales_common`
- copy `code.yml` (i.e. `es.yml`) to `/path/to/archivesspace/locales`
- copy `enums/code.yml` (i.e. `enums/es.yml`) to `/path/to/archivesspace/locales/enums`
- copy the `more_locales_plugin` repository to `/path/to/archivesspace/plugins`

Update the configuration file:

```
AppConfig[:locale] = :es # code as appropriate
AppConfig[:plugins] << "more_locales_plugin"
```

__Pull requests are very welcome.__

**Contributing**

1. fork this repository in Github.
2. add this repository as an upstream (`git remote add upstream git@github.com:lyrasis/aspace_locales.git`)
3. create a branch and update the translations.
4. push the branch to your fork
5. create a pull request

To bring your fork up to date:

```
git fetch --all && git checkout master && git rebase upsteam/master
```

---
