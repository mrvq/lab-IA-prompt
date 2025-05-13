# Tarefa: Board de Tarefas com Spring Boot

## Descrição
Projeto que simula um Trello simplificado usando Java com Spring Boot, com CRUD de Boards, Listas e Cards.

## Prompt Usado
> Gere um projeto Spring Boot com CRUD para entidades Board, TaskList e Card, relacionando-as em estrutura de Kanban.

## Resultado
Foram geradas as entidades, repositórios, controladores e configuração H2. O código foi testado via Postman.

## Código Exemplo
```java
@Entity
public class Card {
    @Id @GeneratedValue
    private Long id;
    private String title;
    private String description;
}
```