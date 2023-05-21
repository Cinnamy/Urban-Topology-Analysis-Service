## Frontend
- [ ] Скоретировать отрисовку графа. Прямо сейчас используется сортировка при добавлении ребер, это не совсем правильно. Стоит либо добавить sequence в модель Edge, либо для отрисовки возвращать отдельный список ребер. Объявляется: `\ui\src\app\services\town.service.ts:9`
Используется: `ui\src\app\town\town.component.ts:132`
- [ ] Возможно стоит скорректировать имена в front'е
- [ ] Скоректировать объекты для создания графов
- [ ] Скоректировать масштаб при большом количестве точек
- [ ] Поменять вывод графов (от вертикальных переходов перейти к горизонтальным)
## Backend
- [ ] Исправить `id_dist` на `id_dest`
- [ ] Привести все к виду `id_...`
- [ ] Попытаться все перевсти на `async await`
- [ ] Может вернуться к SQLAlchemy
- [ ] Добавить download по клику
- [ ] Удалить ненужные участки кода
- [ ] Возвращать 3 `DataFrame` для обратного графа
- [ ] Попробовать регионы перевести в БД
- [ ] При использовании границы для всего Питера (граница 1 уровня) возникают проблемы `/api/city/graph/region/?city_id=2`