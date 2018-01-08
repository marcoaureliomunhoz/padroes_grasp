# Padrões GRASP (General Responsibility Assignment Software Patterns)

Consiste em 9 princípios que podem ser usadas para atribuir responsabilidades a classes e objetos em projetos orientados a objetos.

- **Information Expert** (Especialista na Informação)
- **Creator** (Criador)
- **Low Coupling** (Baixo Acoplamento)
- **High Cohesion** (Alta Coesão)
- **Controller** (Controlador)
- **Polymorphism** (Polimorfismo)
- **Pure Fabrication** (Fabricação Pura)
- **Protected Variations** (Variações Protegidas)

---

**Information Expert** (Especialista na Informação)

- **Problema**: qual o princípio básico para se atribuir responsabilidades a objetos?
- **Solução**: atribuir a responsabilidade a quem tem a informação necessária para realiza-la.

**Creator** (Criador)

- **Problema**: quem deve ser o responsável por criar uma nova instância de uma classe?
- **Solução**: a classe A deve ser responsável por criar uma instância da classe B, se:  
    - A agrega objetos da classe B
    - A contém objetos de B
    - A armazena instâncias de B
    - A, de forma privada, usa instâncias de B
    - A tem os dados necessários para inicializar B

**Low Coupling** (Baixo Acoplamento)

- **Problema**: como reduzir o impacto de mudanças?
- **Solução**: atribuir responsabilidade de forma a manter o acoplamento baixo (baixa dependência).

**High Cohesion** (Alta Coesão)

- **Problema**: como manter os objetos focados, fáceis de entender, gerenciáveis e ainda pouco acoplados?
- **Solução**: atribuir responsabilidade de forma a manter a coesão funcional alta.

**Controller** (Controlador)

- **Problema**: quem deve responder aos eventos de sistema?
- **Solução**: atribuir responsabilidade a uma classe que represente todo um sistema ou represente os serviços de um módulo ou subsistema. É a classe raiz do sistema/módulo.

---

**Fontes**
- https://www.youtube.com/watch?v=IdQjsAcgtNM
- https://pt.wikipedia.org/wiki/GRASP_(padr%C3%A3o_orientado_a_objetos) 
