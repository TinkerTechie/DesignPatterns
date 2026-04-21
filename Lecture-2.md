##
###
how are design patterns different from algorithms
-- 
algorithm -> time and spcae
--
observer -> subject class and observer class 
automatic update -> observer
reuest reply -> polling 

run time poly,orphisma 
subtype polymorphism

template -> behavioural 

'''typescript
class PaymentOptions{
processayment() : void{
  this.validate()
    this.authenticate()
    this.processPayment()
    this.paymentDetails()
    }
  abstract validate() : void
  abstract authenticate() : void
   processPayment() : void {
  
  }
  paymentDetails() : void {
  
  }

}
class CreditCard extends {
  /*validate() : void {
    console.log("validating card")
    }

  authenticate() : void {
    console.log()
  }
  processPayment() : void {
  
  }
  paymentDetails() : void {
  
  }
  paymentSteps() : void {}
    this.validate()
    this.authenticate()
    this.processPayment()
    this.paymentDetails()*/
  }
  let obj : CreditCard = new CreditCard() ;
  '''

-- what are the stpes to make template method readonly 
-- different code for template 

-- sigleton
-- every time any one opens something it should not be making a new object 
-- to make only one object we use singleton 
--  class ke sath ek hi value assocsiate ho -> use static 
-- 


###
