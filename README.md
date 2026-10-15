# MCP-сервер для покупок во ВкусВилле
### https://mcp.vkusvill.ru/mcp

Это официальный MCP-сервер ВкусВилла. Подключите его своему ИИ-помощнику, чтобы делегировать ему выбор и заказ продуктов.
Актуальный список тулов и инструкции для начала работы вы можете найти на странице MCP-сервера.

## Релизы 
### **0.1.** Публичный MCP-сервер https://habr.com/ru/companies/vkusvill/articles/981866/
* **Декабрь 2025 -** Экспериментальный MCP-сервер с тремя тулами:
  * *vkusvill_products_search*
  * *vkusvill_product_details*
  * *vkusvill_cart_link_create*
* **Март 2026**
  * Добавлена информация о составе и КБЖУ в ответ тула *vkusvill_products_search*
  *  Добавлены тулы:
      * *vkusvill_product_analogs*
      * *vkusvill_products_discount*
      * *vkusvill_shops*
* **Май 2026**
  * Добавлен тул *vkusvill_recipes*  
* **Июль 2026**
  * Изменен адрес сервера на https://mcp.vkusvill.ru/mcp и добавлена посадочная страница
  * Изменения в туле *vkusvill_products_search*:
    * Добавлен параметр *mode*: *full*, *short*, *custom*
    * В ответ добавлена информация о категории товаров (*facets.categories*)
    * Добавлен параметр *category_id*
  * Добавлен тул *vkusvill_product_barcode*

### **1.0.** MCP-сервер с авторизацией https://habr.com/ru/companies/vkusvill/articles/1094732/

* **Сентябрь 2026 -** MCP-сервер с авторизацией OAuth 2.0 + PKCE
  * Тул *vkusvill_products_search* делает поиск по актуальному для авторизованного пользователя каталогу
  * Добавлены тулы:
    * *vkusvill_orders_history*
    * *vkusvill_product_lp*
  * Увеличены rate limits
* **Октябрь 2026**
   * Добавлен тул *vkusvill_discounts_personal*
   * Тул *vkusvill_cart_link_create* возвращает омниканальную сссылку
