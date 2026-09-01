# Taller1Martin


1.  ¿Cuál es la diferencia entre la clase CuentaBancaria y un objeto CuentaBancaria?
  - La clase CuentaBancaria es el modelo que define qué datos y comportamientos tendrá una cuenta. Un objeto CuentaBancaria es una cuenta específica creada a partir de ese modelo.

2. ¿Qué hace exactamente la palabra new?
  - La palabra new crea un nuevo objeto en memoria a partir de una clase. Al usar new CuentaBancaria() se crea una nueva cuenta independiente.

3.  Si tienes dos cuentas a y b y ejecutas a.consignar(1000), ¿cambia el saldo de b? Justifica tu respuesta.
     - No cambia el saldo de b, porque a y b son objetos diferentes y cada uno tiene su propio saldo.

4. ¿Por qué se dice que el método retirar protege el estado del objeto?
  - Porque el método verifica que haya suficiente saldo antes de realizar el retiro, si no hay dinero suficiente, evita que el saldo quede en un valor incorrecto.

5.  Propón una entidad distinta a las trabajadas e indica dos de sus atributos y dos de sus métodos.
  - Una entidad podría ser Automovil.

Atributos:

marca
velocidad
Métodos:

acelerar()
frenar()
