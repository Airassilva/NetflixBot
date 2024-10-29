# Netflix Assistant Chatbot

## Descrição
O Netflix Assistant Chatbot é uma aplicação de desktop interativa que permite aos usuários obter informações sobre filmes e séries da Netflix. Utilizando uma interface gráfica amigável, os usuários podem fazer perguntas sobre títulos específicos, diretores, anos de lançamento, gêneros e obter estatísticas gerais sobre o catálogo da Netflix.

## Características
- Interface gráfica intuitiva construída com customtkinter
- Busca por títulos, diretores, anos de lançamento e gêneros
- Exibição de estatísticas gerais sobre o catálogo da Netflix
- Base de dados atualizada de filmes e séries da Netflix

## Requisitos
- Python 3.7+
- pandas
- customtkinter
- gdown

## Instalação
1. Clone o repositório:
git clone https://github.com/Airassilva/NetflixBot.git

## Uso
1. Execute o script principal:
2. A interface gráfica será aberta. Você pode fazer perguntas como:
- "Mostre informações sobre [título]"
- "Quais filmes são dirigidos por [diretor]?"
- "Quais títulos foram lançados em [ano]?"
- "Mostre títulos do gênero [gênero]"
- "Mostrar estatísticas gerais"

## Estrutura do Projeto
- `netflixbot.py`: Script principal contendo a lógica do chatbot e a interface gráfica
- `netflix_movies (1).csv`: Dataset com informações sobre filmes e séries da Netflix (baixado automaticamente na primeira execução)

## Funcionalidades
1. **Busca por Título**: Retorna informações detalhadas sobre um título específico.
2. **Busca por Diretor**: Lista os títulos dirigidos por um diretor específico.
3. **Busca por Ano**: Mostra os títulos lançados em um determinado ano.
4. **Busca por Gênero**: Exibe títulos de um gênero específico.
5. **Estatísticas Gerais**: Fornece uma visão geral do catálogo, incluindo contagens de títulos e top diretores/gêneros.
