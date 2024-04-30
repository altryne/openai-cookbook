# OpenAI Cookbook

OpenAI Cookbook представляет примеры кода для выполнения общих задач с использованием [OpenAI API].

Для запуска этих примеров вам понадобится аккаунт OpenAI и API ключ ([создайте бесплатный аккаунт][api signup]).

Большинство примеров кода написаны на Python, хотя концепции могут быть применены на любом языке.

[![Открыть в GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=468576060&machine=basicLinux32gb&location=EastUs)

## Недавно добавлено/обновлено 🆕 ✨

- [Ответы на вопросы с использованием поискового API и переранжирования](https://github.com/openai/openai-cookbook/blob/main/examples/Question_answering_using_a_search_API.ipynb) [16 июня 2023 года]
- [Как вызывать функции с моделями Chat](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_call_functions_with_chat_models.ipynb) [13 июня 2023 года]
- [Связанные ресурсы из интернета](https://github.com/openai/openai-cookbook#related-resources-from-around-the-web) [22 мая 2023 года]
- [Площадка для встраивания (приложение streamlit)](apps/embeddings-playground/README.md) [19 мая 2023 года]
- [Как использовать многошаговый запрос для написания модульных тестов](examples/Unit_test_writing_using_a_multi-step_prompt.ipynb) [19 мая 2023 года]
- [Как создавать динамические маски с DALL·E и Segment Anything](examples/dalle/How_to_create_dynamic_masks_with_DALL-E_and_Segment_Anything.ipynb) [19 мая 2023 года]

## Руководства и примеры

- Использование API
  - [Как обрабатывать ограничения скорости](examples/How_to_handle_rate_limits.ipynb)
    - [Пример скрипта параллельной обработки, который избегает достижения ограничений скорости](examples/api_request_parallel_processor.py)
  - [Как подсчитать токены с tiktoken](examples/How_to_count_tokens_with_tiktoken.ipynb)
- GPT
  - [Как форматировать входные данные для моделей ChatGPT](examples/How_to_format_inputs_to_ChatGPT_models.ipynb)
  - [Как потоково передавать завершения](examples/How_to_stream_completions.ipynb)
  - [Как использовать многошаговый запрос для написания модульных тестов](examples/Unit_test_writing_using_a_multi-step_prompt.ipynb)
  - [Руководство: Как работать с большими языковыми моделями](how_to_work_with_large_language_models.md)
  - [Руководство: Техники для улучшения надежности](techniques_to_improve_reliability.md)
- Встраивания
  - [Примеры сравнения текстов](text_comparison_examples.md)
  - [Как получить встраивания](examples/Get_embeddings.ipynb)
  - [Ответы на вопросы с использованием встраиваний](examples/Question_answering_using_embeddings.ipynb)
  - [Использование баз данных векторов для поиска встраиваний](examples/vector_databases/Using_vector_databases_for_embeddings_search.ipynb)
  - [Семантический поиск с использованием встраиваний](examples/Semantic_text_search_using_embeddings.ipynb)
  - [Рекомендации с использованием встраиваний](examples/Recommendation_using_embeddings.ipynb)
  - [Кластеризация встраиваний](examples/Clustering.ipynb)
  - [Визуализация встраиваний в 2D](examples/Visualizing_embeddings_in_2D.ipynb) или [3D](examples/Visualizing_embeddings_in_3D.ipynb)
  - [Встраивание длинных текстов](examples/Embedding_long_inputs.ipynb)
  - [Площадка для встраивания (приложение streamlit)](apps/embeddings-playground/README.md)
- Приложения
  - [Вопросы и ответы по файлам](apps/file-q-and-a/)
  - [Вопросы и ответы по веб-поиску](apps/web-crawl-q-and-a)
  - [Улучшение ваших продуктов с помощью ChatGPT и собственных данных](apps/chatbot-kickstarter/powering_your_products_with_chatgpt_and_your_data.ipynb)
- Дообучение GPT-3
  - [Руководство: лучшие практики дообучения GPT-3 для классификации текста](https://docs.google.com/document/d/1rqj7dkuvl7Byd5KQPUJRxc19BJt8wo0yHNwK84KfU3Q/edit)
  - [Дообученная классификация](examples/Fine-tuned_classification.ipynb)
- DALL-E
  - [Как генерировать и редактировать изображения с DALL·E](examples/dalle/Image_generations_edits_and_variations_with_DALL-E.ipynb)
  - [Как создавать динамические маски с DALL·E и Segment Anything](examples/dalle/How_to_create_dynamic_masks_with_DALL-E_and_Segment_Anything.ipynb)
- Azure OpenAI (альтернативный API от Microsoft Azure)
  - [Как использовать ChatGPT с Azure OpenAI](examples/azure/chat.ipynb)
  - [Как получить завершения от Azure OpenAI](examples/azure/completions.ipynb)
  - [Как получить встраивания от Azure OpenAI](examples/azure/embeddings.ipynb)
  - [Как генерировать изображения с DALL·E от Azure OpenAI](examples/azure/DALL-E.ipynb)

## Связанные ресурсы OpenAI

Помимо примеров кода здесь, вы можете узнать о [OpenAI API] из следующих ресурсов:

- Экспериментируйте с [ChatGPT]
- Попробуйте API в [OpenAI Playground]
- Прочитайте об API в [OpenAI Documentation]
- Получите помощь в [OpenAI Help Center]
- Обсудите API в [OpenAI Community Forum] или [OpenAI Discord channel]
- Посмотрите примеры запросов в [OpenAI Examples]
- Оставайтесь в курсе событий с [OpenAI Blog]

## Связанные ресурсы из интернета

Люди создают отличные инструменты и статьи для улучшения результатов работы с GPT. Вот некоторые крутые, которые мы видели:

### Библиотеки и инструменты для запросов

- [Guidance](https://github.com/microsoft/guidance): Удобная библиотека Python от Microsoft, использующая шаблоны Handlebars для чередования генерации, запросов и логического контроля.
- [LangChain](https://github.com/hwchase17/langchain): Популярная библиотека Python/JavaScript для создания последовательностей запросов к языковым моделям.
- [FLAML (A Fast Library for Automated Machine Learning & Tuning)](https://microsoft.github.io/FLAML/docs/Getting-Started/): Библиотека Python для автоматизации выбора моделей, гиперпараметров и других настраиваемых параметров.
- [Chainlit](https://docs.chainlit.io/overview): Библиотека Python для создания интерфейсов чат-ботов.
- [Guardrails.ai](https://shreyar.github.io/guardrails/): Библиотека Python для проверки результатов и повторных попыток при сбоях. Находится в альфа-версии, поэтому ожидайте острых углов и ошибок.
- [Semantic Kernel](https://devblogs.microsoft.com/semantic-kernel/): Библиотека Python/C# от Microsoft, поддерживающая шаблоны запросов, цепочки функций, векторизированную память и интеллектуальное планирование.
- [Outlines](https://github.com/normal-computing/outlines): Библиотека Python, предоставляющая специализированный язык для упрощения запросов и ограничения генерации.
- [Promptify](https://github.com/promptslab/Promptify): Небольшая библиотека Python для использования языковых моделей для выполнения задач NLP.
- [Scale Spellbook](https://scale.com/spellbook): Платный продукт для создания, сравнения и запуска приложений языковых моделей.
- [PromptPerfect](https://promptperfect.jina.ai/prompts): Платный продукт для тестирования и улучшения запросов.
- [Weights & Biases](https://wandb.ai/site/solutions/llmops): Платный продукт для отслеживания обучения моделей и экспериментов с запросами.
- [OpenAI Evals](https://github.com/openai/evals): Открытая библиотека для оценки производительности задач языковых моделей и запросов.
- [LlamaIndex](https://github.com/jerryjliu/llama_index): Библиотека Python для расширения приложений LLM с помощью данных.
- [Arthur Shield](https://www.arthur.ai/get-started): Платный продукт для обнаружения токсичности, галлюцинаций, внедрения запросов и т. д.
- [LMQL](https://lmql.ai): Язык программирования для взаимодействия с LLM с поддержкой типизированных запросов, управления потоком, ограничений и инструментов.

### Руководства по запросам

- [Руководство по запросам от Brex](https://github.com/brexhq/prompt-engineering): Введение Brex в языковые модели и инженерию запросов.
- [promptingguide.ai](https://www.promptingguide.ai/): Руководство по инженерии запросов, демонстрирующее множество техник.
- [OpenAI Cookbook: Техники для улучшения надежности](https://github.com/openai/openai-cookbook/blob/main/techniques_to_improve_reliability.md): Немного устаревший (сентябрь 2022 года) обзор техник для запросов к языковым моделям.
- [Lil'Log Prompt Engineering](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/): Обзор литературы по инженерии запросов от исследователя OpenAI (по состоянию на март 2023 года).
- [learnprompting.org](https://learnprompting.org/): Вводный курс по инженерии запросов.

### Видеокурсы

- [DeepLearning.AI Эндрю Нг](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/): Краткий курс по инженерии запросов для разработчиков.
- [Давайте построим GPT от Андрея Карпати](https://www.youtube.com/watch?v=kCc8FmEb1nY): Подробное погружение в машинное обучение, лежащее в основе GPT.
- [Инженерия запросов от DAIR.AI](https://www.youtube.com/watch?v=dOxUroR57xs): Одночасовое видео о различных техниках инженерии запросов.

### Статьи о продвинутых запросах для улучшения рассуждений

- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models (2022)](https://arxiv.org/abs/2201.11903): Использование запросов с несколькими примерами для пошагового рассуждения улучшает их. Оценка PaLM на задачах математических словесных задач (GSM8K) повышается с 18% до 57%.
- [Self-Consistency Improves Chain of Thought Reasoning in Language Models (2022)](https://arxiv.org/abs/2203.11171): Голосование среди нескольких результатов улучшает точность еще больше. Голосование среди 40 результатов повышает оценку PaLM на математических словесных задачах до 74%, а `code-davinci-002` - с 60% до 78%.
- [Tree of Thoughts: Deliberate Problem Solving with Large Language Models (2023)](https://arxiv.org/abs/2305.10601): Поиск по деревьям пошагового рассуждения помогает еще больше, чем голосование по цепочкам рассуждений. Это повышает оценки `GPT-4` на творческом письме и кроссвордах.
- [Language Models are Zero-Shot Reasoners (2022)](https://arxiv.org/abs/2205.11916): Сообщение моделям, следующим инструкциям, чтобы думать пошагово, улучшает их рассуждения. Это повышает оценку `text-davinci-002` на математических словесных задачах (GSM8K) с 13% до 41%.
- [Large Language Models Are Human-Level Prompt Engineers (2023)](https://arxiv.org/abs/2211.01910): Автоматизированный поиск по возможным запросам нашел запрос, который повышает оценки на математических словесных задачах (GSM8K) до 43%, на 2 процентных пункта выше, чем у запроса, написанного человеком, в Language Models are Zero-Shot Reasoners.
- [Reprompting: Automated Chain-of-Thought Prompt Inference Through Gibbs Sampling (2023)](https://arxiv.org/abs/2305.09993): Автоматизированный поиск по возможным запросам цепочек рассуждений улучшил оценки ChatGPT на нескольких эталонах на 0–20 процентных пунктов.
- [Faithful Reasoning Using Large Language Models (2022)](https://arxiv.org/abs/2208.14271): Рассуждение может быть улучшено системой, которая объединяет: цепочки рассуждений, сгенерированные альтернативными запросами выбора и вывода, модель остановки, которая выбирает, когда останавливать циклы выбора-вывода, функцию значения для поиска по нескольким путям рассуждения и метки предложений, которые помогают избегать галлюцинаций.
- [STaR: Bootstrapping Reasoning With Reasoning (2022)](https://arxiv.org/abs/2203.14465): Рассуждение в цепочке мыслей может быть встроено в модели через дообучение. Для задач с ключом ответа примеры цепочек мыслей могут быть сгенерированы языковыми моделями.
- [ReAct: Synergizing Reasoning and Acting in Language Models (2023)](https://arxiv.org/abs/2210.03629): Для задач с инструментами или средой цепочка мыслей работает лучше, если вы предписываете чередовать **Re**asoning шаги (думая о том, что делать) и **Act**ing (получая информацию от инструмента или среды).
- [Reflexion: an autonomous agent with dynamic memory and self-reflection (2023)](https://arxiv.org/abs/2303.11366): Повторные попытки задач с памятью о предыдущих неудачах улучшают последующую производительность.
- [Demonstrate-Search-Predict: Composing retrieval and language models for knowledge-intensive NLP (2023)](https://arxiv.org/abs/2212.14024): Модели, дополненные знаниями через "поиск-затем-чтение", могут быть улучшены с помощью многошаговых цепочек поиска.
- [Improving Factuality and Reasoning in Language Models through Multiagent Debate (2023)](https://arxiv.org/abs/2305.14325): Генерация дебатов между несколькими агентами ChatGPT в течение нескольких раундов улучшает оценки по различным эталонам. Оценки по математическим словесным задачам повышаются с 77% до 85%.

## Вклад

Если есть примеры или руководства, которые вы хотели бы видеть, не стесняйтесь предлагать их на [странице проблем]. Мы также рады принять качественные запросы на внесение изменений, если они соответствуют содержанию репозитория.

[chatgpt]: https://chat.openai.com/
[openai api]: https://openai.com/api/
[api signup]: https://beta.openai.com/signup
[openai playground]: https://beta.openai.com/playground
[openai documentation]: https://beta.openai.com/docs/introduction
[openai community forum]: https://community.openai.com/top?period=monthly
[openai discord channel]: https://discord.com/invite/openai
[openai help center]: https://help.openai.com/en/
[openai examples]: https://beta.openai.com/examples
[openai blog]: https://openai.com/blog/
[issues page]: https://github.com/openai/openai-cookbook/issues
