# dicas-tips-dotnet

#### 16:31 22/12/2022

em dotnet core, o que significa o seguinte código?
```  [HttpGet]
    public ActionResult<IEnumerable<string>> Get()
    {
        return new string[] { "value1", "value2" };
    }
```

Esse código é uma ação de um controlador de API em um aplicativo ASP.NET Core. Ele representa uma rota HTTP GET que retorna uma lista de strings como resultado.

A anotação [HttpGet] indica que essa ação só deve ser executada quando uma solicitação HTTP GET é enviada para a rota correspondente. A palavra-chave ActionResult<T> é um tipo de retorno genérico que pode conter um resultado de qualquer tipo, no caso, uma lista de strings.

Quando uma solicitação é enviada para essa rota, o método Get() é chamado e retorna uma lista de strings com os valores "value1" e "value2".
