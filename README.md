## Teste Lógico

Este teste será utilizado para a avaliação técnica dos candidatos para vagas de desenvolvedores fullstack. Se você está vendo isso, parabéns você foi convidado a participar do nosso processo seletivo. Caso você tenha chegado aqui por acaso e queira uma chance ainda é possível participar do nosso processo seletivo enviando um email para rh@frentecorretora.com.br

Este teste é separado em teste para estágio e teste para desenvolvedor fulltime de todos os níveis, ou seja apenas estagiários realizaram um teste diferente, os outros níveis de júnior a sênior seram separados pelo desempenho nos teste.

## O que fazer para participar

Crie um fork deste projeto e desenvolva sua solução em cima do seu fork. Use o README do seu repositório para nos contar a sua linha de pensamento ao resolver o teste, como você abordou os problemas encontrados quais foram suas prioridades no desenvolvimento e qualquer ação necessária para a execução do seu projeto.

Lembre-se que isso é um teste técnico e como tal não existe uma única solução ótima, uma solução sub-ótima bem executada pode valer muito mais do que uma solução ótima mal executada.

## Crítérios de avaliação

- O cumprimento dos requisitos. Um dos pontos mais importantes de uma investida é que ela atinja seus objetivos e portanto soluções que não atendam a todos os requisitos terão nota reduzida.
- Cumprimento do prazo estipulado. Dizer um prazo para seu projeto mostra confiança nas suas habilidades, cumpri-lo mostra competência, divergencias no prazo reduziram a sua nota.
- A organização e legibilidade do código. Nós teremos que ler o seu código e quanto mais fácil for nos localizar e ler o seu código mais pontos nós daremos para o seu teste.

## Descrição

### Contexto

Nós precisamos da solução desse simples mas importante teste lógico que segue 4 regras. Crie um algoritmo que solucione as quatro regras da melhor forma possível.

- Crie um algoritmo que conte de 1-100 aonde
- Multiplos de 15 devem ser substituídos por FizzBuzz
- Multiplos de 5 devem ser substituídos por Fizz
- Multiplos de 3 devem ser substituídos por Buzz


n1 = int(input('digite um número qualquer entre 1 e 100 e descubra se ele é ou náo divisível por 15:'))
        
if 1 <= n1 <= 100:
            if n1 % 15 == 0:
                print(f"{n1} é um múltiplo de 15.")
            else:
                print(f"{n1} não é um múltiplo de 15.")
    
n2 = int(input('digite outro número qualquer entre 1 e 100 e descubra se ele é ou não divisível por 5:'))
if 1 <= n1 <= 100:
            if n2 % 5 == 0:
                print(f"{n2} é um múltiplo de 5.")
            else:
                print(f"{n2} não é um múltiplo de 5.")
               
n3 = int(input('digite outro número qualquer entre 1 e 100 e descubra se ele é ou não divisível por 3:'))
if 1 <= n1 <= 100:
            if n3 % 3 == 0:
                print(f"{n3} é um múltiplo de 3.")
            else:
                print(f"{n3} não é um múltiplo de 3.")


tds = input('digite enter e veja a seguir todos os números divisíveis por 3, 5 e 15 de 1 à 100 classificados entre: Fizz, Buzz, FizzBuzz e número reais')

for i in range(1, 101):
    if i % 15 == 0 :
         print ('FizzBuzz')
    elif i % 5 == 0: 
        print ("Fizz")
    elif i % 3 == 0:
        print ('Buzz')
    else:
        print(i)