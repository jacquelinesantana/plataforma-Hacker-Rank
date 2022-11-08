# plataforma-Hacker-Rank
Explorando a plataforma, recursos, como se preparar para testes lógicos através da ferramenta.

1. preparar para uma nova entrevista
2. eu sou ... profissional de trabalho
3. Eu estou na área de profissional desenvolvedore a Escolha quanto tempo de menos de 1 ano até mais de 10anos qual o seu nível
4. Eu tenho minha entrevista em opções Uma semana; Um Mês; 3 Meses ou Mais de 3 Meses. Marque a opção Eu tenho interesse em ser conectada com outras oportunidades de trabalho.
5. clicar no botão Let's go - Vamos lá

exercício da plataforma 1

```
import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.function.*;
import java.util.regex.*;
import java.util.stream.*;
import static java.util.stream.Collectors.joining;
import static java.util.stream.Collectors.toList;

class Result {

  /*

   \* Complete the 'plusMinus' function below.

   *

   \* The function accepts INTEGER_ARRAY arr as parameter.

   */

  public static void plusMinus(List<Integer> arr) {

  // Write your code here

    int positive=0;
    int negative=0;
    int zero=0;
    int total=arr.size();   
 
    //solução oculta...

   double p=(double)positive/total; 
   double n=(double)negative/total; 
   double z=(double)zero/total; 

   System.out.println(String.format("%.6f",p));
   System.out.println(String.format("%.6f",n));
   System.out.println(String.format("%.6f",z));

  }
}


public class Solution {
  public static void main(String[] args) throws IOException {
    BufferedReader bufferedReader = new BufferedReader(new InputStreamReader(System.in));
    int n = Integer.parseInt(bufferedReader.readLine().trim());
    List<Integer> arr = Stream.of(bufferedReader.readLine().replaceAll("\\s+$", "")
    .split(" "))
      .map(Integer::parseInt)
      .collect(toList());
    Result.plusMinus(arr);
    bufferedReader.close();

  }

}
```

## Como realizar a prática e treino antes do processo seletivo:

