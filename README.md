# Порфирий — документы

- [porfiry-diag-1.pdf](porfiry-diag-1.pdf) — диагностика «ответ одной буквой» на сервере Astra Linux.
- [porfiry-diag-2.pdf](porfiry-diag-2.pdf) — сброс, скрипт проверки ресурсов porfiry-check, проверочный файл и снижение памяти Ollama: всё в одном документе.
- [porfiry-fix-2.zip](porfiry-fix-2.zip) — исправление 2 одним архивом: новый контроллер, тесты, apply.sh, rollback.sh, проверка porfiry-selfcheck.php, porfiry-check.sh и инструкция. Внутри — [porfiry-fix-2.pdf](porfiry-fix-2.pdf).
- [porfiry-diag-3.zip](porfiry-diag-3.zip) — диагностика 3: рвёт ли Apache поток. Инструкция — README.txt в архиве.
- [porfiry-apache-config.txt](porfiry-apache-config.txt) — что в Apache/PHP может обрывать поток и что поменять (то же — CONFIG.txt в porfiry-diag-3.zip).
- [porfiry-fix-3.zip](porfiry-fix-3.zip) — исправление 3: правка Apache для потока чата (apache-fix.sh для 000-default) + проверка apache-check.sh. Инструкция — INSTRUCTION.txt в архиве.
- [porfiry-fix-science.zip](porfiry-fix-science.zip) — исправление научного чата, только веб-сервер .69: ответ не обрывается «Сервер перестал отвечать», пока модель рассуждает; ODT и PDF собираются (LibreOffice без экрана). Скрипт update-web.sh, инструкция на одну страницу — ИНСТРУКЦИЯ.pdf в архиве.
- [porfiry-test-28-10-morning.zip](porfiry-test-28-10-morning.zip) — утро 28.10: обновление сайта (галочка «Подумать тщательнее» в научном чате, понятные ошибки LibreOffice, исправленная проверка) и диагностика всех трёх серверов (diag-web.sh, diag-models.sh). Инструкция — ИНСТРУКЦИЯ.pdf в архиве.
