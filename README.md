# Фундаментални въпроси за ReactJS

## 1. Какво е React и кои са основните му предимства?
React е JavaScript библиотека за изграждане на потребителски интерфейси, разработена от Facebook, с предимства като компонентна архитектура, виртуален DOM, еднопосочен поток на данни, JSX синтаксис и богата екосистема.

## 2. Какво представлява JSX?
JSX е синтаксично разширение на JavaScript, което позволява писането на HTML-подобен код в JavaScript файлове, улеснявайки описването на структурата на потребителския интерфейс.

## 3. Каква е разликата между компонент и елемент в React?
React елементът е лек JavaScript обект, описващ какво да се визуализира на екрана, докато компонентът е функция или клас, който приема props и връща React елемент.

## 4. Какво представляват props в React?
Props са механизъм за предаване на данни от родителски към дъщерни компоненти, те са само за четене и следват еднопосочния поток на данни.

## 5. Какво е state в React и как се използва?
State е JavaScript обект, съдържащ данни специфични за компонента, които могат да се променят във времето, като промяната предизвиква ново рендериране.

## 6. Какво е Виртуален DOM и как работи?
Виртуалният DOM е програмна концепция, представляваща виртуално копие на реалния DOM, което позволява React да изчисли и приложи само минимално необходимите промени в реалния DOM.

## 7. Какво са Life cycle hooks (методи на жизнения цикъл)?
Life cycle методите са специални методи в класовите компоненти, които се изпълняват в различни фази от живота на компонента: монтиране, обновяване и размонтиране.

## 8. Какво е Hook в React?
Hook е функция, която позволява на функционалните компоненти да използват React функционалности като състояние, жизнен цикъл и контекст без да се пишат класови компоненти.

## 9. Какви видове Hooks има в React?
Основните hooks включват useState, useEffect, useContext, useReducer, useRef, useMemo, useCallback, useImperativeHandle, useLayoutEffect и useDebugValue.

## 10. Какво е Error Boundary в React?
Error Boundary е компонент, който улавя JavaScript грешки в дървото на неговите дъщерни компоненти, регистрира тези грешки и показва резервен потребителски интерфейс вместо компонента, който се е срутил.

## 11. Какво е onChange в React?
onChange е събитиен обработчик, който се извиква когато стойността на елемент от формуляр се промени, позволявайки на React да контролира въвеждането на данни.

## 12. Какво е Context в React?
Context е механизъм за предаване на данни през дървото на компонентите без да се предават props ръчно на всяко ниво, особено полезен за "глобални" данни като текуща тема, потребител или език.

## 13. Какво е prop drilling и защо трябва да се избягва?
Prop drilling е практика на предаване на props през множество нива компоненти, които не се нуждаят от тези данни, само за да стигнат до компоненти на по-дълбоко ниво. Това води до по-сложен, труден за поддръжка код и ненужни рендерирания.

## 14. Какво е React Router и как се използва?
React Router е библиотека за маршрутизация в React приложения, позволяваща навигация между различни компоненти без презареждане на страницата.

## 15. Какво е Redux и кога трябва да се използва?
Redux е библиотека за управление на състоянието в JavaScript приложения, предоставяща предвидим контейнер за състоянието, следвайки строги правила за промяна на състоянието.

## 16. Какво представлява useEffect и какви са особеностите му?
useEffect е hook, който позволява изпълнение на странични ефекти във функционални компоненти, като заявки към сървъри, манипулации на DOM или абонамент за събития.

## 17. Какво е React Fragment?
React Fragment е компонент, който позволява групиране на няколко елемента без добавяне на допълнителен възел в DOM дървото.

## 18. Какво е controlled и uncontrolled компонент?
В controlled компонентите данните се контролират от React чрез state, докато в uncontrolled компонентите данните се управляват от самия DOM.

## 19. Какво е React.memo и кога се използва?
React.memo е higher-order компонент, който мемоизира резултата от рендериране на компонент, предотвратявайки ненужни рендерирания, когато входните props не са променени.

## 20. Какво е React Suspense?
Suspense е функционалност на React, която позволява компонентите да "изчакат" нещо преди рендериране, като често се използва за lazy loading на компоненти и данни.

## 21. Реактивен ли е React?
React не е изцяло реактивен фреймуърк в традиционния смисъл. Въпреки името си, React използва декларативен подход, но не предлага автоматично проследяване на зависимостите и реактивно разпространение на промените както други реактивни фреймуърки.

