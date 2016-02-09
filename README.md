# jQuery Countup

Un simple plugin de jQuery crado par contar desde una fecha, es una adaptacion del [jQuery-Countdown](https://github.com/martinaglv/jQuery-Countdown) de Martin Angelov.


Ejemplo de Uso:

```js
$(function(){
		
	$('#countup').countup({
    	start: new Date(2010, 5, 5, 17, 42, 21), //año, mes, dia, hora, minutos, segundos
  
	});
	
});
```