```mermaid

derDiagram
    USUARIO {
        int id
        string nome
        string email
        string senha
    }

    EVENTO {
        int id
        string titulo
        datetime data_hora
        string local
        string descricao
        int usuario_id
    }

    PARTICIPANTE {
        int id
        string nome
        string email
        string telefone
        int evento_id
    }

    CHECKLIST {
        int id
        string item
        boolean concluido
        int evento_id
    }

    NOTIFICACAO {
        int id
        string mensagem
        datetime data_envio
        int evento_id
    }

    USUARIO ||--o{ EVENTO : "cria"
    EVENTO ||--o{ PARTICIPANTE : "tem"
    EVENTO ||--o{ CHECKLIST : "possui"
    EVENTO ||--o{ NOTIFICACAO : "gera"
```mermaid
