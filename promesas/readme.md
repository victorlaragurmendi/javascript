los errores los estamos manejando en el cuerpo de la promesa

la funcion que usa el await debe ser asincrona

el async awayt es opcionala poner .then()

el objeto error  tiene una parte llamada message

si el array fuera vacio se mostraria el mensaje definido en reject

en el ejemplo estamos simulando una promesa con settimeout pues si demora un tiempo y no se controla esa promesa, bien devolvera undefined ya que a la funcion que esta declarando la promesa en caso de que no este declarada la promesa le llega al pincho esperar y retornara undefined por eso son importantes las promesas para manejar cosas asincronas