Взаимодействовать с модулем возможно без развертывания локального окружения.
# Ключевые элементы: 
- ссылка на Telegram бота для взаимодействия: https://t.me/AGMKAISupport_bot.
- ссылка на Google Sheets с листами KB и Logs в режиме чтения: https://docs.google.com/spreadsheets/d/1yiLkF0MK8WO4EiMAohjzTUWwst9VtU3C1DX401nRS3I/edit?usp=sharing.
- входные файлы для RAG на Google Drive: https://drive.google.com/drive/folders/1S7FSGvb8-Qg3Vl-sTWlygjlpZ7t9g6B9?usp=drive_link либо же в папке knowledge_base.
- json на GitHub.
# Инструкция по проверке:
- перейти по ссылке Telegram бота;
- отправить один из демонстрационных запросов: Как быстро проверить качество входных данных; Как посчитать отклонение план факт; Какие данные нужны для начала формирования плана; Сформируй черновик пояснения по KPI за период;
- убедиться, что ответ содержит блок «Источники» с doc_name и chunk_id;
- при необходимости открыть Google Sheets и убедиться, что запрос записан в Logs.
