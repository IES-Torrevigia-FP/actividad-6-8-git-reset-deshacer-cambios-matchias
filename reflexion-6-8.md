git reset cambia el historial moviendo HEAD hacia atrás y puede borrar o deshacer cambios según el modo (--soft, mixed o hard). En cambio, git revert no borra nada, sino que crea un nuevo commit que deshace los cambios, por eso es más seguro en repositorios compartidos.

Usaría:

--soft cuando quiero rehacer el último commit sin perder cambios.
mixed cuando quiero revisar y volver a organizar los cambios.
--hard solo en pruebas o cuando quiero eliminar todo completamente.