# Regex utils
Criei esse projeto para reutilizar expressões regulares criadas por mim e que são úteis no dia a dia.

* Nome
```js
^([a-zA-Zà-źÀ-Ź]{2,}((\s[a-zA-Zà-źÀ-Ź]{2,})*)?)$
```

* Email

```js
^([\w]+|[\w]+[\-\_\.]?[\w]+)+@([\w-]+\.)+[a-zA-Z\-]{2,4}$
```

* Telefone fixo e Celular

```js
^(([\(][\d]{2}[\)]|[\d]{2})[\s]?([9][1-9][\d]{3}|[1-9][\d]{3})[-]?[\d]{4})$
```

* Cep

```js
^[\d]{5}[\-]?[\d]{3}$
```

* CPF

```js
^(([\d]{3}[\.]){2}[\d]{3}[\-][\d]{2}|[\d]{11})$
```

* CNPJ
```js
^([\d]{2}[\.][\d]{3}[\.][\d]{3}[\/][\d]{4}[\-][\d]{2}|[\d]{14})$
```