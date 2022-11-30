
# Comandos do Markdown ✍📝

# Títulos:

Para criar títulos, use a Hashtag.
1 Hashtag = título principal
2 Hashtags = subtítulo
3 Hashtags = subtítulo do subtítulo e assim por diante...

**Exemplo:**

```
# Título 1
## Título 2
### Título 3

```
**Resultado:**

# Título 1
## Título 2
### Título 3

---




# Negrito:

```
**palavras em negrito**

 OU 
 
__palavras em negrito__ 

```
**Resultado:** 

**palavras em negrito**





# Itálico 

```
*palavras em itálico*

OU 

_palavras em itálico_

```

**Resultado:**

*palavras em itálico* 




# Negrito e Itálico ao mesmo tempo:

```
__*Negrito e Itálico ao mesmo tempo*__

OU

**_Negrito e Itálico ao mesmo tempo_**

```

**Resultado:**

__*Negrito e Itálico ao mesmo tempo*__



# Listas Numeradas: 

só coloque um número e um ponto e a lista do markdown vai se adaptar automaticamente

```
1. Item 1
1. Item 2 
1. Item 3
   1. Subitem 3.1
   1. Subitem 3.2
   1. Subitem 3.3
1. Item 4
1. Item 5

```

**Resultado:**


1. Item 1
1. Item 2 
1. Item 3
   1. Subitem 3.1
   1. Subitem 3.2
   1. Subitem 3.3
1. Item 4
1. Item 5



# Listas com Marcadores ou listas demarcadas: 

Asterisco ou traço para criar a lista.

**Exemplo: **

``` 
* Item 1
* Item 2
* Item 3
  * Subitem 3.1
  * Subitem 3.2
  * Subitem 3.3
* Item 4
* Item 5


OU


- item 1
- item 2
- item 3
   - subitem 3.1
   - subitem 3.2
   - subitem 3.3
- item 4
- item 5

```


**Resultado:**

* Item 1
* Item 2
* Item 3
  * Subitem 3.1
  * Subitem 3.2
  * Subitem 3.3
* Item 4
* Item 5


# Linhas:

Apenas digite 3 asteriscos ou 3 linhas.

**Exemplo: **

```
lorem ipsulum

***

OU 

texto text
---

```
**Resultado:**

lorem ipsulum

***

OU 

texto text
---

# Listas de Tarefas ou Checklist

Coloque o traço seguido de chaves com espaço para criar itens desmarcados e traço seguido de chaves com x no meio para criar itens marcados

**Exemplo:**

```
- [x] item 1
- [ ] item 2
- [x] item 3
- [ ] item 4
- [ ] item 5

```

**Resultado:**

- [x] item 1
- [ ] item 2
- [x] item 3
- [ ] item 4
- [ ] item 5


# Comandos:

Utilize crase para especificar que é um comando.

**Exemplo:**

```
"Alguém poderia me explicar o que faz o comando `System.out.println()`"?

``` 

**Resultado:**

"Alguém poderia me explicar o que faz o comando `System.out.println()`"?


# Responder citação: 

Para responder alguém coloque o sinal de maior. 

**Exemplo:**

```
Vi que você fez essa pergunta:

> Alguém poderia me explicar o que faz o comando System.out.println()?

Esse comando serve para imprimir um texto na tela em java, e saltar para a linha de baixo.

Por exemplo: `System.out.println("Olá Mundo");`

```

**Resultado:**

Vi que você fez essa pergunta:

> Alguém poderia me explicar o que faz o comando System.out.println()?

Esse comando serve para imprimir um texto na tela em java, e saltar para a linha de baixo.

Por exemplo: `System.out.println("Olá Mundo");`


# Código

Para mostrar um código utilize 3 crases seguidas. é o que estou fazendo em todos esses exemplos em que a tela fica com o fundo cinza.

**Exemplo:**


![examplo programação](https://user-images.githubusercontent.com/78625466/204804995-b817b50d-3a34-44c4-af87-cc630fb16457.PNG)




**Resultado:**

```
Scanner sc = new Scanner(System.in);

System.out.println("Digite um número:");
double num = sc.nextDouble();

if(num%2 == 0) {
  System.out.printf("%d é PAR", num);
} else {
  System.out.printf("%d é ÍMPAR", num);
}


```

ou se achar mais fácil postar direto uma imagem do código no seu computador.


# Postar Imagens e GIFs

Para postar imagens ou gifs como fiz acima é só pegar a imagem desejada e jogar em cima do arquivo markdown. Ele vai ficar com uma leitura parecida com essa:

```

![atletico-mineiro](https://user-images.githubusercontent.com/78625466/204806417-31eab862-c4de-4b02-a794-6ce3f09de70f.png)


```

**Resultado:**

![atletico-mineiro](https://user-images.githubusercontent.com/78625466/204806465-54548a92-b433-4cfb-8ae6-2588cebaed68.png)


**PARA GIFS É A MESMA COISA**

```
![brazil](https://user-images.githubusercontent.com/78625466/204805921-3b21a9a4-4ac4-441b-9c7f-30a9ffb97c41.gif)


``` 
**Resultado:**


![brazil](https://user-images.githubusercontent.com/78625466/204806022-a39e46de-4a60-4b72-99e4-7c06faacf277.gif)


# Inserir Links: 

Para inserir links você deve colocar uma frases entre chaves e o link entre parênteses. 

**Exemplo:**

```

[Meu Github Principal](https://github.com/BrunoSilva03)

[Meu gitHub Secundário](https://github.com/BrunoSilva05)


```

**Resultado:**

[Meu Github Principal](https://github.com/BrunoSilva03)

[Meu gitHub Secundário](https://github.com/BrunoSilva05)


# Criando Tabelas


A sintaxe das tabelas é assim: 

```
Id | Nome | Vendas | Preço | Saldo final do mês
---|---|---|---|---
1 | Milho | 7 | 0,80 | POSITIVO
2 | Sabonete | 500 | 2,00 | POSITIVO
3 | Vaso de Planta | 2 | 50 | NEGATIVO
4 | Canetas | 20 | 0,50 | NEGATIVO
5 | Sorvete | 150 | 10,00 | POSITIVO


```

**Resultado:**

Id | Nome | Vendas | Preço | Saldo final do mês
---|---|---|---|---
1 | Milho | 7 | 0,80 | POSITIVO
2 | Sabonete | 500 | 2,00 | POSITIVO
3 | Vaso de Planta | 2 | 50 | NEGATIVO
4 | Canetas | 20 | 0,50 | NEGATIVO
5 | Sorvete | 150 | 10,00 | POSITIVO


# Mencionar outro usuários:

Para mencionar coloque o "@" mais o nome de usuário de quem deseja mencionar.

**Exemplo:**

```
O usuário @BrunoSilva05 fez um código parecido com este.

```

**Resultado:**

O usuário @BrunoSilva05 fez um código parecido com este.

# emojis

Você pode usar emojis no padrão markdown que é digitando dois pontos mais o nome do emoji:

```
:fire:

```

**Resultado**

:fire:

ou da maneira mais simples que é usar os recursos do próprio computador para colocar o emoji.
Se estiver usando o Windows tecle **Windows** mais **.** que irá abrir o menu de emojis e você escolhe quais e quantos quiser.
_Se for o mac seria **command** mais **.**_

**Exemplo**

![lista de emojis do windows](https://user-images.githubusercontent.com/78625466/204813711-75b0e830-76bf-41d7-a737-7a699e31cbcb.PNG)

**Resultado**

 ## 😁🤣👨‍💻🚨🧠✨🎶🌌🎨💥💖🐱😎😋⚡😀🔥

