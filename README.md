// JavaScript String charAt() Method : 	Returns the character at the specified index (position)
var str = "HELLO WORLD";
var res = str.charAt(0) ; console.log(res) 

//charCodeAt() : Returns the Unicode of the character at the specified index  : Code ASCII
var str = "HEfLLO WORLD";
var n = str.charCodeAt(1); console.log(n) // Syntax : string.charCodeAt(index)    

// JavaScript String concat() Method : Syntax => string.concat(string1, string2, ..., stringX)
var str1 = "Hello ";
var str2 = "world!";
var str3 = "Have a nice day!";
var res = str1.concat(str2, str3); console.log(res)

// endsWith():	Checks whether a string ends with specified string/characters => string.endsWith(searchvalue, length)
var str = "Hello world, welcome to the universe.";
var n = str.endsWith("universe."); console.log(n)
var str = "Hello world, welcome to the universe.";
var n = str.endsWith("world", 11);  console.log(n)

//JavaScript String fromCharCode() Method => String.fromCharCode(n1, n2, ..., nX) 
var res = String.fromCharCode(72, 69, 76, 76, 79); console.log(res) // 3aks charAt


//JavaScript String includes() Method =>    string.includes(searchvalue, start)
var str = "Hello world, welcome to the universe.";
var n = str.includes("world");console.log(n) ;
var str = "Hello world, welcome to the universe.";
var n = str.includes("world", 12); console.log(n) 

//JavaScript String indexOf() Method =>  string.indexOf(searchvalue, start) 
var str = "Hello world, welcome to the universe.";
var n = str.indexOf("welcome"); console.log(n)
var str = "Hello world, welcome to the universe.";
var n = str.indexOf("e", 5);console.log(n)

//JavaScript String lastIndexOf() Method =>    string.lastIndexOf(searchvalue, start)
var str = "Hello planet earth, you are a great planet.";
var n = str.lastIndexOf("planet"); console.log(n) 
var str = "Hello planet earth, you are a great planet.";
var n = str.lastIndexOf("planet", 20);console.log(n)  

//JavaScript String localeCompare() Method => string.localeCompare(compareString)
var str1 = "cd";
var str2 = "ab";
var n = str1.localeCompare(str2);console.log(n)
var str1 = "ab";
var str2 = "ab";
var n = str1.localeCompare(str2);  console.log(n)

//JavaScript String match() Method => string.match(regexp)
var str = "The rain in SPAIN stays mainly in the plain";
var res = str.match(/ain/g);console.log(res);
var str = "The rain in SPAIN stays mainly in the plain";
var res = str.match(/ain/gi);console.log(res)

//JavaScript String repeat() method => Syntax string.repeat(count)

//JavaScript String replace() Method => Syntax string.replace(searchvalue, newvalue)
var str = "Visit Microsoft! ";
var res = str.replace("Microsoft", "W3Schools"); console.log(res) ;
var str = "Mr Blue has a blue house and a blue car";
var res = str.replace(/blue/g, "red");console.log(res) 

//JavaScript String search() Method => string.search(searchvalue)
var str = "Visit W3Schools!";
var n = str.search("W3Schools"); console.log(n) 

//JavaScript String slice() method => JavaScript String slice() method
var str = "Hello world!";
var res = str.slice(0, 5); console.log(res)
var str = "Hello world!";
var res = str.slice(3); console.log(res)
var str = "Hello world!";
var res = str.slice(-1); console.log(res)

//JavaScript String split() Method
var str = "How are you doing today?";
var res = str.split(" "); console.log(res)
var str = "How are you doing today?";
var res = str.split();console.log(res)
var str = "How are you doing today?";
var res = str.split("");console.log(res)
var str = "How are you doing today?";
var res = str.split(" ", 3);console.log(res) 
var str = "How are you doing today?";
var res = str.split("o");console.log(res)


//JavaScript String startsWith() Method => string.startsWith(searchvalue, start)
var str = "Hello world, welcome to the universe.";
var n = str.startsWith("Hello"); console.log(n) ;
var str = "Hello world, welcome to the universe.";
var n = str.startsWith("world", 6);console.log(n)

//JavaScript String substr() Method

var str = "Hello world!";
var res = str.substr(1, 4);console.log(res)
var str = "Hello world!";
var res = str.substr(2);console.log(res);
var str = "Hello world!";
var res = str.substr(11, 1);console.log(res)
var str = "Hello world!";
var res = str.substr(0, 1);console.log(res)

//JavaScript String substring() Method => string.substring(start, end)
var str = "Hello world!";
var res = str.substring(1, 4);console.log(res)
var str = "Hello world!";
var res = str.substring(2);console.log(res);
var str = "Hello world!";
var res = str.substring(4, 1);console.log(res)
var str = "Hello world!";
var res = str.substring(-3);console.log(res)
var str = "Hello world!";
var res = str.substring(str.length - 1, str.length);console.log(res)

//JavaScript String toLocaleLowerCase() Method => string.toLocaleLowerCase()
var str = "Hello World!";
var res = str.toLocaleLowerCase();console.log(res)

//JavaScript String toLocaleUpperCase() Method => string.toLocaleUpperCase()
var str = "Hello World!";
var res = str.toLocaleUpperCase();console.log(res);

//JavaScript String toLowerCase() Method => string.toLowerCase()    
var str = "Hello World!";
var res = str.toLowerCase(); console.log(res)

//JavaScript String toString() Method => string.toString();
var str = "Hello World!";
var res = str.toString();console.log(res);

//JavaScript String toUpperCase() Method => string.toUpperCase()
var str = "Hello World!";
var res = str.toUpperCase();console.log(res);

//JavaScript String valueOf() Method => string.valueOf()
var str = "Hello World!";
var res = str.valueOf();console.log(res)