## 22. Какво е Pure Component в React?
Pure Component е компонент, който извършва плитко сравнение на props и state преди рендериране, и се рендерира отново само ако има разлика.

## 23. Какво е Higher-Order Component (HOC)?
HOC е функция, която приема компонент и връща нов компонент с разширена функционалност.

## 24. Какво е Render Props в React?
Render Props е техника за споделяне на код между компоненти чрез prop, чиято стойност е функция, която връща React елемент.

## 25. Какво е React StrictMode?
StrictMode е инструмент за открояване на потенциални проблеми в приложението, като активира допълнителни проверки и предупреждения в процеса на разработка.

## 26. Какво е React Portals?
Portals предоставя начин за рендериране на деца в DOM възел, който съществува извън DOM йерархията на родителския компонент.

## 27. Каква е разликата между Shallow Rendering и Full Rendering в тестването?
Shallow Rendering изолира компонента за тестване, без да рендерира дъщерните компоненти, докато Full Rendering създава пълно DOM дърво с всички дъщерни компоненти.

## 28. Какво е Server-Side Rendering (SSR) в React?
SSR е техника за рендериране на React компоненти на сървъра вместо в браузъра, което подобрява първоначалното зареждане и SEO на приложението.

## 29. Какво е React Fiber?
React Fiber е нова имплементация на алгоритъма за съгласуване (reconciliation) в React, проектирана за постепенно рендериране и по-добро управление на приоритетите.

## 30. Какво е React Testing Library?
React Testing Library е набор от помощни методи за тестване на React компоненти по начин, който наподобява как потребителите взаимодействат с приложението.

## 31. Какви са начините за оптимизация на React приложения?
Ключови техники включват използване на React.memo, useMemo и useCallback за предотвратяване на ненужни рендерирания, Code Splitting чрез React.lazy, правилно използване на ключове в списъци и избягване на анонимни функции в рендер методи.

## 32. Какво е useMemo и как се различава от useCallback?
useMemo мемоизира стойност, докато useCallback мемоизира функция. И двата хука се използват за оптимизиране на производителността, като предотвратяват ненужни изчисления или рендерирания.

## 33. Защо ключовете (keys) са важни при рендериране на списъци?
Ключовете помагат на React да идентифицира кои елементи са се променили, добавени или премахнати, което е важно за ефективно обновяване на UI и предотвратяване на бъгове при работа със списъци.

## 34. Какво е Code Splitting в React?
Code Splitting е техника за разделяне на кода на по-малки пакети, които се зареждат при нужда, вместо цялото приложение да се зареди наведнъж, подобрявайки първоначалното време за зареждане.

## 35. Какво е Concurrent Mode в React?
Concurrent Mode е набор от нови функционалности в React, които позволяват рендерирането да бъде прекъсвано, давайки приоритет на по-важни обновявания, подобрявайки отзивчивостта на приложението.

## 36. Какво е Server Components в React?
Server Components е експериментална функционалност, която позволява компоненти да се изпълняват и рендерират само на сървъра, без JavaScript на клиента, подобрявайки производителността и намалявайки bundle размера.

## 37. Какво е React Query и какви проблеми решава?
React Query е библиотека за управление на асинхронни данни в React, която предлага кеширане, повторни опити, изчакване на данни и много други функционалности, опростявайки управлението на данни от API.

## 38. Какво е React Native и как се отнася към React?
React Native е фреймуърк, базиран на React, който позволява разработка на нативни мобилни приложения за iOS и Android с един и същи JavaScript код, използвайки подобни концепции и структура като React.

## 39. Какви са основните принципи за структуриране на React проект?
Добрите практики включват организиране по функционалност или тип (компоненти, услуги, хукове), използване на атомичен дизайн, спазване на принципа за единствена отговорност и поддържане на компонентите малки и фокусирани.

## 40. Какво е Compound Components модел?
Compound Components е модел, при който няколко компонента работят заедно, споделяйки имплицитно състояние, за да предоставят по-богат UI и по-интуитивен API за разработчика.

## 41. Какво представлява Custom Hook?
Custom Hook е JavaScript функция, чието име започва с "use" и която може да извиква други хукове, позволявайки извличане и преизползване на логика между компоненти.

