// Estrutura de definição para os nós da lista vinculada
struct reg {
    float item;
    struct reg *prox;
};
typedef struct reg NO;

// Função para calcular o índice de hash
int funcaohash(float);

// Função para inicializar a tabela de hash
void inicializa(NO **);

// Função para inserir um elemento na tabela de hash
void insere(float, NO **);

// Função para imprimir a tabela de hash
void imprime(NO **);

// Função para liberar a memória usada pela tabela de hash
void libera(NO **);

// Função para excluir um elemento da tabela de hash
void apaga(float, NO **);

// Função para inserir um elemento na lista vinculada em um índice específico
void inserelista(float,  NO **);

// Função para percorrer a lista vinculada em um índice específico
void percorrelista(int,  NO **);

// Função para procurar um elemento na lista vinculada em um índice específico
int buscarlista(float, NO **);

// Função principal
int main() {
    // Declarar e inicializar a tabela de hash
    NO *HASH[TAM_MAX];
    inicializa(HASH);

    // Inserir 10 elementos na tabela de hash
    for (i = 0; i < 10; i++) {
        // ...
    }

    // Imprimir a tabela de hash
    imprime(HASH);

    // Excluir elementos da tabela de hash
    while (1) {
        // ...
    }

    // Liberar a memória usada pela tabela de hash
    libera(HASH);

    // Sair do programa
    return 0;
}

// Função para calcular o índice de hash
int funcaohash(float chave) {
    return abs(chave) % TAM_MAX;
}

// Função para inicializar a tabela de hash
void inicializa(NO **HASH) {
    int i;
    for (i = 0; i < TAM_MAX; i++)
        HASH[i] = NULL;
}

// Função para inserir um elemento na tabela de hash
void insere(float item, NO **HASH) {
    // ...
}

// Função para inserir um elemento na lista vinculada em um índice específico
void inserelista(float item, NO **HASH) {
    // ...
}

// Função para imprimir a tabela de hash
void imprime(NO **HASH) {
    // ...
}

// Função para liberar a memória usada pela tabela de hash
void libera(NO **HASH) {
    // ...
}

// Função para excluir um elemento da tabela de hash
void apaga(float item, NO **HASH) {
    // ...
}

// Função para procurar um elemento na lista vinculada em um índice específico
int buscarlista(float item, NO **HASH) {
    // ...
}

// Função para percorrer a lista vinculada em um índice específico
void percorrelista(int pos, NO **HASH) {
    // ...
}
