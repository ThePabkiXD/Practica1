```mermaid
flowchart TD
    A[Inicio] --> B[Crear Ejercicio1]
    B --> C[Inicializar adyasencia = new HashMap<>]
    C --> D[agregarVertice: A, B, C, D, E]
    D --> E[agregarArista: A→B, A→C, B→D, C→D, D→E]
    E --> F[mostrarGrafo]
    F --> G[Para cada vértice en adyasencia]
    G --> H[Imprimir "vértice -> lista_adyacencia"]
    H --> G
    G --> I[Fin]
