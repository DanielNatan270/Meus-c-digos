# Meus-c-digos
Compiladores e interpretadores 
Um compilador é um programa que traduz um código-fonte escrito em uma linguagem de programação de alto nível (como C, Java ou Pascal) para uma linguagem de baixo nível (geralmente código de máquina ou assembly), que pode ser diretamente executada por um computador.

🧠 Diferença entre Compilador e Interpretador

Característica	Compilador	Interpretador
Tradução	Traduz todo o código de uma vez	Traduz linha por linha
Tempo de execução	Mais rápido após a compilação	Mais lento
Exemplo	GCC (C), javac (Java)	Python, Ruby, JavaScript
🧱 Fases de um Compilador
Um compilador clássico tem várias fases, normalmente agrupadas em duas grandes partes: análise e síntese.

🔹 1. Análise (frente do compilador)
Análise Léxica (Scanner): Divide o código em tokens (palavras-chave, identificadores, operadores).

Análise Sintática (Parser): Garante que a estrutura do código segue a gramática da linguagem (ex: se os parênteses estão corretos).

Análise Semântica: Verifica o significado do código, como tipos de variáveis, uso correto de funções etc.

🔸 2. Síntese (traseira do compilador)
Geração de Código Intermediário: Transforma o código em uma forma intermediária (como bytecode).

Otimização de Código: Melhora o desempenho do código intermediário.

Geração de Código Final: Produz o código de máquina específico para o processador.

🧪 Exemplo Prático (Simplificado)
Código em C:

c
Copiar
Editar
int main() {
    printf("Olá mundo!");
    return 0;
}
Compilador C (como GCC) realiza:

Tokenização: int, main, (), {, etc.

Verificação sintática: estrutura correta da função.

Análise semântica: printf existe? main retorna int?

Geração de código intermediário e final.

🛠️ Tipos de Compiladores
Compiladores nativos: Produzem código de máquina diretamente (ex: GCC).

Compiladores para bytecode: Como o javac, que gera bytecode para a JVM.

Compiladores Just-In-Time (JIT): Como o do Java e .NET, que compilam partes do código em tempo de execução.

Transpiladores: Traduzem código de uma linguagem para outra (ex: TypeScript → JavaScript).

📚 Ferramentas de Construção de Compiladores
Lex e Yacc: Usados em sistemas Unix para gerar analisadores léxicos e sintáticos.

Flex e Bison: Alternativas modernas ao Lex/Yacc.

ANTLR: Ferramenta poderosa para análise sintática.

💡 Compiladores Famosos
GCC: GNU Compiler Collection — suporta C, C++, Fortran, etc.

Clang: Compilador moderno para C/C++, parte do LLVM.

javac: Compilador Java oficial.

Rustc: Compilador da linguagem Rust.


