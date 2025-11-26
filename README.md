# 🎵 Sistema de Avaliação de Músicas

Um projeto simples e direto em Java para gerenciar informações de músicas e suas avaliações. Perfeito para quem está começando a entender programação orientada a objetos!

## 💡 O que faz?

Este projeto permite cadastrar músicas com suas informações básicas (título, artista, ano) e receber avaliações dos ouvintes. No final, ele calcula a média das notas dadas.

## 🚀 Como funciona

O sistema tem duas classes principais:

**Musica.java** - A classe que representa uma música e guarda todas as informações dela

**Main.java** - Onde a mágica acontece! Aqui criamos uma música e testamos o sistema

### Exemplo de uso

```java
Musica musica = new Musica();
musica.titulo = "Musica do weid desenvolvedor";
musica.artista = "Weid";
musica.anoLancamento = 2025;

// Avaliar a música
musica.avaliaMusica(8);
musica.avaliaMusica(8);
musica.avaliaMusica(5);

// Ver a média
double media = musica.calculaMediaAvaliacoes();
```

## 🎯 Funcionalidades

- Cadastro de título e artista
- Registro do ano de lançamento
- Sistema de avaliações com notas
- Cálculo automático da média das avaliações
- Exibição de ficha técnica completa

## 🛠️ Tecnologias

- Java
- POO (Programação Orientada a Objetos)

## 📦 Como usar

**1. Clone o repositório:**

```bash
git clone https://github.com/seu-usuario/sistema-avaliacoes-musica.git
```

**2. Compile os arquivos:**

```bash
javac Musica.java Main.java
```

**3. Execute o programa:**

```bash
java Main
```

## 📝 O que aprendi

Este projeto foi uma forma de praticar:

- Criação de classes e objetos
- Atributos e métodos
- Manipulação de dados
- Cálculos com valores acumulados

## 🤝 Contribuições

Sinta-se à vontade para sugerir melhorias! Algumas ideias para expandir:

- Adicionar validação de notas (0-10)
- Criar uma lista de múltiplas músicas
- Adicionar gênero musical
- Implementar busca por artista

## 👤 Autor

Desenvolvido por **Weid** - Um desenvolvedor aprendendo e evoluindo cada dia! 🚀

---

⭐ Se este projeto te ajudou de alguma forma, deixa uma estrela aí!
