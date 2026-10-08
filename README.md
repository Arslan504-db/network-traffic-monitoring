# Исследование методов мониторинга сетевого трафика

Курсовая работа по дисциплине «Защита информационных процессов в автоматизированных системах». Направление 10.03.01 «Информационная безопасность».

## 🎯 Задача

Провести сравнительный анализ методов мониторинга сетевого трафика и определить их применимость для организаций разного масштаба.

## 🛠 Что рассмотрено

- **Пассивный мониторинг** — Wireshark, NetFlow, ntopng
- **Активный мониторинг** — iPerf, Nagios, SmokePing
- **DPI (Deep Packet Inspection)** — Snort, Cisco Umbrella
- **Машинное обучение** для обнаружения аномалий
- **SDN** (Software-Defined Networking) — VMware NSX, OpenDaylight
- **Big Data** — Hadoop, Apache Spark, Elasticsearch

## 🧰 Инструменты

```
Wireshark  |  NetFlow   |  Nagios
Cisco Umbrella  |  Hadoop  |  Splunk
```

## 📊 Что сделано

1. Проведён аналитический обзор научных публикаций по теме
2. Составлена классификация методов мониторинга
3. Проведён сравнительный анализ по критериям:
   - функциональные возможности
   - архитектура
   - сложность настройки
   - эффективность выявления угроз
   - совместимость и интеграция
4. Разработаны практические рекомендации для малых, средних и крупных организаций

## 📸 Доказательства

### Анализ трафика в Wireshark
![Wireshark](https://raw.githubusercontent.com/Arslan504-db/network-traffic-monitoring/main/screenshot_wireshark.png)

### Мониторинг в Nagios
![Nagios](https://raw.githubusercontent.com/Arslan504-db/network-traffic-monitoring/main/screenshot_nagios.png)

### Анализ потоков в NetFlow
![NetFlow](https://raw.githubusercontent.com/Arslan504-db/network-traffic-monitoring/main/screenshot_netflow.png)

## 📚 Что я узнал

- Как анализировать pcap-файлы в **Wireshark**
- Чем **пассивный** мониторинг отличается от **активного**
- Как работает **DPI** и где он применяется
- Какие методы мониторинга подходят для разных типов организаций
- Как использовать **машинное обучение** для обнаружения аномалий

## 🔗 Связанные проекты

- [Мини-SIEM на ELK](https://github.com/Arslan504-db/diploma-siem-education)
- [PKI на OpenSSL](../pki-openssl-lab)
- [Пентест-лаборатория](../pentest-lab-report)
