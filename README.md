# DesignPatterns

###
## what are patterns ?? 
some sort of repeative problem that is occuring and somebody solved that problem 

liskov -> lsp 
base ki jagah child function accept kar skta hai

-- ocp

-- when we make a class and define type then the object of paytm gets made

 -- only run time needs to be cjanhed

- every time we change payment type then the whole new object is making whcih is complie time change but we need to change at runtime

high level -> kaam bta rha 
low level  --> kaam karta 

solid pribnciple - > div -> high level does not directly interact with low level 

strategy patternn changes the type at runtime 

''' typescript
interface Payment {
  pay(amount : number) }

class Checkout{
  type : Payment
  pay(amount : number) {
  this.type.pay(amount : number) } }

  class UPI implements Payment {
  pay(amount : number) : void {}

  } 
  
  class Paytm implements Payment {
  pay(amount : number) : void {}

  } 
  
  class Credit implements Payment {
  pay(amount : number) : void {}

  } 
  
  class Wallet implements Payment {
  pay(amount : number) : void {}

  } 
  '''
every problem has thousand of problems matters what is effective problem 

design patterns -> 

  solid principle -> Robert.C.Martin  -> agile principle

  single responsiblity principle -> one reason to change for class 

  open closed 
  liskov
  interface segregation principle
  no high level low level interaction(dip ) dependency inversion principle  
###
