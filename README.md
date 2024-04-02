# Список сделанных улучшений
- Реализовал useTrottle
- Декомпозировал файл по FSD ( разделил на абстрактые уровни api, бизнес логики и представления)
- Вынес API_URL в env переменные
- Исправил типы
- Доработал button компонент, прокидывание пропсов и ref
- Добавил кеширвоание при запросе случайного ползователя на уровне хука useRandomUser
- Добавил disabled и loader состояние ( условное ) при нажатии на кнопку, просто показываю что оно должно быть здесь, не делал упор на дизайн
- Использовал useCallback и useMemo чтобы избежать лишних рендеров
- Добавил перехват исключений ошибок при запросах

# Список предложений
- Реализовать клиент для взаимодействия с беком, в него прокинуть baseUrl из env переменных, чтобы не пришлось указывать его в каждом запросе, в этом же клиенте реализовать Interceptors которые будут обрабатывать общие ошибки получаемые при запросах  

