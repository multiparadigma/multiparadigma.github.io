

# Jekyll como aperitivo

Se você é como eu, e está dando os seus primeiros passos no mundo da programação,
já deve ter notado que muitos desenvolvedores gostam de manter um blog pessoal, seja para publicações pessoais e/ou técnicas, ou para expor o próprio currículo. Nós usaremos uma ferramenta para gerar um *esqueleto de site estático* que será customizado de acordo com as suas preferências

Você não aprenderá a programar, de fato, enquanto não transcender as limitações exteriores, isto é, as exigências da sociedade de mercado, e focar exclusivamente numa paixão pessoal. Assim sendo, vamos começar com um projeto simples e de escopo pequeno. Mas se você ainda não encontrou a sua vocação, continue procurando.

Agora é o momento para você desenvolver um pouco mais de paixão pela arte de escrever código.

## Alguns requisitos padrões para usar Jekyll

1. Ambiente Ruby (2.2.5) de desenvolvimento
2. Gerenciador de pacotes (RubyGems)
3. gcc/Make


Verifique se os softwares necessários estão instalados:


```
ruby -v
```

```
gcc -v
```

```
g++ -v
```

```
make -v​	
```


Para instalar Ruby no Fedora:

```
sudo dnf install ruby ruby-devel @development-tools
```

Para instalar Ruby no Debian:

```
sudo apt-get install ruby-full build-essential
```
Ubuntu:

```
sudo apt-get install ruby-full build-essential zlib1g-dev
```


## Como instalar a ferramenta Jekyll


```
gem install jekyll bundler
```

No diretório de sua escolha, digite o seguinte:


```
jekyll new nome-do-seu-blog
```


```
cd nome-do-seu-blog
```


```
bundle exec jekyll serve 
```


Nos próximos passos, aprenderemos como hospedar o blog criado usando o serviço disponibilizado pelo GitHub, e, em seguida, aprenderemos com mais calma um pouco mais sobre a estrutura de diretórios que foram automaticamente geradas pelo Jekyll.