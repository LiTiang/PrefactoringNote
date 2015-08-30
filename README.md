## CONVENTION
* **Naming**
	* use long name for a method which seldom to use
	* <font color="red">see note</font>
* **Presentation**
	draw GUI + use case 


## PRINCIPLE
* not all principle or practice to meet all case
* 讓被呼叫方法具備查核先決條件之機制
* 把假設和決策形諸文件p33
* process error & mistake p34
* coding style strategy p41
* lower request for initial version of sys is `MFS`
* Analysis = use case
* Design   = construct a suit of solving method  
* Paralysis of Analysis & Design p48

## CONCEPT
* request = sys func
* code    = request implementation
* log     = why select specific skill to solve specific func

## METHOD
* Transfer initial request to type 1 of nonformal use case ( NUC1 )
* description in NUC1 must has mix behaveiors of both `sys` & `usr`
* transfer description for `usr` behavior to `Note`
* the ver2 of NUC has higher `Abstraction` & prefer no skill level, delete implemenation details

## TERMINOLOGY
* **Prefactoring**
	* insight, give a chance to lower the posibility of using refactoring
	
    * focus on `interface`( thinking which `component` can be used, not how to use such `component` ), then `Abstraction`
    
    * the `prefactoring` guideline base on 3 extreme ( Extreme `Abstraction`, 
    Extreme `Separation of concern`, Extreme `readability` )

* **Interface**
	* char I (method) which come from `API` or 
    * `Java` `Interface`
    * `CRC` card
    * the interaction within stuffs
    * `Class`
    
