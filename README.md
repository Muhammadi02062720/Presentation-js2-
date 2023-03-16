
> # Scope...

> ### What is scope ?

 >Scope is the area of code where a variable (or function) exists and is accessible. There are a few different types of scopes in JavaScript: Global Scope, Function Scope and Block Scope.

 >Майдони намоёне ки кодхо намоён хаст, ва тағиребанда (е функсия) вуҷуд дорад ва функсияхо бо хам алока доранд(робита). Дар JavaScript якчанд намудҳои гуногуни минтақаҳо (Scope) мавҷуданд: минтақаи глобалӣ, минтақаи функсия ва минтақаи блок. 

![](/images/Screenshot_11.png)

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

 >The function add’s declaration (which in this case includes the implied value of 
it as an actual function) is hoisted, such that the call on the first line is able to 
execute

![](/images/Screenshot_6.png)

> ## Hoisting - Function Expression

 >Function expressions in JavaScript are not hoisted, unlike function declarations. You can't use function expressions before you create them:

 >Функсияи Ифодави ё Баёни дар JavaScript, ба фарқ аз эъломияҳои функсия,  бароварда намешаванд. Шумо наметавонед ибораҳои функсияро пеш аз сохтани онҳо истифода баред:

![](/images/Screenshot_7.png)

# Recurcion

> ### what is recurcion ?

 >A process ( a function in our case ) that calls itself.

 >Раванде аст ки худаш худашро даъват менамояд.

 ![](/images/Screenshot_8.png)

 >### Recurcion
  >A recursive function must have a condition to stop calling itself. Otherwise, 
the function is called indefinitely.
  
  >Функсияи рекурсивӣ бояд барои қатъ кардани даъват ба худ шарт дошта бошад. Дар акси ҳол функсия беохир даъват карда мешавад

![](/images/Screenshot_10.png)

# Closure 

> ### What is Closure ?

 >Closure is one of the most important, and often least understood, concepts in JavaScript. You can think of closure as a way to “remember” and continue to access a function’s scope (its variables) even once the function has finished running.  

 > Анчоми кор ва ё бастан яке аз маъмултарин ва муҳимтарин, ва аксар вақт камтарин мафҳумҳои фаҳмо дар Забони JavaScript аст. Шумо метавонед анчоми кор ва бастанро ҳамчун роҳи" ёдоварӣ " ва идомаи дастрасӣ ба майдони намоёни функсия (ва инчунин ба тағйиребандахои он) ва ҳатто пас аз ба итмом расидан иҷрои кори функсия бифахмед.
