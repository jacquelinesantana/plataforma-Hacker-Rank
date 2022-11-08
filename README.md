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

Antes de apresentar o passo a passo, é importante reforçar que vou incluir imagens de todo o processo.

1. Na tela de boas vindas, escolha uma das opções: Prepare for job Interviews(preparar-se para entrevistas de emprego) ou Learn & Compete with outhers (estudo e competir com outres), escolhemos a **Prepare for job Interview**s;
2. Na tela seguinte escolha entre as opções: Student ou Working Professional, escolhemos **Student**;
3. Na guia seguinte escolha quanto tempo de experiência com a tecnologia você já tem;
4. Na tela seguinte podemos escolher entre modo Dark ou não;
5. Você pode acessar a opção Settings para realizar algumas configurações no seu cadastro e perfil;
6. Essa parte da aplicação é em inglês, caso precise de ajuda, tem como traduzir a página pelo próprio navegador;
7. Escolha o seu teste/ treino e clicar em Iniciar preparação;
8. Você poderá escolher um desafio para resolver;
9. Leia com calma o enunciado do desafio, aqui vimos que se tratava de um desafio de lógica;
10. Você poderá escolher uma opção de linguagem de programação que seja mais familiar a você, para aplicar a sua solução;
11. Note que no teste, vc tem indicação de onde vc deve desenvolver a solução, no caso da imagem, a solução será um trecho de código que vamos desenvolver dentro do método PluxMinus();
12. Agora é desenvolver a solução e quando finalizada testar clicando primeiro no botão Run Code, veja com atenção a resposta da aplicação em execução(pode demorar alguns segundos) e se deu tudo certo clicar em submit Code;
13. Exemplo de uma resolução desenvolvida;
14. Tela de sucesso ao submeter a resolução desenvolvida, é necessário rolar a pagina para baixo;

### Imagens:

