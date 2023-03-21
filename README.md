# bash_sistema_operativo
# Semaforos que es en sistemas

# Un semáforo es una herramienta fundamental en los sistemas operativos para la gestión de procesos y la 
# sincronización de actividades. En esencia, un semáforo es una variable compartida entre procesos o hilos que #permite controlar el acceso a un recurso o sección crítica en un sistema concurrente.

# El semáforo se inicializa con un valor entero positivo y se utiliza para llevar un registro del número de #procesos que pueden acceder simultáneamente a un recurso compartido. Cuando un proceso desea acceder al recurso, #decrementa el valor del semáforo en uno. 

# En qué consisten los semáforos binarios y enteros 

# Los semáforos binarios y enteros son dos tipos de semáforos utilizados en la programación de sistemas operativos para la gestión de procesos y la sincronización de actividades.

# Un semáforo binario es un semáforo con dos posibles valores: 0 y 1. Este tipo de semáforo se utiliza comúnmente para la exclusión mutua, lo que significa que solo un proceso a la vez puede acceder al recurso compartido. Cuando el semáforo está en 1, significa que el recurso está disponible y un proceso puede acceder a él. Cuando el semáforo está en 0, significa que el recurso está ocupado y otro proceso debe esperar a que el semáforo cambie a 1 antes de intentar acceder al recurso.

# Relacion entre los semáforos y la sincronización 

# La relación entre los semáforos y la sincronización es muy estrecha. Los semáforos son una herramienta fundamental en la programación de sistemas operativos para la sincronización de procesos y la gestión de recursos compartidos.

# La sincronización se refiere a la coordinación de las actividades de varios procesos en un sistema concurrente, de tal manera que los procesos trabajen juntos de manera ordenada y cooperativa. La sincronización puede ser necesaria cuando varios procesos desean acceder a los mismos recursos compartidos al mismo tiempo.

# Los semáforos permiten a los procesos sincronizar sus actividades al coordinar el acceso a los recursos compartidos. Cuando un proceso necesita acceder a un recurso compartido, debe primero obtener el control del semáforo asociado a ese recurso. Si el semáforo está en un estado que indica que el recurso no está disponible, el proceso debe esperar hasta que el semáforo cambie de estado.