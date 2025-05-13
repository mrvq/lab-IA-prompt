# Prompts para Geração de Código

## ✅ CRUD com Spring Boot

**Prompt:**  
> Gere um CRUD completo em Spring Boot para uma entidade `Produto` com campos `id`, `nome`, `preco`.

**Resultado:**  
Código com @RestController, ProductRepository (JpaRepository), ProductService, e endpoints RESTful prontos.

---

## ✅ Refatoração de Código

**Prompt:**  
> Reescreva este código Java para usar streams no lugar de for-loops.

**Antes:**  
```java
List<String> upper = new ArrayList<>();
for(String s : lista) {
    upper.add(s.toUpperCase());
}
```

**Depois:**  
```java
List<String> upper = lista.stream()
    .map(String::toUpperCase)
    .collect(Collectors.toList());
```

---

## ✅ Testes Automatizados

**Prompt:**  
> Gere testes com JUnit para o controller `ProdutoController`.

**Resultado:**  
Testes com `@WebMvcTest`, uso de `MockMvc` e verificação de status e JSON retornado.