# my-profile
plain text
&nbsp;
yippee

# H1

## H2

### H3

#### H4

##### H5

###### H6

####### H7

*italics*

_also italic_

**bold**

__also bold__




## Github flavoured markdown

My `CustomerService` class uses the `CustomerRepository` for its constructor injection

```sql
SELECT * FROM customers;
```

```java
public static void main(String[] args){
    System.out.println("Hello world");
}
```

```C#
public static void main(String[] args){
    Console.WriteLine("Hello world");
}
```

## Task Lists

- [ ] Do something
- [x] Do something else

## Tables

| Name | Street | Town |
|------|--------|------|
|Nish|Walmey St.|Brum|
|Cathy|123 St|Stafford

## Mermaid

### Graph

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

### Sequence diagram

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop HealthCheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

### Database Schema

```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses

```

### Sparta Academy Project Database Schema

```mermaid
erDiagram
    Course }o--o{ Trainee : has
    Course }|--|{ Trainer : teaches

    Course{
        
    }
```