# [Clean Architecture](http://niquola.github.io/happydev-2013-slides/)

My slides for [happydev.2013](http://2013.happydev.ru)

### Что такое АРХИТЕКТУРА?

> Software Architecture as a Set of Architectural Design Decisions

[A. Jansen & J. Bosch](http://new.csd.uwo.ca/courses/CS4471b/secure/Additional%20Resources/020_Architectures.dir/1_WICSA_Confs/WICSA_2005_Pittsburgh/2005_papers/18500111.pdf)

### Решение это часто компромис

Умные люди знают, любое решение имеет обратную сторону (tradeoff)

У монеты две стороны; У палки два конца

* CAP & Basically Available, Soft-state, Eventually consistent
* Простота и Гибкость
* Модульность и монолитность

### Это сокрыто в природе вещей

[Три закона диалектики](http://ru.wikipedia.org/wiki/%D0%97%D0%B0%D0%BA%D0%BE%D0%BD%D1%8B_%D1%84%D0%B8%D0%BB%D0%BE%D1%81%D0%BE%D1%84%D0%B8%D0%B8#.D0.92_.D0.B4.D0.B8.D0.B0.D0.BB.D0.B5.D0.BA.D1.82.D0.B8.D1.87.D0.B5.D1.81.D0.BA.D0.BE.D0.BC_.D0.BC.D0.B0.D1.82.D0.B5.D1.80.D0.B8.D0.B0.D0.BB.D0.B8.D0.B7.D0.BC.D0.B5)

*Закон единства и борьбы противоположностей*

> Движение и развитие в природе, обществе и мышлении
> обусловлено раздвоением единого на взаимопроникающие противоположности
> и разрешением возникающих противоречий между ними через борьбу

### Разница только в том насколько осознано вы выбираете

Иногда полезно использовать негативное определение
(ибо в порыве вдохновения о темной стороне часто забывают).

Хорошее решение уменьшает кол-во негативных последствий

>  Основная задача дизайна уменьшить боль, а не увеличить количество ништяков!
>  Нет хорошей или плохой архитектуры - она может быть обоснованной или нет

[Тренинг «Проектирование обоснованной архитектуры», Евгений Кривошеев](http://jugru.timepad.ru/event/80808/)

### LEAN manufacturing (производственные концепции и практики Toyota)

Делая выбор, порой забывают, что есть еще одна опция - "Отложить этот выбор"

> good architecture maximizes
> the number of decisions
> not made

Robert Martin (Uncle Bob)</h4>

### Архитектура не висит в воздухе

Мы часть бизнесс-механизма, производящего ПО

Свое подтверждение архитектура должна выводить из требований
Требования из бизнесс модели

![semat](semat.png)

Принимающие архитектурные решения должны в достаточной степени понимать это.
Например некоторые противоречия могут быть разрешены только уровнем выше.

### System Thinking

> Design is taking things apart
> and then compose


### Modularity vs Monolitic

### Bounded Contexts & Aggregates

## Сложная предметная область?
### Induction vs Deduction


### Behaviour Driven
Важнее то как система себя ведет
нежели то как она устроена

### Use Case
Последовательность взаимодействий с системой направленная на достижение цели

### TDD mantra

### Преждевремменное моделирование сложной предметной области корень множества проблем

### Выпрямление

* Use Case
* Prototype
* Specification
* Implementation
* Refactoring to deeper insight

### Закон Конвея & Кайдзен
![](kaizen.png)
