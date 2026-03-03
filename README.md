programa {
  inclua biblioteca Util
  funcao inicio() {
    real A, B, C
  
  escreva ("primeiro lado: ")
  leia (A)
Util.aguarde (250)
  escreva ("segundo lado: ")
  leia (B)
Util.aguarde (250)
  escreva ("terceiro lado: ")
  leia (C)
Util.aguarde (250)
se (A == B e B == C) {

    escreva(".")
    Util.aguarde (1000)
    escreva(".")
    Util.aguarde (1000)
    escreva(".")
    Util.aguarde (500)
  escreva ("\n")
  escreva ("equilatero")
}
senao se(A == B ou A == C ou B ==C ){

    escreva(".")
    Util.aguarde (1000)
    escreva(".")
    Util.aguarde (1000)
    escreva(".")
    Util.aguarde (500)
escreva ("\n")
  escreva("isosceles")
}
senao{

    escreva(".")
    Util.aguarde (1000)
    escreva(".")
    Util.aguarde (1000)
    escreva(".")
    Util.aguarde (500)

escreva ("\n")
  escreva ("escaleno")
}
  }
}
