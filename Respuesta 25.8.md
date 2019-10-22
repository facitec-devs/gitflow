Para sistemas grandes o sistemas donde la plataforma de ejecución no es la misma que
la plataforma de desarrollo, la integración continua quizá no sea práctica. Ante tales circunstancias se puede usar un sistema que se construya diariamente. Las características de
esto son las siguientes:
1. La organización de desarrollo establece un tiempo de entrega (por ejemplo, 2 P.M.)
para los componentes del sistema. Si los desarrolladores tienen nuevas versiones
de los componentes que escriben, deben entregarlas en ese plazo. Los componentes pueden estar incompletos, pero deben ofrecer alguna funcionalidad básica
que pueda ponerse a prueba.
2. A partir de dichos componentes se crea una nueva versión del sistema al compilarlos
y vincularlos para formar un sistema completo.
3. Entonces este sistema se entrega al equipo de pruebas, que realiza un conjunto de
pruebas de sistema predefinidas. Al mismo tiempo, los desarrolladores todavía trabajan en sus componentes, añaden funcionalidad y reparan las fallas descubiertas en
pruebas anteriores.
4. Las fallas que se descubren durante las pruebas del sistema se documentan y regresan a los desarrolladores del sistema, quienes reparan dichas fallas en una versión
posterior del componente.
