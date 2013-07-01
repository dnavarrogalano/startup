#!/usr/bin/env node
var fs = require('fs');
var outfile = "hw2.txt";
var outArray = [] ; //new array(100) ;


var i = 1;
console.log("inicia: " + i + "\n " );
while (outArray.length <= 100)

  {
	//console.log("entra: " + i + "\n " );
	i=i+2;
		if(isPrimo(i))
			{
			outArray.push(i);
			
			}
	}

function isPrimo( x ) 
{
	if (x % 2 == 0 ) // par != primo
		{return false;}
	else
		{
		
		var aux = Math.floor(x/2);
		//console.log("x : " + x + "\n " );
		//console.log("aux : " + aux + "\n " );
		for(j=3;j<=aux; j=j+2)
		{
			//console.log("j : " + j + "\n " );
			if (x % j == 0)
				{return false;}
					
		}
			//console.log("ok : " + x + "\n " );
			return true;
	}

	
}

fs.writeFileSync(outfile, outArray);  

//console.log("Script: " + __filename + "\nWrote: " + out + "To: " + outfile);
