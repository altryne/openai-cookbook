# Kusto как векторная база данных

[Azure Data Explorer, также известный как Kusto](https://azure.microsoft.com/en-us/products/data-explorer), представляет собой облачный сервис аналитики данных, который позволяет пользователям выполнять продвинутый анализ больших наборов данных в реальном времени. Он особенно хорошо подходит для работы с большими объемами данных, что делает его отличным выбором для хранения и поиска векторов.

Kusto поддерживает специальный тип данных под названием dynamic, который может хранить неструктурированные данные, такие как массивы и свойства. [Тип данных dynamic](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/scalar-data-types/dynamic) идеально подходит для хранения векторных значений. Вы можете дополнительно улучшить векторное значение, храня метаданные, связанные с исходным объектом, в отдельных столбцах вашей таблицы.
Kusto также поддерживает встроенную функцию [series_cosine_similarity_fl](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/functions-library/series-cosine-similarity-fl) для выполнения поиска по сходству векторов.

[Начните работу](https://aka.ms/kustofree) с Kusto бесплатно.

![Kusto_Vector](./images/kusto_vector_db.png)

## Начало работы с Kusto и встраиваниями Open AI

### Демонстрационный сценарий

![Wiki_embeddings](./images/wiki_embeddings.png)

![semantic_search_flow](./images/semantic_search_user_flow.png)

Если вы хотите попробовать эту демонстрацию, пожалуйста, следуйте инструкциям в [блокноте](Getting_started_with_kusto_and_openai_embeddings.ipynb).

Это позволит вам:

1. Использовать предварительно вычисленные встраивания, созданные с помощью API OpenAI.

2. Хранить встраивания в Kusto.

3. Преобразовать исходный текстовый запрос в встраивание с помощью API OpenAI.

4. Использовать Kusto для выполнения поиска по косинусному сходству в хранимых встраиваниях.
