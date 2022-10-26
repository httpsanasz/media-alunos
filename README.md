# media-alunos
teste em c

#include <stdio.h> 

#n alunos com n notas

#media da sala

#quantidade de aprovados, de rec e reprovados

def main():

n=int(input("Digite o numero de alunos: "))

  soma=0
  
  i=0
  
  aprovados=0
  
  muito_bom=0
  
  reprovado=0
  
  rec=0
  
  while n>i:
  
      nota=float(input("Digite a nota do aluno: "))
      
  soma=soma+nota
  
  i=i+1
  
  if nota >=5:
  
      aprovados=aprovados+1
      
  if nota >8:
  
      muito_bom=muito_bom+1
      
  elif nota <3:if + else
  
     reprovado=reprovado+1
     
  else
  
     rec=rec+1
     
print ("A media da turma eh: ", soma/n)

print ("O numero de aprovados eh:", aprovados)

print ("O numero de alunos com nota muito boa eh: ", muito bom)

print ("O numero de reprovados eh: ", reprovado)

print ("O numero de alunos em recuperacao eh: ", rec)

main ()