## 42. Каква е разликата между изпълнение на React на клиента и на сървъра?
При клиентско рендериране целият JavaScript се изпраща на клиента и се изпълнява в браузъра, докато при сървърното рендериране React генерира HTML на сървъра и го изпраща готов на клиента, което подобрява първоначалното зареждане и SEO.

## 43. Как React работи с TypeScript?
React има отлична интеграция с TypeScript, позволявайки типизиране на props, state, hooks и други React структури чрез интерфейси и generics, подобрявайки безопасността на типовете и разработческия опит.

## 44. Какви са основните подходи за стилизиране в React?
Основните подходи включват CSS файлове, CSS модули, inline стилове, CSS-in-JS библиотеки като styled-components и emotion, и CSS фреймуърки като Tailwind CSS.

## 45. Как се интегрира React с REST API?
React може да комуникира с REST API чрез нативния fetch API, Axios или специализирани библиотеки като React Query, използвайки useEffect за извличане на данни или custom hooks за капсулиране на API логиката.

## 46. Какво е GraphQL и как се използва с React?
GraphQL е език за заявки за API, който позволява на клиентите да заявят точно данните, които им трябват. С React се използва често чрез Apollo Client или Relay, предлагайки по-ефективен начин за извличане и управление на данни.


========================================================================================================================================================================


# Fundamental Questions about ReactJS

## 1. What is React and what are its main advantages?
React is a JavaScript library for building user interfaces, developed by Facebook, with advantages such as component architecture, virtual DOM, one-way data flow, JSX syntax, and a rich ecosystem.

## 2. What is JSX?
JSX is a syntax extension of JavaScript that allows writing HTML-like code in JavaScript files, making it easier to describe the structure of the user interface.

## 3. What is the difference between a component and an element in React?
A React element is a lightweight JavaScript object describing what to render on the screen, while a component is a function or class that accepts props and returns a React element.

## 4. What are props in React?
Props are a mechanism for passing data from parent to child components, they are read-only and follow the one-way data flow.

## 5. What is state in React and how is it used?
State is a JavaScript object containing component-specific data that can change over time, with changes triggering a new render.

## 6. What is the Virtual DOM and how does it work?
The Virtual DOM is a programming concept representing a virtual copy of the real DOM, which allows React to calculate and apply only the minimum necessary changes to the real DOM.

## 7. What are lifecycle hooks (lifecycle methods)?
Lifecycle methods are special methods in class components that execute at different phases of a component's life: mounting, updating, and unmounting.

## 8. What is a Hook in React?
A Hook is a function that allows functional components to use React features like state, lifecycle, and context without writing class components.

## 9. What types of Hooks are there in React?
The main hooks include useState, useEffect, useContext, useReducer, useRef, useMemo, useCallback, useImperativeHandle, useLayoutEffect, and useDebugValue.

## 10. What is an Error Boundary in React?
An Error Boundary is a component that catches JavaScript errors in its child component tree, logs those errors, and displays a fallback UI instead of the component that crashed.

## 11. What is onChange in React?
onChange is an event handler that is called when the value of a form element changes, allowing React to control data input.

## 12. What is Context in React?
Context is a mechanism for passing data through the component tree without manually passing props at every level, especially useful for "global" data like current theme, user, or language.

## 13. What is prop drilling and why should it be avoided?
Prop drilling is the practice of passing props through multiple levels of components that don't need this data, just to reach components at a deeper level. This leads to more complex, harder-to-maintain code and unnecessary renderings.

## 14. What is React Router and how is it used?
React Router is a library for routing in React applications, allowing navigation between different components without page reloads.

## 15. What is Redux and when should it be used?
Redux is a library for state management in JavaScript applications, providing a predictable state container, following strict rules for state changes.

## 16. What is useEffect and what are its characteristics?
useEffect is a hook that allows the execution of side effects in functional components, such as server requests, DOM manipulations, or event subscriptions.

## 17. What is React Fragment?
React Fragment is a component that allows grouping of multiple elements without adding an additional node to the DOM tree.

## 18. What is a controlled and uncontrolled component?
In controlled components, data is controlled by React through state, while in uncontrolled components, data is managed by the DOM itself.

## 19. What is React.memo and when is it used?
React.memo is a higher-order component that memoizes the result of rendering a component, preventing unnecessary renderings when the input props have not changed.

## 20. What is React Suspense?
Suspense is a React feature that allows components to "wait" for something before rendering, often used for lazy loading of components and data.

