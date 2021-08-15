# Topic 8. La esencia del buen diseño

## Tip 14: Un buen diseño es más fácil de cambiar que un mal diseño

Algo que está bien diseñado se adapta a quiénes lo usan. En el caso del código es que se adapta al cambio. 

**Principio Easier to Change(ETC)**. Cada principio de diseño es un caso especial de ETC.

¿Por qué el **desacoplamiento** es bueno? Porque al aislar las preocupaciones hacemos que cada una sea más fácil de cambiar -> ETC.

¿Por qué es útil el **SRP**? Porque un cambio en los requisitos se refleja en un cambio en un solo módulo -> ETC.

¿Por qué es importante el **naming**? Porque los buenos nombres hacen que el código sea más fácil de leer, y tienes que leerlo para cambiarlo. ¡ETC!

## ETC es un value, no una regla

Los values son cosas que te ayudan a tomar decisiones. ETC es una guía que te ayuda a escoger entre opciones. 

Para incorporar esto es necesario cambiar la mentalidad. Cada vez que hagas algo(guardes cambios, escribas un test, fixees un bug, etc) pregúntate a ti mismo: 

*"¿Lo que acabo de hacer hizo que el sistema general fuera más fácil o más difícil de cambiar?"*

Hay una premisa implícita en ETC, la cuál asume que una persona puede decir cuál de los muchos caminos será más fácil de cambiar en el futuro.

A veces, sin embargo, no tendrás ni idea:

1. **Intenta que el código que escribas sea reemplazable**. De esa manera, pase lo que pase en el futuro, este fragmento de código no será un obstáculo. En realidad es lo que deberías estar haciendo todo el tiempo, de todos modos. Realmente solo está pensando en mantener el código **desacoplado y cohesivo**.

2. **Anota la situación en un diario**, las opciones que tienes y las conjeturas sobre el cambio. Deja un tag o comentario en el código. Más adelante, cuando este código tenga que cambiar, podrás mirar el diario y obtener tu feedback. 


