
onClick "Получить данные"
    onDispatch(fetchData())

onClick "Очистить данные"
    onDispatch(clearData())

onClick "Сохранить данные"
    call exportToCVS
