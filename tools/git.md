Git
===

### Commits en Git

Los mensajes de commit:

  * siempre los hacemos en inglés
  * normalmente tienen una sola línea (aunque sabemos que más podría ser mejor)
  * la primera línea se forma de un **tipo**, un **contexto** y una **descripción**
    ```
    tipo(contexto):descripción
    ```

  La línea no debiera tener más de 100 caracteres para que se lea bien en Github.

#### Tipo

  * **feat**: Un nuevo feature
  * **fix**: La corrección de un bug
  * **chore**: Cambios al proceso de build y herramientas auxiliares
  * **test**: Agrega tests
  * **style**: Cambios que no afectan el significado del código (espacios, indentación, etc.)

#### Contexto

  El contexto es una palabra que haga referencia al lugar del código donde afecta el commit.

#### Descripción

  * usamos el verbo imperativo en inglés:  "change" not "changed" nor "changes"
  * sin mayúscula al principio
  * sin punto (.) al final

Nota: Esto es un extracto/traducción de [este documento](https://github.com/ajoslin/conventional-changelog/blob/master/CONVENTIONS.md), que es más completo, pero que por el momento no es una práctica que sigamos completamente en Platanus.

### Branches y Pull-requests

Salvo cosas muy insignificantes, los features los hacemos en un nuevo branch y hacemos un pull-request hacia master.
