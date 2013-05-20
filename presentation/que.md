!SLIDE center transition=turnUp

# Que es REST

.notes Se originó en el año 2000, en una tesis doctoral sobre la web escrita por Roy Fielding.
.notes REST Hoy en dia, significa todo y nada a la vez.
.notes Muchas veces malinterpretado, puede signifcar algo completamente distinto a lo que era originalmente.

!SLIDE smbullets incremental transition=turnUp

# Caracteristicas de REST

* Client-Server
* Stateless
* Cacheable
* Uniform Interface
* Layered System
* Code-on-demand

.notes Quien ha trabajado con REST? Seguramente saben que tiene las siguientes caracteristicas
.notes Usando HTTP obtenemos todas menos una de las reestricciones

!SLIDE bullets incremental transition=turnUp

# La caracteristica olvidada

**Inside Uniform Interface**

* Hypermedia as the engine of application state

!SLIDE smbullets incremental transition=turnUp

# HATEOAS

**H**ypertext **A**s The **E**ngine of **A**pplication **S**tate

* Un solo punto de entrada muestra los recursos dispobiles y sus URL's
* Vinculos representan las relaciones entre los recursos.
* Los clientes son guiados por los vinculos en el proceso de negocio
