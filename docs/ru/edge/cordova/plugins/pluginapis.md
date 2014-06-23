---

license: Licensed to the Apache Software Foundation (ASF) under one or more contributor license agreements. See the NOTICE file distributed with this work for additional information regarding copyright ownership. The ASF licenses this file to you under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0
    
         Unless required by applicable law or agreed to in writing,
         software distributed under the License is distributed on an
         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
         KIND, either express or implied.  See the License for the
         specific language governing permissions and limitations
    

   under the License.
---

# API плагинов

Cordova поставляется с минимальным набором APIs, и проекты которым необходимы дополнительные API, добавляют их через плагины.

Вы можете осуществить поиск по всем существующим плагинам (включая сторонние плагины) с использованием [Реестра плагинов][1].

 [1]: http://plugins.cordova.io/

Традиционный набор плагинов Cordova следующий:

*   [Состояние батареи][2]
    
    > Отслеживает статус батареи устройства.

*   [Камеры][3]
    
    > Получает фото используя камеру устройства.

*   [Консоль][4]
    
    > Добавление дополнительных возможностей к console.log().

*   [Контакты][5]
    
    > Работа с базой данных контактных устройств.

*   [Устройство][6]
    
    > Соберите устройство конкретную информацию.

*   [Устройство движения (акселерометр)][7]
    
    > Использовать датчик движения устройства.

*   [Ориентацию устройства (компас)][8]
    
    > Получите направление, которое указывает устройство.

*   [Диалоги][9]
    
    > Визуальные уведомления.

*   [Файловая система][10]
    
    > Крюк в родной файловой системы через JavaScript.

*   [Передача файлов][11]
    
    > Крюк в родной файловой системы через JavaScript.

*   [Геолокация][12]
    
    > Сделайте ваше приложение местоположение известно.

*   [Глобализация][13]
    
    > Включите представление объектов, характерных для языка.

*   [InAppBrowser][14]
    
    > Запуск URL-адреса в другой экземпляр браузера в приложение.

*   [Средства массовой информации][15]
    
    > Запись и воспроизведение звуковых файлов.

*   [Захвата мультимедиа][16]
    
    > Захват файлов мультимедиа с помощью захвата приложений устройств в СМИ.

*   [Информацию о сети (подключение)][17]
    
    > Быстро проверьте состояние сети и сети сотовой связи информацию.

*   [Экран-заставка][18]
    
    > Скрывать и отображать экран-заставку приложения.

*   [Вибрация][19]
    
    > API-интерфейс для того чтобы вибрировать устройство.

 [2]: https://github.com/apache/cordova-plugin-battery-status/blob/master/doc/index.md
 [3]: https://github.com/apache/cordova-plugin-camera/blob/master/doc/index.md
 [4]: https://github.com/apache/cordova-plugin-console/blob/master/doc/index.md
 [5]: https://github.com/apache/cordova-plugin-contacts/blob/master/doc/index.md
 [6]: https://github.com/apache/cordova-plugin-device/blob/master/doc/index.md
 [7]: https://github.com/apache/cordova-plugin-device-motion/blob/master/doc/index.md
 [8]: https://github.com/apache/cordova-plugin-device-orientation/blob/master/doc/index.md
 [9]: https://github.com/apache/cordova-plugin-dialogs/blob/master/doc/index.md
 [10]: https://github.com/apache/cordova-plugin-file/blob/master/doc/index.md
 [11]: https://github.com/apache/cordova-plugin-file-transfer/blob/master/doc/index.md
 [12]: https://github.com/apache/cordova-plugin-geolocation/blob/master/doc/index.md
 [13]: https://github.com/apache/cordova-plugin-globalization/blob/master/doc/index.md
 [14]: https://github.com/apache/cordova-plugin-inappbrowser/blob/master/doc/index.md
 [15]: https://github.com/apache/cordova-plugin-media/blob/master/doc/index.md
 [16]: https://github.com/apache/cordova-plugin-media-capture/blob/master/doc/index.md
 [17]: https://github.com/apache/cordova-plugin-network-information/blob/master/doc/index.md
 [18]: https://github.com/apache/cordova-plugin-splashscreen/blob/master/doc/index.md
 [19]: https://github.com/apache/cordova-plugin-vibration/blob/master/doc/index.md

Переводы документации для этих плагинов могут быть найдены просматривая старые версии документации Cordova. Используйте выпадающее меню в верхнем правом углу сайта для выбора версии.