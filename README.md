# Segundo-Bimestre---Atividade-1---Interpreta-o-de-Algoritmos-em-Portugol_atividade-11
programa {
  funcao inicio() {
    real peso_de_peixes, excesso, multa
    escreva("Digite o peso dos peixes: ")
    leia(peso_de_peixes)
    excesso = peso_de_peixes - 50
    se (peso_de_peixes > 50)
    {
      multa = excesso * 4.5
    }
    senao
    {
      excesso = 0
      multa = 0
    }
   escreva("Quantidade de peixes: ", peso_de_peixes, "kg")
   escreva("Excesso: ", excesso, "kg")
   escreva("Multa a pagar: R$ ", multa)
  }
}
