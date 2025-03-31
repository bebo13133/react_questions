
 ** Какво е React и кои са основните му предимства?
 * React е JavaScript библиотека за изграждане на потребителски интерфейси, разработена от Facebook, с предимства като компонентна архитектура, виртуален DOM, еднопосочен поток на данни, JSX синтаксис и богата екосистема.



 * 2. Какво представлява JSX?
 * JSX е синтаксично разширение на JavaScript, което позволява писането на HTML-подобен код в JavaScript файлове, улеснявайки описването на структурата на потребителския интерфейс.



 * 3. Каква е разликата между компонент и елемент в React?
 * React елементът е лек JavaScript обект, описващ какво да се визуализира на екрана, докато компонентът е функция или клас, който приема props и връща React елемент.



 * 4. Какво представляват props в React?
 * Props са механизъм за предаване на данни от родителски към дъщерни компоненти, те са само за четене и следват еднопосочния поток на данни.



 * 5. Какво е state в React и как се използва?
 * State е JavaScript обект, съдържащ данни специфични за компонента, които могат да се променят във времето, като промяната предизвиква ново рендериране.



 * 6. Какво е Виртуален DOM и как работи?
 * Виртуалният DOM е програмна концепция, представляваща виртуално копие на реалния DOM, което позволява React да изчисли и приложи само минимално необходимите промени в реалния DOM.



 * 7. Какво са Life cycle hooks (методи на жизнения цикъл)?
 * Life cycle методите са специални методи в класовите компоненти, които се изпълняват в различни фази от живота на компонента: монтиране, обновяване и размонтиране.


 * 8. Какво е Hook в React?
 * Hook е функция, която позволява на функционалните компоненти да използват React функционалности като състояние, жизнен цикъл и контекст без да се пишат класови компоненти.



 * 9. Какви видове Hooks има в React?
 * Основните hooks включват useState, useEffect, useContext, useReducer, useRef, useMemo, useCallback, useImperativeHandle, useLayoutEffect и useDebugValue.



 * 10. Какво е Error Boundary в React?
 * Error Boundary е компонент, който улавя JavaScript грешки в дървото на неговите дъщерни компоненти, регистрира тези грешки и показва резервен потребителски интерфейс вместо компонента, който се е срутил.


 * 11. Какво е onChange в React?
 * onChange е събитиен обработчик, който се извиква когато стойността на елемент от формуляр се промени, позволявайки на React да контролира въвеждането на данни.



 * 12. Какво е Context в React?
 * Context е механизъм за предаване на данни през дървото на компонентите без да се предават props ръчно на всяко ниво, особено полезен за "глобални" данни като текуща тема, потребител или език.


 * 13. Какво е prop drilling и защо трябва да се избягва?
 * Prop drilling е практика на предаване на props през множество нива компоненти, които не се нуждаят от тези данни, само за да стигнат до компоненти на по-дълбоко ниво. Това води до по-сложен, труден за поддръжка код и ненужни рендерирания.



 * 14. Какво е React Router и как се използва?
 * React Router е библиотека за маршрутизация в React приложения, позволяваща навигация между различни компоненти без презареждане на страницата.



 * 15. Какво е Redux и кога трябва да се използва?
 * Redux е библиотека за управление на състоянието в JavaScript приложения, предоставяща предвидим контейнер за състоянието, следвайки строги правила за промяна на състоянието.
 


 * 16. Какво представлява useEffect и какви са особеностите му?
 * useEffect е hook, който позволява изпълнение на странични ефекти във функционални компоненти, като заявки към сървъри, манипулации на DOM или абонамент за събития.


 * 17. Какво е React Fragment?
 * React Fragment е компонент, който позволява групиране на няколко елемента без добавяне на допълнителен възел в DOM дървото.



 * 18. Какво е controlled и uncontrolled компонент?
 * В controlled компонентите данните се контролират от React чрез state, докато в uncontrolled компонентите данните се управляват от самия DOM.


 * 19. Какво е React.memo и кога се използва?
 * React.memo е higher-order компонент, който мемоизира резултата от рендериране на компонент, предотвратявайки ненужни рендерирания, когато входните props не са променени.



 * 20. Какво е React Suspense?
 * Suspense е функционалност на React, която позволява компонентите да "изчакат" нещо преди рендериране, като често се използва за lazy loading на компоненти и данни.



 * 21. Реактивен ли е React?
 * React не е изцяло реактивен фреймуърк в традиционния смисъл. Въпреки името си, React използва декларативен подход, но не предлага автоматично проследяване на зависимостите и реактивно разпространение на промените както други реактивни фреймуърки.



 * 22. Какво е Pure Component в React?
 * Pure Component е компонент, който извършва плитко сравнение на props и state преди рендериране, и се рендерира отново само ако има разлика.



 * 23. Какво е Higher-Order Component (HOC)?
 * HOC е функция, която приема компонент и връща нов компонент с разширена функционалност.



 * 24. Какво е Render Props в React?
 * Render Props е техника за споделяне на код между компоненти чрез prop, чиято стойност е функция, която връща React елемент.



 * 25. Какво е React StrictMode?
 * StrictMode е инструмент за открояване на потенциални проблеми в приложението, като активира допълнителни проверки и предупреждения в процеса на разработка.



 * 26. Какво е React Portals?
 * Portals предоставя начин за рендериране на деца в DOM възел, който съществува извън DOM йерархията на родителския компонент.



 * 27. Каква е разликата между Shallow Rendering и Full Rendering в тестването?
 * Shallow Rendering изолира компонента за тестване, без да рендерира дъщерните компоненти, докато Full Rendering създава пълно DOM дърво с всички дъщерни компоненти.



 * 28. Какво е Server-Side Rendering (SSR) в React?
 * SSR е техника за рендериране на React компоненти на сървъра вместо в браузъра, което подобрява първоначалното зареждане и SEO на приложението.



 * 29. Какво е React Fiber?
 * React Fiber е нова имплементация на алгоритъма за съгласуване (reconciliation) в React, проектирана за постепенно рендериране и по-добро управление на приоритетите.



 * 30. Какво е React Testing Library?
 * React Testing Library е набор от помощни методи за тестване на React компоненти по начин, който наподобява как потребителите взаимодействат с приложението.


 * 31. Какви са начините за оптимизация на React приложения?
 * Ключови техники включват използване на React.memo, useMemo и useCallback за предотвратяване на ненужни рендерирания, Code Splitting чрез React.lazy, правилно използване на ключове в списъци и избягване на анонимни функции в рендер методи.



 * 32. Какво е useMemo и как се различава от useCallback?
 * useMemo мемоизира стойност, докато useCallback мемоизира функция. И двата хука се използват за оптимизиране на производителността, като предотвратяват ненужни изчисления или рендерирания.


 * 33. Защо ключовете (keys) са важни при рендериране на списъци?
 * Ключовете помагат на React да идентифицира кои елементи са се променили, добавени или премахнати, което е важно за ефективно обновяване на UI и предотвратяване на бъгове при работа със списъци.


 * 34. Какво е Code Splitting в React?
 * Code Splitting е техника за разделяне на кода на по-малки пакети, които се зареждат при нужда, вместо цялото приложение да се зареди наведнъж, подобрявайки първоначалното време за зареждане.


 * 35. Какво е Concurrent Mode в React?
 * Concurrent Mode е набор от нови функционалности в React, които позволяват рендерирането да бъде прекъсвано, давайки приоритет на по-важни обновявания, подобрявайки отзивчивостта на приложението.

 * 36. Какво е Server Components в React?
 * Server Components е експериментална функционалност, която позволява компоненти да се изпълняват и рендерират само на сървъра, без JavaScript на клиента, подобрявайки производителността и намалявайки bundle размера.



 * 37. Какво е React Query и какви проблеми решава?
 * React Query е библиотека за управление на асинхронни данни в React, която предлага кеширане, повторни опити, изчакване на данни и много други функционалности, опростявайки управлението на данни от API.
 


 * 38. Какво е React Native и как се отнася към React?
 * React Native е фреймуърк, базиран на React, който позволява разработка на нативни мобилни приложения за iOS и Android с един и същи JavaScript код, използвайки подобни концепции и структура като React.
 

 * 39. Какви са основните принципи за структуриране на React проект?
 * Добрите практики включват организиране по функционалност или тип (компоненти, услуги, хукове), използване на атомичен дизайн, спазване на принципа за единствена отговорност и поддържане на компонентите малки и фокусирани.


 * 40. Какво е Compound Components модел?
 * Compound Components е модел, при който няколко компонента работят заедно, споделяйки имплицитно състояние, за да предоставят по-богат UI и по-интуитивен API за разработчика.


 * 41. Какво представлява Custom Hook?
 * Custom Hook е JavaScript функция, чието име започва с "use" и която може да извиква други хукове, позволявайки извличане и преизползване на логика между компоненти.


 * 42. Каква е разликата между изпълнение на React на клиента и на сървъра?
 * При клиентско рендериране целият JavaScript се изпраща на клиента и се изпълнява в браузъра, докато при сървърното рендериране React генерира HTML на сървъра и го изпраща готов на клиента, което подобрява първоначалното зареждане и SEO.


 * 43. Как React работи с TypeScript?
 * React има отлична интеграция с TypeScript, позволявайки типизиране на props, state, hooks и други React структури чрез интерфейси и generics, подобрявайки безопасността на типовете и разработческия опит.
 


 * 44. Какви са основните подходи за стилизиране в React?
 * Основните подходи включват CSS файлове, CSS модули, inline стилове, CSS-in-JS библиотеки като styled-components и emotion, и CSS фреймуърки като Tailwind CSS.


 * 45. Как се интегрира React с REST API?
 * React може да комуникира с REST API чрез нативния fetch API, Axios или специализирани библиотеки като React Query, използвайки useEffect за извличане на данни или custom hooks за капсулиране на API логиката.



 * 46. Какво е GraphQL и как се използва с React?
 * GraphQL е език за заявки за API, който позволява на клиентите да заявят точно данните, които им трябват. С React се използва често чрез Apollo Client или Relay, предлагайки по-ефективен начин за извличане и управление на данни.
