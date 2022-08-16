# C++ FAQ
В этом репозитории собрана основная информация с часто
задаваемыми вопросами и полезными источниками.

---

### :pushpin: Как оно работает :pushpin: ###
##### Основные источники к которым обращаются разработчики на С++ когда возникает вопрос, а как это работает (должно работать) #####

* [Документация по С++ (cppreference)](https://en.cppreference.com/w)
* [Последний драфт стандарта (Working Draft)](http://eel.is/c++draft/)
* [Платформа вопросов и ответов по программированию (stackoverflow)](https://stackoverflow.com/questions/tagged/c%2b%2b)
* [Взгляните на свой исходный код глазами компилятора (C++ Insights)](https://cppinsights.io)

---

### :pushpin: Где (как) запустить, посмотреть и поделиться кодом :pushpin: ###
##### Основные сервисы с помощью которых можно собрать, запустить, протестировать, разместить ваш програмный код #####

- Сервисы для сборки и запуска кода:
  * :heavy_plus_sign: [GodBolt - Сборник компиляторов/дизассемблеров](https://godbolt.org)
    - позволяет запускать код через множество разных компиляторов GCC, Clang, MSVC ...
    - показывает хорошо аннотированный вывод сборки
    - множество компиляторов с множеством разных версий, в том числе с экспериментальными функциями
    - поддерживает несколько популярных библиотек (ranges, {fmt}, …)
    - отличный текстовый редактор с несколькими курсорами, режим VIM, темный режим, …
    - возможен обмен кода между Compiler Explorer, C++ Insights и Quick Bench
  * [Wandbox - Сборник компиляторов](https://wandbox.org/)
    - GCC, Clang, C++03 - C++2a, Boost
  * [CPP.SH - Сборник компиляторов](https://cpp.sh/)
    - Clang, C++03 - C++23 (experimental)

- Сервисы для профилирования кода:
  * :heavy_plus_sign: [Perfbench](https://perfbench.com/)
  * [Quick-Bench](https://quick-bench.com/)
  
- Сервисы для размещение кода:
  * :heavy_plus_sign: [GitHub Gist](https://gist.github.com)
  * [Pastebin](https://pastebin.com)

---

### :pushpin: Где (кто) мне может помочь, проконсультировать :pushpin: ###
##### Основные сообщества в различных социальных сетях, где можно поучаствовать в обсуждении вопросов и решение проблем #####

- Telegram каналы
  * [pro.cxx (Для людей с опытом)](https://t.me/ProCxx)
  * [supapro.cxx (Чат для тех, кто немного знает C++)](https://t.me/supapro)

- Беседы в Vk.com
  * [Nemezida C++](https://vk.me/join/7tQtOXRZLIPkOh46aN5nN4WNEir47wHYtBE=)
  * [Nemezida Flood](https://vk.me/join/r2GYEBn3TqU9UI5hXBq917IrDXCTOTpT5mU=)
  * [С++ беседа от группы code blog](https://vk.me/join/nvk47HgezGDt485EsI9V9AT6f2I7SGGQSOc=)

```TODO``` (Если вы знаете еще какие-то интересные сообщества, [оповестите нас](https://github.com/JoshuaJakowlew/cppfaq/issues)!) 

---

### :heavy_check_mark: Нововведения С++ :heavy_check_mark: ###
##### Список выпущенных стандартов языка и изменения которые они привнесли #####

- [Нововведения С++11 (Видео)](https://www.youtube.com/watch?v=ZOmZCj5ijck&ab_channel=PVS-StudioRu)
  * [Список нововведений С++11](https://en.cppreference.com/w/cpp/11)
- [Нововведения С++14 (Видео)](https://www.youtube.com/watch?v=5TTS9zr9PGk&ab_channel=PVS-StudioRu)
  * [Список нововведений С++14](https://en.cppreference.com/w/cpp/14)
- [Нововведения С++17 (Видео)](https://www.youtube.com/watch?v=rRMgJEZVY04&ab_channel=PVS-StudioRu)
  * [Список нововведений С++17](https://en.cppreference.com/w/cpp/17)
- [Нововведения С++20 (Видео)](https://www.youtube.com/watch?v=KPuYn_fUdxc&t=3s&ab_channel=PVS-StudioRu)
  * [Список нововведений С++20](https://en.cppreference.com/w/cpp/20)
- [Нововведения С++23 (Видео)](https://www.youtube.com/watch?v=mQzijnbnTO4&t=968s)
  * [Список нововведений С++23](https://en.cppreference.com/w/cpp/23)
- [Список нововведений С++11-23 с примерами](https://github.com/AnthonyCalandra/modern-cpp-features)

### Учебные материалы

---

### :heavy_check_mark: Ресурсы с задачами для практики и тренировок :heavy_check_mark: ###
##### Список сайтов на которых можно применить и отточить свои знания #####

* [Hackerrank](https://www.hackerrank.com/domains/cpp)
* [CodeForces](https://codeforces.com/)
* [Codewars](https://codewars.com/kata/search/cpp?q=&&beta)
* [LeetCode](https://leetcode.com/)

---

### :heavy_check_mark: Книги для изучения языка :heavy_check_mark: ###
##### Список книг на которые стоит обратить свое внимание (разделены на 3 уровня сложности) #####

* :green_book: Начальный :green_book:
  - Стенли Б. Липпман - Язык программирования C++. Базовый курс. [[Скачать книгу](https://disk.yandex.ru/i/O_9ghFjZMr8bBA)]
  - Стивен Прата - Язык программирования C++. Лекции и упражнения [[Скачать книгу](https://disk.yandex.ru/i/QSR598p9CpG5tA)]
  - Бьёрн Страуструп - Принципы и практика с использованием C++ [[Скачать книгу](https://disk.yandex.ru/i/1EJ6hlr7g_glhw)]
* :blue_book: Средний :blue_book:
  - Скотт Мейерс - Эффективный и современный С++. 42 рекомендации по использованию C++11 и C++14 [[Скачать книгу](https://disk.yandex.ru/i/BKzDWpscRPl_lQ)]
  - Яцек Галовиц - C++17 STL. Стандартная библиотека шаблонов [[Скачать книгу](https://disk.yandex.ru/i/UcSk25yhTVBNVg)]
* :orange_book: Выше среднего :orange_book:

"Жизнь после Праты"
- Ivor Horton Peter Van Weert  "Beginning C++20 - From Novice to Professional" (6th edition)
- Nicolai M. Josuttis "С++17 The Complete Guide"
- Marc Gregorie "Professional C++" (4th edition)
- Vardan Grigoryan, Shunguang Wu "Expert C++ - Become a proficient programmer by learning coding best practices with C++17 and C++20's latest features"
- David Vandevoorde, Nicolai M. Josuttis, Douglas Gregor "C++ Templates - The Complete Guide" (2nd edition)
- Antony Polukhin, Boost C++ Application Development Cookbook
- Bjorn Andrist, Viktor Sehr, C++ High Performance: Master the art of optimizing the functioning of your C++ code (2nd Edition)

---

### :heavy_check_mark: Курсы по С++ для начинающих и не только :heavy_check_mark: ###

- Для ознакомления с языком, если у вас вообще нет опыта.
  * [Введение в программирование C++ ](https://stepik.org/course/363/promo)
  * [Программирование на языке C++ ](https://stepik.org/course/7/promo)
  * [Изучение синтаксиса С++ с примерами](https://www.programiz.com/cpp-programming)
  * [ [OTUS] "С++ для начинающих разработчиков 2020"](https://disk.yandex.ru/d/kcsmDi1uDcKdcw?w=1)

- Для тех, кто имеет уже базовые знания в языке.
- * [ [Яндекс Практикум] "Разработчик C++"](https://practicum.yandex.ru/profile/cpp/)
  * [ [МФТИ] "Искусство разработки на современном C++"](https://ru.coursera.org/specializations/c-plus-plus-modern-development) //ЗАКРЫ
  * [ [OTUS] "Разработчик C++ 2020"](https://disk.yandex.ru/d/01KzEC-oIrpUqA?w=1)
  * [ [Повторение материала] ](https://thispointer.com/c11-tutorial/)
 
---
 
### :heavy_check_mark: Полезные, а также интересные лекции и статьи в мире С++ :heavy_check_mark: ###

- Лекционный материал.

  * [ [Константина Владимирова (LLVM Compiler Devloper)] Великолепные лекции по С++](https://www.youtube.com/channel/UCvmBEbr9NZt7UEh9doI7n_A/featured)
  * [ [Константина Владимирова (LLVM Compiler Devloper)] C++ базовый курс, MIPT, ILab](https://www.youtube.com/watch?v=Bym7UMqpVEY&list=PL3BR09unfgciJ1_K_E914nohpiOiHnpsK)
  ---
  * [Лекторий ФПМИ (Введение в С++ (1 курс, осень 2020) ЧАСТЬ №1)](https://www.youtube.com/playlist?list=PL4_hYwCyhAvazfCDGyS0wx_hvBmnAAf4h)
  * [Лекторий ФПМИ (Введение в С++ (1 курс, весна 2021) ЧАСТЬ №2)](https://www.youtube.com/playlist?list=PL4_hYwCyhAvYTzwME4vQoDO8ZINM5trra)
  * [Лекторий ФПМИ (Введение в С++ (1 курс, осень-весна 2021-2022))](https://www.youtube.com/playlist?list=PLSaMkqCXRp4Jen1F8YHJpxlj64hJhdoCS)
  ---
  * [ [Computer Science Center] Программирование на C++, часть 1 (осень 2018)](https://www.youtube.com/playlist?list=PLlb7e2G7aSpTFea2FYxp7mFfbZW-xavhL)
  * [ [Computer Science Center] Программирование на C++, часть 2 (весна 2019)](https://www.youtube.com/playlist?list=PLlb7e2G7aSpRs7YafQ1GgJvyRku10m1RN)

- Конференции
  * [C++ User Group](https://www.youtube.com/channel/UCJ9v015sPgEi0jJXe_zanjA)

- Полезные статьи
  * [Отличные статьи по С++](http://scrutator.me/)
  * [User-defined литералы и магия на интринсиках (разные статьи)](https://wunkolo.github.io/)
  * [Настоящая производительность виртуальных функций](https://johnysswlab.com/the-true-price-of-virtual-functions-in-c/)

- Полезные выступления
  * [ [CppCon 2021] Branchless Programming in C++ - Fedor Pikus](https://www.youtube.com/watch?v=g-WPhYREFjk)
  * [ [CppCon 2021] Beyond struct: Meta-programming a struct Replacement in C++20 - John Bandela](https://www.youtube.com/watch?v=FXfrojjIo80)

- Сборник материалов на Английском языке (Сюда стоит посмотреть)
  * [Jason Turner (C++ Weekly)](https://www.youtube.com/user/lefticus1)
  * [Сборник разных гайдов/примеров по cmake](https://github.com/onqtam/awesome-cmake)
  * [Modern C++ and Native Code (converting from bfilipek.com)](https://www.cppstories.com/)
  * [CppNuts](https://www.youtube.com/user/MrRupeshyadav)
  * [CppStories](https://www.cppstories.com/p/start-here/)
  * [CppCon](https://www.youtube.com/channel/UCMlGfpWw-RUdWX_JbLCukXg)
  * [Bisqwit](https://www.youtube.com/channel/UCKTehwyGCKF-b2wo0RKwrcg)
  * [Programming and Technology Tutorials(javidx9)](https://www.youtube.com/c/javidx9/videos)
  * [Molly Rocket(Handmade Hero)](https://www.youtube.com/c/MollyRocket/videos)

---

### :heavy_check_mark: Полезные материалы по Cmake :heavy_check_mark: ###

- Основные ссылки
  * [Официальный сайт системы автоматизации сборки программного обеспечения Cmake](https://cmake.org/)
  * [Документация](https://cmake.org/documentation/)

- Cтатьи
  * [Полное руководство по CMake. Часть первая: Синтаксис](https://habr.com/ru/post/431428/)
  * [Полное руководство по CMake. Часть вторая: Система сборки](https://habr.com/ru/post/432096/)
  * [Полное руководство по CMake. Часть третья: Тестирование и пакетирование](https://habr.com/ru/post/433822/)

- Лекции/Видео/Tutorials
  * [Сборка проектов на C++ с использованием CMake [OTUS]](https://www.youtube.com/watch?v=LZwEtbc9gEA)
  * [CMake с нуля [SimpleCODING!] :)](https://www.youtube.com/playlist?list=PL6x9Hnsyqn2UwWjSvjCzAY6sEOBrHY7VH)

- Книги/Справочники
  * [Open Source Книга от разработчиков CMake "Mastering CMake"](https://cmake.org/cmake/help/book/mastering-cmake/)
  * [Программирование: система построения проектов cmake [Дубров Д.В.]](https://disk.yandex.ru/i/IvnzEcNJseJbMw)
  * [CMake Cookbook](https://disk.yandex.ru/i/jwBzh2_JcIViTw)

---

### :heavy_check_mark: Материалы для изучения алгоритмов и структур данных :heavy_check_mark: ###

- [Алгоритмы - Теория и Реализация](https://ru.algorithmica.org/cs/graph-traversals/cycle/)
- [Лекции Павла Марвина](https://www.youtube.com/c/pavelmavrin)

- [Тренировки по алгоритмам [Яндекс]](https://yandex.ru/yaintern/algorithm-training)
   * Тренировки по алгоритмам от Яндекса [Плейлист](https://www.youtube.com/watch?v=QLhqYNsPIVo&list=PL6Wui14DvQPySdPv5NUqV3i8sDbHkCKC5)

- [ [OTUS] Алгоритмы для разработчиков 2020](https://disk.yandex.ru/d/JYgqgDt9-7_EXg?w=1)
- [ [Яндекс.Практикум] Алгоритмы для разработчиков 2020](https://yadi.sk/d/igBICEE1ST6NNg)
- [Книги для изучения алгоритмов](https://yadi.sk/d/dQkuPvG9E0nlqQ)
- [Реализации алгоритмов на C++](https://github.com/TheAlgorithms/C-Plus-Plus)

- Визуальное представление алгоритмов:
  * [VisualGo](https://visualgo.net/en)
  * [Algorithm Visualizer](https://algorithm-visualizer.org)

- [Algorithms Specialization от Стэндфордского университета (Coursera)](https://www.coursera.org/browse/computer-science/algorithms)
- [ФПМИ Алгоритмы и структуры данных](https://www.youtube.com/playlist?list=PL4_hYwCyhAvasUkSNdsUKoqcWpw9xl3i1)
- [Алгортимы Ч.1 от Принстонского университета ( Coursera ) ](https://ru.coursera.org/learn/algorithms-part1?action=enroll#syllabus)
- [Алгортимы Ч.2 от Принстонского университета ( Coursera ) ](https://ru.coursera.org/learn/algorithms-part2)

---

```EOF``` :floppy_disk:
