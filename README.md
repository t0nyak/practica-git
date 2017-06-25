# practica-git
Resultados de los ejercicios de la práctica de Git del Web Bootcamp

### ¿Qué comando utilizaste en el paso 11? ¿Por qué?

Utilicé el comando `git reset --hard HEAD~1`. Este comando
resetea el último commit del repositorio. Si hubiera utilizado
HEAD~2 serían los dos últimos. Por otra parte, he utilizado --hard
porque quería perder los cambios hechos.

### ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

He rehecho los cambios primero, ya que el reset fue con --hard
y de esta forma no se pueden recuperar esos cambios y a continuación
he utilizado `git add README.md` ya que había modificado el archivo
para contestar la primera pregunta y por último `git commit -m "..."`

### El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No, ya que styled se creó de la misma versión de master que acabamos
de mergear.

### El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Sí, ya que ambos tenían versiones diferentes del mismo archivo y habían
partido de la misma.