## 21. Is React reactive?
React is not entirely a reactive framework in the traditional sense. Despite its name, React uses a declarative approach, but does not offer automatic dependency tracking and reactive propagation of changes like other reactive frameworks.

## 22. What is a Pure Component in React?
A Pure Component is a component that performs a shallow comparison of props and state before rendering, and only re-renders if there is a difference.

## 23. What is a Higher-Order Component (HOC)?
A HOC is a function that takes a component and returns a new component with enhanced functionality.

## 24. What is Render Props in React?
Render Props is a technique for sharing code between components via a prop whose value is a function that returns a React element.

## 25. What is React StrictMode?
StrictMode is a tool for highlighting potential problems in an application by activating additional checks and warnings during development.

## 26. What is React Portals?
Portals provide a way to render children into a DOM node that exists outside the DOM hierarchy of the parent component.

## 27. What is the difference between Shallow Rendering and Full Rendering in testing?
Shallow Rendering isolates the component for testing without rendering child components, while Full Rendering creates a complete DOM tree with all child components.

## 28. What is Server-Side Rendering (SSR) in React?
SSR is a technique for rendering React components on the server rather than in the browser, improving initial loading and SEO of the application.

## 29. What is React Fiber?
React Fiber is a new implementation of the reconciliation algorithm in React, designed for incremental rendering and better prioritization.

## 30. What is React Testing Library?
React Testing Library is a set of helper methods for testing React components in a way that mimics how users interact with the application.

## 31. What are the ways to optimize React applications?
Key techniques include using React.memo, useMemo and useCallback to prevent unnecessary renderings, Code Splitting with React.lazy, properly using keys in lists, and avoiding anonymous functions in render methods.

## 32. What is useMemo and how does it differ from useCallback?
useMemo memoizes a value, while useCallback memoizes a function. Both hooks are used to optimize performance by preventing unnecessary calculations or renderings.

## 33. Why are keys important when rendering lists?
Keys help React identify which elements have changed, been added, or removed, which is important for efficient UI updates and preventing bugs when working with lists.

## 34. What is Code Splitting in React?
Code Splitting is a technique for dividing code into smaller packages that load on demand, rather than loading the entire application at once, improving initial load time.

## 35. What is Concurrent Mode in React?
Concurrent Mode is a set of new features in React that allow rendering to be interrupted, giving priority to more important updates, improving application responsiveness.

## 36. What are Server Components in React?
Server Components is an experimental feature that allows components to be executed and rendered only on the server, without JavaScript on the client, improving performance and reducing bundle size.

## 37. What is React Query and what problems does it solve?
React Query is a library for managing asynchronous data in React, offering caching, retries, data waiting, and many other features, simplifying API data management.

## 38. What is React Native and how does it relate to React?
React Native is a framework based on React that allows development of native mobile applications for iOS and Android with the same JavaScript code, using similar concepts and structure as React.

## 39. What are the main principles for structuring a React project?
Good practices include organizing by functionality or type (components, services, hooks), using atomic design, following the single responsibility principle, and keeping components small and focused.

## 40. What is the Compound Components model?
Compound Components is a model where several components work together, implicitly sharing state, to provide a richer UI and more intuitive API for the developer.

## 41. What is a Custom Hook?
A Custom Hook is a JavaScript function whose name starts with "use" and which can call other hooks, allowing extraction and reuse of logic between components.

## 42. What is the difference between client-side and server-side execution of React?
In client-side rendering, all JavaScript is sent to the client and executed in the browser, while in server-side rendering, React generates HTML on the server and sends it ready to the client, improving initial loading and SEO.

## 43. How does React work with TypeScript?
React has excellent integration with TypeScript, allowing typing of props, state, hooks, and other React structures through interfaces and generics, improving type safety and developer experience.

## 44. What are the main approaches to styling in React?
The main approaches include CSS files, CSS modules, inline styles, CSS-in-JS libraries like styled-components and emotion, and CSS frameworks like Tailwind CSS.

## 45. How is React integrated with REST API?
React can communicate with REST API through the native fetch API, Axios, or specialized libraries like React Query, using useEffect for data retrieval or custom hooks to encapsulate API logic.

## 46. What is GraphQL and how is it used with React?
GraphQL is a query language for APIs that allows clients to request exactly the data they need. It is often used with React through Apollo Client or Relay, offering a more efficient way to retrieve and manage data.
