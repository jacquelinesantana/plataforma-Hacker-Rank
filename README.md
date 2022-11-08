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

(imagem tela 1 - escolher qual o seu objetivo aqui)

![01-tela inicial](https://user-images.githubusercontent.com/8031302/200458556-3b5d09f2-c307-4e24-a423-f3f27c327c61.JPG)

(imagem 2 - escolher o que você é)

![02-tela inicial](https://user-images.githubusercontent.com/8031302/200458590-87e57ff5-62f8-4957-935b-670ed6059a71.JPG)

(imagem 3 - Escolher tempo de experiência/ contato como desenvolvedore)

![03-tela inicial](https://user-images.githubusercontent.com/8031302/200458604-fc76baf3-038b-43ed-b313-0c2c60bd453b.JPG)

(imagem 4 - escolher o modo dark)

![05-escolha da tela modo dark ou não](https://user-images.githubusercontent.com/8031302/200458622-464c9ad4-4a0f-4299-ba47-e9e3ee0982bf.JPG)

(imagem 5 - traduzindo a pagina pelo navegador)

![09 - mudar idioma pelo navegador](https://user-images.githubusercontent.com/8031302/200458683-3b6d8c02-6484-450a-9086-dd94beae1c19.jpg)

(imagem 6 - iniciar a preparação)

![10 - iniciar treinamento](https://user-images.githubusercontent.com/8031302/200458693-9b72ca36-b5e5-4e0b-9948-6bcd4241a66e.jpg)

(imagem 7 - escolher primeiro desafio para resolução)

![11 - iniciar treinamento 2](https://user-images.githubusercontent.com/8031302/200458706-733ef746-52ee-4c7c-81a0-42f268d25055.jpg)

(imagem 8 - enunciado do problema, lembrando que algumas empresas podem utilizar seus próprios desafios e em outras línguas que não o inglês.)

![12 - exercício 1 - contar numeros pos-neg-zeros e total de numeros](https://user-images.githubusercontent.com/8031302/200458737-4855707e-09a8-4ab9-a352-f75d2ecba13e.JPG)

(imagem 9 - escolher a linguagem de programação que será utilizada na resolução do desafio)

![13 - escolher linguagem para a resolução](https://user-images.githubusercontent.com/8031302/200458728-61f0c7b2-4c6c-48c8-9127-1552020a0b39.jpg)

(imagem 10 - no exercício temos a indicação de onde devemos dar sequência no código para desenvolver a solução)

![14 - no codigo terá marcado onde vc deve entrar com a sua solução - exemplo trabalharemos apenas um metodo](https://user-images.githubusercontent.com/8031302/200458735-bf44208f-472f-419e-866f-4366f610d3d2.jpg)

(imagem 11 - realize um teste clicando em Run Code, antes de submeter a solução na plataforma)

![18 - executar a aplicação para validar antes de submissão](https://user-images.githubusercontent.com/8031302/200458806-5e176a50-8b3a-42d8-8788-1934772a4ade.jpg)

(imagem 12 - envio da solução)

![15 - escreva seu codigo conforme a orientação dentro do local indicado e ao finalizar clicar em submit code](https://user-images.githubusercontent.com/8031302/200458750-9ea77761-cc23-41ae-9ecc-7d850445c27d.jpg)

(imagem 13 - imagem de como fica um exemplo de solução, a plataforma indica com marcação vermelha onde detectar erros)



![16 - solução dentro das chaves do método que o exercício indica para criar a solução](https://user-images.githubusercontent.com/8031302/200458768-9e3373a9-3a25-4316-a858-1e2851737df3.jpg)

(imagem 14 - exemplo do retorno ao enviar a solução correta)

![17 - envio da solução tela de validação](https://user-images.githubusercontent.com/8031302/200458831-7cbb35a0-cad2-4347-b1a7-5467e63a0f17.jpg)

