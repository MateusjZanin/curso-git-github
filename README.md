# Curso de Git \& GitHub para Ciência de Dados

1. Repositórios com Curadoria de Textos e Recursos 
Estes projetos reúnem listas de sites, livros e artigos ideais para praticar leitura:
Awesome English: Uma das coleções mais completas, com links para notícias em inglês simplificado, contos curtos e exercícios de compreensão.
English Learning Resources: Oferece acesso a bibliotecas digitais gratuitas como o Project Gutenberg (com mais de 75.000 eBooks) e o Open Textbook Library.
Useful Websites for English Learners: Focado em sites que oferecem vocabulário e textos de apoio para níveis variado.

2. Geradores de Texto Aleatório (Tools)
Se você é programador ou quer gerar massa de dados/texto para testes, existem bibliotecas específicas:
txtgen: Um utilitário leve para gerar frases, parágrafos e até artigos inteiros aleatórios em inglês.
Random-Word: Uma biblioteca Python simples para gerar palavras aleatórias do dicionário.
Wonderwords: Ótima para criar frases estruturadas aleatoriamente (ex: "The blue cat runs quickly").

3. Ferramentas de Leitura Ativa
Learning with Texts (LWT): Uma ferramenta clássica hospedada no GitHub que permite importar qualquer texto em inglês para ler, traduzir termos desconhecidos e criar cartões de memória (flashcards) automaticamente. 
Dica: Se você quer textos técnicos para praticar o inglês voltado para programação, explore a aba Explore do próprio GitHub ou a documentação de projetos famosos (como o React ou VS Code), que são escritos de forma muito clara. 
Você está procurando textos para estudar o idioma ou precisa de geradores de texto para usar em algum projeto de programação?

## Fluxo de trabalho Git local

1. git checkout -b - nova branch
2. cria ou atualzia arquivos
3. git status
4. git add .
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)

1. git clone
2. git checkout -b <nova_branch>
3. alterações de arquivos
4. git status
5. git add arquivos
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova_branch>
9. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)
1. Fork do projeto para seu próprio github
2. git clone
3. git checkout -b <nova_branch>
4. alterações de arquivos
5. git status
6. git add arquivos
7. git status
8. git commit -m "nova mensagem"
9. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>