# Function
 >Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

>Функсияҳо яке аз блокҳои бунёдии JavaScript мебошанд. Функсия Дар JavaScript ба тартиб монанд аст-маҷмӯи дастурҳое, ки вазифаро иҷро мекунанд е ягон кииматро ҳисоб мекунанд, аммо барои он ки ин тартиб ҳамчун функсия мувофиқат кунад, он бояд баъзе вурудотро қабул кунад ва натиҷаро баргардонад, ки дар он ҷо байни вуруд ва натиҷа робитаи возеҳе вуҷуд дорад. Барои истифодаи функсия, шумо бояд онро дар ҷое дар минтақае муайян кунед, ки мехоҳед онро даъват кунед.

![](/images/Screenshot_1.png)

> # Function - Declaration

> ###What is the Function Declaration ?

 >A function declaration tells the compiler about a function's name, return type, and parameters. A function definition provides the actual body of the function.

>Эъломияи функсия ба компилятор дар бораи номи функсия, навъи киммати баргардонидашуда ва параметрҳоро 
баён мекунад. Таърифи (номи функсия) функсия бадани воқеии функсияро ифода мекунад.

![](/images/Screenshot_2.png)

> # Function - Expression

>Variable x is used to store the function. Here the function is treated as an expression. And the function is called using the variable name.The function is called an anonymous function.

>Тағиребандаи x барои нигоҳ доштани функсия истифода мешавад. Дар ин ҷо функсия ҳамчун ифодакунанда баён шудааст. Функсия бо истифода аз номи тағиребандахо даъват карда мешавад.Ин намуд функсия функсияи беном номида мешавад.

> # Scope...

> ### What is scope ?

 >Scope is the area of code where a variable (or function) exists and is accessible. There are a few different types of scopes in JavaScript: Global Scope, Function Scope and Block Scope.

 >Майдони намоёне ки кодхо намоён хаст, ва тағиребанда (е функсия) вуҷуд дорад ва функсияхо бо хам алока доранд(робита). Дар JavaScript якчанд намудҳои гуногуни минтақаҳо (Scope) мавҷуданд: минтақаи глобалӣ, минтақаи функсия ва минтақаи блок. 

![](/images/FHHHS29VIAIMlWv.png)

> # Global Scope

> ### What is the Global Scope ?

 >Global Scope is a term used when a variable is declared outside any of the functions i.e the variables should be declared globally.

 >Минтақаи намоени глобалӣ истилоҳест, ки ҳангоми эълони тағиребанда берун аз ягон функсия истифода мешавад, яъне тағиребандаҳо бояд дар саросари функсия (истифода) эълон карда шаванд.

 ![](/images/Screenshot_3.png)

 > # Local Scope

 > ### What is the Local Scope ?

  >When we declare a function it creates its own scope. So, whenever a function is declared it creates its local scope which is limited to that function. So, it means that if you are declared a variable inside a function it’s limited to it.

  >Вақте ки мо функсияро эълон мекунем, он майдони намоени худро эҷод мекунад. Ҳамин тавр, вақте ки функсия эълон карда мешавад, он минтақаи намоени маҳаллии худро эҷод мекунад, ки бо ин функсия маҳдуд аст. Пас, ин маънои онро дорад, ки агар шумо тағиребандаро дар дохили функсия эълон карда бошед, пас он бо он маҳдуд аст.

  ![](/images/Screenshot_4.png)

  > # Hoisting

  > ### What is the Hoisting ?

   >Hoisting in JavaScript is a behavior in which a function or a variable can be used before declaration

   >Ба боло баромадан Ба JavaScript рафторест, ки дар он функсия ё тағиребанда пеш аз эъломия истифода бурдан мешавад

   ![](/images/Screenshot_5.png)

> ## Hoisting -Function Declaration

 >The function foo’s declaration (which in this case includes the implied value of 
it as an actual function) is hoisted, such that the call on the first line is able to 
execute

![](/images/Screenshot_6.png)

> ## Hoisting - Function Expression

 >Function expressions in JavaScript are not hoisted, unlike function declarations. You can't use function expressions before you create them:

 >Ифодаи функсия дар JavaScript, ба фарқ аз эъломияҳои функсия,  бароварда намешаванд. Шумо наметавонед ибораҳои функсияро пеш аз сохтани онҳо истифода баред: