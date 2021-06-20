- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

    > `git reset --hard HEAD~1`

    > Porque con `git reset HEAD~1` volveriamos al commit anterior sin perder los cambios que tengamos en nuestro working copy y usando el `--hard` nos 'ahorramos' el `git reset HEAD~1` y luego un `rm`

- ¿Qué comando utilizaste en el paso 12? ¿Por qué?

    > `git reset --hard 3eaba96`

    > De la misma manera que en el paso anterior, volvemos al commit ya directamente actualizando nuestra working copy que viene de un `reset --hard` y tiene la working copy desactualizada con el commit al que nos movemos

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

    > No causa conflicto.

    > Porque styled ya contiene el trabajo de master
    
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

    > Si que causó conflicto

    > Porque hay lineas con diferente información en el archivo git-nuestro.md que contienen ambas ramas

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

    > No causa conflicto

    > Porque al mergear styled con master, styled contiene todo el trabajo de nuestro respositorio y simplemente lo que estamos haciendo es que master vaya al punto en el que todo el trabajo lo tenemos actualizado.

- ¿Qué comando o comandos utilizaste en el paso 25?

    > `git log --graph`

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

    > Si

    > Porque title contiene todo el trabajo antes realizado y master viene de un commit anterior y simplemente seria añadir el trabajo nuevo que tiene title

- ¿Qué comando o comandos utilizaste en el paso 27?

    > `git reset HEAD~1`

- ¿Qué comando o comandos utilizaste en el paso 28?

    > `git restore git-nuestro.md`

- ¿Qué comando o comandos utilizaste en el paso 29?

    > `git branch -D title`

- ¿Qué comando o comandos utilizaste en el paso 30?

    > `git reset f5a1e4d`

- ¿Qué comando o comandos utilizaste en el paso 32?

    > `git reset 1bd64baca42158ae4329b1df0ad57eaef0633aa7`

- ¿Qué comando o comandos utilizaste en el paso 33?

    > `git reset e59a6e5`
