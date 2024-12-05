Os navegadores tendem a ter configurações de CSS por padrão que não são muito favoráveis a pessoas que desenvolvem site, pois podem diversas vezes causar bug's e por isso criamos um arquivo específico para dar um reset nessas config's. Está então uma das configurações de reset mais utilizadas:

```
* {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}

body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
```

 > e para fazer a conexão do arquivo com a página deixe sempre como primeiro entre as tags links

```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu portifólio</title>
    *<link rel="stylesheet" href="reset.css">*
    <link rel="stylesheet" href="style.css">
</head>
```
