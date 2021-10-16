# RecyclerItemClickListener
### **Snippet de código para facilitar a impplementação de Listener de clique normal e clique longo para RecyclerView.**

## Implementação
Ele deve ser implementado no listener **addOnItemTouchListener**
```
recyclerView.addOnItemTouchListener(
  new RecyclerItemClickListener(
    getApplicationContext(),
    recyclerView,
    new RecyclerItemClickListener.OnItemClickListener() {
      @Override
      public void onItemClick(View view, int position) {
        ADICIONE AQUI O QUE QUER QUE SEJA FEITO EM UM CLIQUE NORMAL
      }

      @Override
      public void onLongItemClick(View view, int position) {
        ADICIONE AQUI O QUE QUER QUE SEJA FEITO EM UM CLIQUE LONGO
      }
      @Override
      public void onItemClick(AdapterView<?> parent, View view, int position, long id) {
        
      }
```
