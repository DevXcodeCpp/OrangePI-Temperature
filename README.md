# Orange Pi CPU Monitor 🌡️

Легкий и красивый скрипт на Bash для мониторинга температуры процессора в реальном времени. Специально оптимизирован для Orange Pi и других одноплатных компьютеров на базе процессоров Rockchip (RK3399 и др.).

## ✨ Особенности
* 🚀 **Минимальное потребление ресурсов** — не нагружает систему.
* 🎨 **Красивый вывод** — цветная индикация и обновление строки без спама в консоль.
* 🛠️ **Простая установка** — работает как системная команда.
* 🧹 **Авто-очистка** — корректно возвращает курсор в терминал после выхода (Ctrl+C).

## 🚀 Быстрая установка (One-liner)

Просто скопируйте и вставьте эту команду в терминал вашего Orange Pi:

```bash
curl -sL [https://raw.githubusercontent.com/DevXcodeCpp/OrangePI-Temperature/main/cpu-temp.sh](https://raw.githubusercontent.com/DevXcodeCpp/OrangePI-Temperature/main/cpu-temp.sh) -o cpu-temp.sh && chmod +x cpu-temp.sh && sudo mv cpu-temp.sh /usr/local/bin/cpu-temp
