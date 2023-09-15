gettext-playground
==================
```
echo Compiling translation files...
for %%L in (cs,de,es,hr_HR,pt_BR,ru,tr) do (
	mkdir build\resource\msg\%%L\
	msgfmt ..\msg\%%L.po -o build\resource\msg\%%L\%APP_NAME%.mo
	)
echo Done!
```
