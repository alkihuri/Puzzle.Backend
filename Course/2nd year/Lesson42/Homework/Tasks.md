﻿Урок 44: Dependency Injection (DI)

Обязательная часть:

Создайте приложение, которое использует Dependency Injection для внедрения зависимостей. Например, создайте интерфейс IProductService и реализацию ProductService, которая будет возвращать список продуктов.
Внедрите зависимость в контроллер, чтобы он использовал ProductService для получения данных.
Продвинутая часть:

Используйте DI для внедрения зависимости в несколько слоев приложения. Создайте два дополнительных сервиса (например, IOrderService и ICustomerService).
Настройте автоконфигурацию DI контейнера так, чтобы зависимости автоматически внедрялись в контроллеры при запуске приложения.