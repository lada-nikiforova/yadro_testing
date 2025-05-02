const FETCH_DATA = 'FETCH_DATA';

const CLEAR_DATA = 'CLEAR_DATA';

const SELECT_ROW = 'SELECT_ROW';


const fetchData(payload) 

        type: FETCH_DATA,

        payload //данные, которые получаем с сервера
        

const clearData

    type: CLEAR_DATA


const initialState 

    data: []


const selectRow(index)

    type: SELECT_ROW,
    
    payload: index

