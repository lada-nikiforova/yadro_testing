function appReducer(state = initialState, action) 
    switch(action.type) 
        case FETCH_DATA:
        maxRow = rowWithMaxValue(action.payload) 
        return {
            ...state, 
            data: action.payload,
            selectedRow: maxRow};
        case CLEAR_DATA: return { ...state, data: [], selectedRow: null };
        case SELECT_ROW: return { ...state, selectedRow: action.payload}

        
        default: return state;
