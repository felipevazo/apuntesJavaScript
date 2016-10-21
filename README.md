
agregar metodos fuera de clase en la clase
clase.prototype.metodo=function(variableEntrada)
{
};
crear constructor de  clase:
function nombreClase(variablesEntrada)
{
this.variables=variables;
};

establecer herencia
hijo.prototype=new Padre();

this.variableOMetodo -> publico
var variableOMetodo -> privado, ambos dentro de la clase.


con un if-else podemos crear un sistema de clave para entregar valores de atributos.

FOR IN, AWEONAO
var obj = {a:1, b:2, c:3};
    
for (var prop in obj) {
  console.log("obj." + prop + " = " + obj[prop]);
}

typeof nombrevariable=tipovariable;

// what is this "Object.prototype" anyway...?
var prototypeType = typeof Object.prototype;
console.log(prototypeType);-> imprime OBJECT, es decir prototype es un objeto al final

// now let's examine it!
var hasOwn =Object.prototype.hasOwnProperty("hasOwnProperty");
console.log(hasOwn);--------> imprime true, lo que significa que tiene atributo de tipo "tienepropioatributo" wut
