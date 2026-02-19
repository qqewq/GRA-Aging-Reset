# links_epigenetic_clock_repos.md

Список основных публичных репозиториев и ресурсов по эпигенетическим часам, которые можно использовать как источники кода, данных и описаний моделей. [github](https://github.com/mdozmorov/Aging_clock)

***

## 1. Обзорные и сборочные репозитории

### 1.1. Aging_clock

- Repo: `https://github.com/mdozmorov/Aging_clock` [github](https://github.com/mdozmorov/Aging_clock/blob/master/README.md)
- Описание:  
  - коллекция ссылок на статьи и данные по эпигенетическим часам;  
  - README с обзором основных моделей (Horvath, Hannum, PhenoAge, GrimAge и др.);  
  - полезная точка входа в тему.

***

## 2. Калькуляторы и пайплайны

### 2.1. epical

- Repo: `https://github.com/liguowang/epical` [github](https://github.com/liguowang/epical)
- Описание:  
  - «repository of epigenetic age calculators»;  
  - реализованы несколько популярных часов;  
  - удобен для применения часов к своим данным метилирования (Illumina и др.).

### 2.2. EpigeneticAgePipeline

- Repo: `https://github.com/CastellaniLab/EpigeneticAgePipeline` [github](https://github.com/CastellaniLab/EpigeneticAgePipeline)
- Описание:  
  - пайплайн для расчёта эпигенетического возраста;  
  - включает шаги по препроцессингу, применению разных моделей и анализу эпигенетического ускорения.

***

## 3. Многовидовые часы (животные модели)

### 3.1. mammalian-methyl-clocks

- Repo: `https://github.com/jazoller96/mammalian-methyl-clocks` [github](https://github.com/jazoller96/mammalian-methyl-clocks)
- Описание:  
  - коэффициенты и возрастные трансформации для множества эпигенетических часов у млекопитающих и других видов;  
  - база для экспериментов по старению на животных (мыши, собаки и др.).

***

## 4. Демонстрационные и учебные проекты

### 4.1. Epigenetic-Clock (малый пример)

- Repo: `https://github.com/AkshajD/Epigenetic-Clock` [github](https://github.com/AkshajD/Epigenetic-Clock)
- Описание:  
  - простой пример анализа метилирования на 6 CpG‑сайтах в крови;  
  - предсказание возраста с помощью ML;  
  - полезен для понимания базовой методики на маленьком датасете.

***

## 5. Как этим пользоваться в рамках репозитория

- Для теории GRA:  
  - эти репозитории дают **конкретные реализации** численной меры пены на эпигенетическом мета‑уровне (\(\Phi^{(M)}\)). [providence.elsevierpure](https://providence.elsevierpure.com/en/publications/loss-of-epigenetic-information-as-a-cause-of-mammalian-aging)

- Для практики:  
  - их можно подключать к своим данным, чтобы оценивать биологический возраст до/после интервенций (lifestyle, фармакология, экспериментальные подходы). [github](https://github.com/mdozmorov/Aging_clock)

- Для дальнейшей работы в этом репо:  
  - добавить сюда примеры использования (`epigenetic_clock_tools.md`), небольшие скрипты/ноутбуки, которые показывают step‑by‑step, как считать эпигенетический возраст и строить графики изменений.