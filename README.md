# justanothernobel
Just Another Nobel

The birth of the idea
	
В этом документе предлагается детальное описание идеи, которая ложится в основу создания проекта -- сервиса аккумулирования актуальных задач науки (математики) и привлечения средств для стимулирования продвижения исследования.

Читателю, который заинтересован в самостоятельном выводе описанной ниже идеи, предлагается следующий нетрудный алгоритм, который, кроме всего прочего, должен подарить приятное время и хорошие эмоции. Итак, рекомендуется:


-- посмотреть короткий фильм "N -- это число" про  известного математика Пола Эрдеша (см. \url{https://www.youtube.com/watch?v=FsFFHX2K2z8}).
-- подумать хотя бы 10 минут над приведенной цитатой сэра Исаака Ньютона вначале фильма. Впрочем, если цитата вам нравится, она начнет жить своей жизнью внутри вас, рождая порой нетривиальные мысли, поэтому можно особенно не думать, а попытаться полюбить или хотя бы проникнуться симпатией к словам: \\ \say{I do not know what I may appear to the world, but to myself I seem to have been only like a boy playing on the seashore, and diverting myself in now and then finding a smoother pebble or a prettier shell than ordinary, whilst the great ocean of truth lay all undiscovered before me.}
\item кроме того, еще одна цитата: \\
\say{One enters the first room of the mansion and it’s dark. One stumbles around bumping into furniture, but gradually you learn where each piece of furniture is. Finally, after six months of so, you find the light switch, you turn it on, and suddenly it’s all illuminated. You can see exactly where you were. Then you move into the next room and spend another six months in the dark. So each of these breakthroughs, while sometimes they’re momentary, sometimes over a period of a day or two, they are the culmination of, and couldn’t exist without, the many months of stumbling around in the dark that precede them.} (Andrew Wiles, the mathematician who proved Fermat’s Last Theorem in 1994 quoted by Singh, 1997, p236, 237)
\item дальше, пожалуйста, исследуйте, как работают и в чем смысл краудфандингово сайта. любого. например, этого: \url{https://www.gofundme.com/}. Дополнительное внимание можете уделить сайту вопросов и ответов \url{http://math.stackexchange.com/}. Этот не единственный, разумеется, но он про математику.
\item после этого оставьте все свои направленные, регулируемые и принуждаемые размышления на неопределенное время. Тогда, возможно, через час, день, неделю, месяц или год ваша мысли каким-то образом совпадут с теми, которые изложены далее. Если вы не хотите терять время, прошу вас следовать дальше. Дорога будет не близкой, но интересной.
\end{enumerate}

\section{Description of the idea in detail}

Идея: следуя примеру Пола Эрдеша, мотивировать исследование открутых проблем небольшими (но и не ограниченными) денежными вознаграждениями. Как побочный, но критически важный момент, происходит аккумулирование актуальных задач в пределах одного сайта. Это открывает многие пути в исследовании взаимосвязей, в отыскании цепочек проблем, в возможностях межобластных работ внутри математики. 

Глобальная сверхзадача: очертить океан правды, о котором говорит сэр Исаак Ньютон. 

Другой важный побочный эффект -- выявление действительно актуальных направлений развития науки, которые питаются либо большим интересом (в случае чистой, на данный момент не прикладной математики), либо питаются интересом практического применения и могут являтся объектом востребования коммерческих или некоммерческих организаций.

Третья причина реализации проекта -- привлечь внимание общества к науке, дать возможность людям, далеким от математики, влиять на неё благотворно.

Итак, платформа (сайт) будет иметь возможность накопления задач и давать возможность спонсорам назначать награду за решение конкретной задачи. У одной задачи может быть множество спонсоров, все суммы сладываются и в итоге выплачиваются автору, решившему проблему.

\subsection*{Target audience}
Целевая аудитория, как люди, на которых расчитана какая-то конкретная задача, жёстко не регулируется, но тем не менее может быть регулируемой в процессе развития проекта. 

На самом деле, кто решит задачу -- не важно. Мы не беспокоимся о привлечении людей со специальным профилем для решение какой-то задачи. Это происходит само по себе, автоматически и естественно. Любая нерешенная проблема -- либо из элементарной математики, либо по процессам Маркова, -- это объект нашего интереса. В первую очередь для проекта интересны именно задачи и их накопление, а не люди, которые их решат.

Чем разрабатываемый сайт отличается от \url{http://math.stackexchange.com/}? Отличается принципиально. Тем не менее, самые тупиковые вопросы с stackexchange -- это то, что нам интересно (например, см. \url{http://math.stackexchange.com/questions/358423/a-short-proof-for-dimrt-dimr1}).

\subsection*{Possible project names}
Имя проекта должно быть разумным с той позиции, что оно должно потенциально позволить расширить сайт для других наук, где проблемы могут быть сформулированы конкретно. На примере сайта \url{http://stackexchange.com/}. Возможные имена:  
\begin{itemize}
\item math.sciencetrack.solutions (.net)
\item math.boostsciences.com (and variations)
\end{itemize}

\section{Implementation details}

Главные возможности, которые сайт дает пользователю -- это формулировка новой задачи, спонсирование уже сформулированной задачи. Для и того, и другого необходима формальная регистрация на сайте.


Перед тем, как пользователи сайта смогут увидеть задачу, она должна быть сформулирована как можно более конкретно. 
Формулирование задачи -- это творчество и интеллектуальный труд, поэтому нужно предоставить все необходимые для такого труда инструменты: должен 
быть реализован конструктор проблемы. Конструктор проблемы -- это возможность создания на сайте уникальной страницы, которая содержит необходимые ресурсы: это поля для обработки кода \LaTeX, это возможность красивого размещения ссылок на связанные статьи, добавление любой графики, добавление схем и т.д. Каждый элемент добавляется опционально и работает в стиле drag and drop.

\subsection*{Life cycle of a problem and accompanying events}

Абстрактно цикл жизни задачи описывается диаграммой ниже. Два наиболее тонких момента в схеме -- это два тайника (stash), которые помогают определить актуальность и действительность задачи и решения соответсвенно. Эти тайники -- сущности абстрактные. 

В действительности система должна быть саморегулируемой и не иметь узких мест ни на каком этапе, поэтому вывод о том, правильно ли сформулирована задача и корректно ли предложенное решение, должны делать люди, пользователи сайта, которые в хорошо разбираются в конкретной области. Эти пользователи, имея вес/рейтинг могут исправлять, дополнять, редактировать или ставить правильные вопросы к предлагаемым задачам. 

Предлагается система сообществ, определяемых конкретной областью науки. Внутри таких общест происходит процесс подтвердения действительности и актуальности задачи и процесс подтверждения истинности предложенного решения. Внутри каждого сообщества все участники разные, имеют разные отличительные качества и мнения каждого учитывается по-разному -- например, в качестве удельного веса голоса.

\begin{tikzpicture}[node distance=2cm]

\node (start) [startstop] {The idea to formulate the problem};
\node (pro1) [process, below of=start] {Start up the Problem Constructor and formalize};
\node (in1) [io, below of=pro1] {Submit proposed problem to the stash};
\node (dec1) [decision, below of=in1, yshift=-0.5cm] {Is it ok?};
\node (pro2a) [process, left of=dec1, xshift=-3cm] {Make author be informed};
\node (pro2b) [process, right of=dec1, xshift=3cm] {Problem is published};
\node (pro2c) [process, below of=dec1, yshift=-0.5cm] {Someone solved the problem}; 
\node (pro3) [process, below of=pro2c] {Start up the Solution Constructor and formalize}; 
\node (in2) [io, below of=pro3] {Submit proposed solution to the stash};
\node (dec2) [decision, below of=in2, yshift=-0.5cm] {Is it ok?};
\node (stop) [startstop, below of=dec2, yshift=-0.5cm] {The problem is marked as closed};

\draw [arrow] (start) -- (pro1);
\draw [arrow] (pro1) -- (in1);
\draw [arrow] (in1) -- (dec1);
\draw [arrow] (dec1) -- node[anchor=south] {no} (pro2a);
\draw [arrow] (dec1) -- node[anchor=south] {yes} (pro2b);
\draw [arrow] (pro2a) |- (pro1);
\draw [arrow] (pro2b) |- (pro2c);
\draw [arrow] (pro2c) -- (pro3);
\draw [arrow] (pro3) -- (in2);
\draw [arrow] (in2) -- (dec2);
\draw [arrow] (dec2) -- node[anchor=east] {yes} (stop);
\draw [arrow, yshift=-0.5cm] (dec2) -| node[anchor=east, yshift=-0.5cm] {no} (pro2b);

\end{tikzpicture}

Problem Constructor \& Solution Constructor -- это две схожие сущности, которые ползволяют пользователю удобно и без ограничений сформулировать постановку новой задачи или оформить решение.

 Solution Constructor запускается после нажатия кнопки "I solved problem!" (или "Evrika!"), предлагает автору формализовать решение, скорее всего это будет просто ссылка на статью в интернете, но может быть и форма для \LaTeX 'а. Решение описано, нажимается кнопка "submit" и решение попадает в stash проверки решения. Это есть специальный тип задач "Решенные, не подтвержденные". Задачи из этого раздела могут попадать либо обратно в класс "нерешенных", либо в класс "решенных".
 
Система подтверждения решения работает таким образом. За время своего существования, задача собирает рейтинг, который говорит о её важности. Рейтинг учитывает время, которое задача не могла найти решение, количество привлеченных средств, мнения участников сообщества о её важности. Когда задача решена и её решение должно быть подтверждено, рейтинг её важности должен быть погашен за счет голосов участников сообщества в пользу предложенного решения. Тут происходит баланс важности задачи и минимизация ошибки в принятии неверного решения за истинное.

\subsection*{How to sponsor a problem}

Возможность спонсирования задачи открывается после того, как задача попадает на сайт. Задача попадает на сайт после автоматизированной проверки на недопустимые выражения. Дальше она начинает свою жизнь и может/должна подвергаться многочисленным изменениям до момента её решения. Спонсирование происходит по отношению к конкретной задаче. Посетитель сайта должен иметь возможность субсидировать сумму по собственному усмотрению, посмотреть историю субсидий. 

\subsection*{Other details}

Подключение возможности отслеживания прогресса какой-то задачи.

\section{Design sketch}

\subsection*{Homepage}

Homepage размещает ссылки на 3 основные типа задач: "Нерешенный", "Решенные" и "Решенные, но не подтвержденные".
Обязательно присутсвует кнопка "Сформулировать новую задачу". 

По центру страницы размещается идея сайта и его смысл, выраженный точно и лаконично.Где-то на странице (возможно как фон) размещаются цитаты, интересные выражения ученых, факты и т.п. 

Должно быть достаточно свободного пространства, страница должна дышать. Всё должно быть предельно просто и понятно, красиво и приятно.

Как возможная идея -- знак i в кружочке вместе с именем Пола Эрдеша, в знак того, что он является вдохновителем (i -- inspire).

\subsection*{Unsolved, unverified and solved problems}

Три вкладки имеют похожую структуру. Главное -- есть возможность сортировки по любому критерию, можно выбирать задачи из разных разделов (сообществ). 

\end{document}
