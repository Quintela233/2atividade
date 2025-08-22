# Esse reposiório descreve 3 ténicas dentro de POO

# Herança

Permite reutilização de código onde uma classe filha herda características da classe pai
Evita repetição, mas pode deixar o sistema confuso se usado excessivamente
Alternativa: usar composição

# Composição / Associação

Conecta classes através de relacionamentos "tem um" ao invés de "é um" (herança)
Exemplos: pessoa tem endereço, professor tem alunos, aluno está em turmas
Mais flexível que herança

# Injeção de Dependencia

Técnica para passar dependências de uma classe "de fora para dentro"
Ao invés da classe criar suas próprias dependências, ela as recebe prontas
Torna o código mais flexível e fácil de manter
Exemplo: ao invés de "Carro cria Motor", você passa o motor pronto para o carro
