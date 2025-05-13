# Prompts Gerais

## ✅ Resumo Automático

**Prompt:**  
> Resuma o seguinte texto em até 3 frases com foco nos pontos principais.

**Exemplo de uso:**  
Texto original: artigo científico de 5 páginas.  
Resumo gerado: *"Este estudo explora o impacto das mudanças climáticas nas áreas urbanas, focando em planejamento sustentável. Conclui-se que políticas públicas precisam priorizar infraestrutura verde. A pesquisa apresenta evidências de sete cidades latino-americanas."*

---

## ✅ Reescrita com Tom Específico

**Prompt:**  
> Reescreva o parágrafo abaixo com tom mais informal, adequado para redes sociais.

**Original:**  
"A produtividade empresarial está diretamente ligada à gestão de tempo eficiente."

**Resultado:**  
"Quer render mais no trampo? Aprende a dominar teu tempo que o resto vem!"

---

## ✅ Explicação de Conceitos Complexos

**Prompt:**  
> Explique o que é 'machine learning' como se eu tivesse 10 anos.

**Resultado:**  
"Machine learning é quando o computador aprende sozinho, tipo como a gente aprende com os erros."

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
