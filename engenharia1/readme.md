#Primeira Atividade da Disciplina de Engenharia de Software

## Comentários sobre o livro "Software Engineering at Google, Oreilly"

### Primeiro Trecho

> **What precisely do we mean by software engineering? What distinguishes “software engineering” from “programming” or “computer science”? And why would Google have a unique perspective to add to the corpus of previous software engineering literature written over the past 50 years?**
> 
> The terms “programming” and “software engineering” have been used interchangeably for quite some time in our industry, although each term has a different emphasis and different implications. University students tend to study computer science and get jobs writing code as “programmers.”
> 
> “Software engineering,” however, sounds more serious, as if it implies the application of some theoretical knowledge to build something real and precise. Mechanical engineers, civil engineers, aeronautical engineers, and those in other engineering disciplines all practice engineering. They all work in the real world and use the application of their theoretical knowledge to create something real. Software engineers also create “something real,” though it is less tangible than the things other engineers create.
> 
> Unlike those more established engineering professions, current software engineering theory or practice is not nearly as rigorous. Aeronautical engineers must follow rigid guidelines and practices, because errors in their calculations can cause real damage; programming, on the whole, has traditionally not followed such rigorous practices. But, as software becomes more integrated into our lives, we must adopt and rely on more rigorous engineering methods. We hope this book helps others see a path toward more reliable software practices.

#### Comentário

Este primeiro trecho apresenta a premissa central da discussão: o que é a engenharia de software e como ela se diferencia da programação ou da ciência da computação. Ele aborda a evolução da prática da programação para algo mais estruturado, comparando-a com disciplinas de engenharia mais tradicionais, como a mecânica ou a civil.

- A distinção entre “programming” e “software engineering” é apresentada de forma clara, sugerindo que esta última envolve um grau maior de rigor e aplicação teórica.
- Um ponto interessante é como o texto destaca a falta de padronização ou rigor na engenharia de software em comparação com outras engenharias mais tradicionais. Isso reflete os desafios específicos da área, como a intangibilidade dos produtos criados.
- A referência ao impacto crescente do software na sociedade serve como uma justificativa para a necessidade de práticas mais sólidas e confiáveis.

---

### Segundo Trecho

> **Programming Over Time**  
> We propose that “software engineering” encompasses not just the act of writing code, but all of the tools and processes an organization uses to build and maintain that code over time. What practices can a software organization introduce that will best keep its code valuable over the long term? How can engineers make a codebase more sustainable and the software engineering discipline itself more rigorous? We don’t have fundamental answers to these questions, but we hope that Google’s collective experience over the past two decades illuminates possible paths toward finding those answers.
> 
> One key insight we share in this book is that software engineering can be thought of as “programming integrated over time.” What practices can we introduce to our code to make it sustainable—able to react to necessary change—over its life cycle, from conception to introduction to maintenance to deprecation?
> 
> The book emphasizes three fundamental principles that we feel software organizations should keep in mind when designing, architecting, and writing their code:
> 
> - **Time and Change**  
>   How code will need to adapt over the length of its life
> 
> - **Scale and Growth**  
>   How an organization will need to adapt as it evolves
> 
> - **Trade-offs and Costs**  
>   How an organization makes decisions, based on the lessons of Time and Change and Scale and Growth

#### Comentário

O segundo trecho expande o conceito de engenharia de software para incluir não apenas a escrita de códigos, mas também todos os processos e ferramentas utilizados para manter o código valioso ao longo do tempo. 

- A idéia de "programming integrated over time" é uma contribuição essencial, pois sugere que as práticas devem levar em consideração todo o ciclo de vida do software, desde sua concepção até a descontinuação.
- A introdução dos princípios fundamentais é extremamente valiosa para guiar organizações no desenvolvimento de práticas mais eficazes. Em particular:
  - **Time and Change** aborda a adaptabilidade do código ao longo de sua vida.
  - **Scale and Growth** reconhece o impacto do crescimento organizacional e a necessidade de escalabilidade.
  - **Trade-offs and Costs** destaca a importância de decisões ponderadas, considerando os custos e benefícios.
- Este trecho também reforça a ideia de que, embora não haja respostas definitivas, a experiência coletiva do Google ao longo de décadas pode iluminar caminhos para soluções mais eficazes.


## Exemplos de Tradeoffs

O conceito de **tradeoff** refere-se à necessidade de tomar decisões entre alternativas que possuem benefícios e custos conflitantes. Em diversas áreas, os tradeoffs ajudam a balancear objetivos opostos e tomar decisões informadas. Abaixo, estão três exemplos comuns de tradeoffs:

### 1. **Qualidade vs. Velocidade no Desenvolvimento de Software**
Durante o desenvolvimento de software, muitas vezes existe um tradeoff entre **qualidade** e **velocidade**. Se a prioridade é entregar o produto rapidamente, pode ser necessário comprometer a qualidade, resultando em um código menos otimizado, com maior probabilidade de bugs. Por outro lado, se a qualidade é priorizada, o desenvolvimento pode demorar mais, aumentando o custo e o tempo para entrega.

- **Qualidade**: código bem testado e robusto, mais tempo de desenvolvimento.
- **Velocidade**: entrega mais rápida, mas pode gerar mais erros e falhas.

### 2. **Custo vs. Benefício em Produção**
Ao decidir entre diferentes métodos ou materiais para a produção de bens, existe um tradeoff entre o **custo** e o **benefício**. Um processo mais barato pode reduzir custos no curto prazo, mas pode resultar em produtos de menor qualidade ou maior custo no longo prazo devido a defeitos e problemas. Por outro lado, investir em uma opção mais cara pode aumentar a qualidade e a durabilidade, mas eleva o custo inicial.

- **Custo**: redução no preço de produção, mas risco de qualidade inferior.
- **Benefício**: maior qualidade e durabilidade, mas aumento nos custos.

### 3. **Desempenho vs. Consumo de Energia em Dispositivos Eletrônicos**
Em dispositivos eletrônicos, como smartphones ou laptops, existe um tradeoff entre **desempenho** e **consumo de energia**. Processadores de alto desempenho geralmente consomem mais energia, o que pode reduzir a duração da bateria. Já processadores mais eficientes energeticamente podem oferecer um desempenho inferior, resultando em um equilíbrio entre eficiência e capacidade de processamento.

- **Desempenho**: maior capacidade de processamento, mas maior consumo de energia.
- **Consumo de Energia**: menor consumo de energia, mas desempenho reduzido.

### Conclusão
Os tradeoffs são parte integrante de muitas decisões e é importante avaliá-los cuidadosamente com base nas necessidades e prioridades de cada situação.

