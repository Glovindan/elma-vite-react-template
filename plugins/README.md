# Расширения

> Папка для систематического хранения пользовательских расширений используемых для сборки в `vite.config.ts`

## htmlIncludePlugin

> Расширение для возможности подключения HTML файлов в точку входа `index.html` через инструкцию `@@include('path/your_html.html')`

### Пример

```
<!doctype html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
	</head>
	<body>
		<div class="example-widget-container">
			@@include('./src/components/filterPanel/filterPanel.html')
			@@include('./src/components/table/table.html')
		</div>
	</body>
	<script type="module" src="/src/main.ts"></script>
</html>
```
