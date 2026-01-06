  Wortex × Horizon VPN 🌐

  <div align="center">

  ![Android (https://img.shields.io/badge/Platform-Android_8.0%2B-3DDC84?logo=android&logoColor=white)](https://github.com/leo20112022/wortex-vpnclient/releases)
  ![Core (https://img.shields.io/badge/Core-Xcore_Native-blue?logo=c%2B%2B&logoColor=white)](https://github.com/leo20112022/wortex-vpnclient)
  ![Release (https://img.shields.io/github/v/release/leo20112022/wortex-vpnclient?color=orange&label=Latest%20Build)](https://github.com/leo20112022/wortex-vpnclient/releases/latest)

  Wortex — это флагманский Android-клиент для Horizon VPN, построенный на базе проприетарного ядра Xcore.

  Мы переосмыслили опыт использования VLESS Reality: вместо сложных конфигов — интерактивная карта, вместо падения скорости — Zero-Copy маршрутизация, вместо блокировок — Chaos Mode.

  📥 Скачать APK (https://github.com/leo20112022/wortex-vpnclient/releases/latest) • 💬 Поддержка (https://t.me/Niktoworking)

  </div>

  ---

  📸 Интерфейс

  <p align="center">
    <img src="https://github.com/user-attachments/assets/84e598b4-f100-430c-b38e-4a6a6f251ba5" width="19%" alt="Dashboard" />
    <img src="https://github.com/user-attachments/assets/9068e423-e7dc-4f00-bf84-ef6a4935d9fa" width="19%" alt="Map Selection" />
    <img src="https://github.com/user-attachments/assets/cee1c6da-7bec-4172-89d0-6a59da49825e" width="19%" alt="Settings" />
    <img src="https://github.com/user-attachments/assets/63bf8300-61fa-43f7-8a81-b193a8084357" width="19%" alt="Speedtest" />
    <img src="https://github.com/user-attachments/assets/ed5fde53-b938-4ccb-8096-3eca34c396e4" width="19%" alt="Menu" />
  </p>

  ---

  🔥 Ключевые возможности

  🚀 Ядро Xcore (Next-Gen Performance)
  Собственная оптимизация Xray-core, недоступная в стандартных клиентах:
   * Энергоэффективность: Сниженное потребление батареи благодаря оптимизации JNI-моста.
   * Multipath TCP/UDP: Бесшовное переключение между Wi-Fi и LTE без обрыва соединения.
   * Zero-Copy TUN: Прямая передача пакетов в сетевой стек Android, минимизирующая задержки (Latency).

  🛡 Обход цензуры и DPI
   * Chaos Mode: Рандомизация параметров соединения (Jitter, Packet Size) для защиты от ML-анализаторов трафика.
   * VLESS Reality: Передовой протокол маскировки под легитимные сайты.
   * Lockdown: Режим повышенной скрытности для сетей с агрессивной фильтрацией.

  🗺 Визуальный контроль
   * Интерактивная карта: Выбирайте локацию касанием, а не поиском в списке.
   * Live Ping: Цветовая индикация задержки в реальном времени прямо на карте.

  ⚡ Smart Routing (Split Tunneling)
  Гибкая настройка правил для локальных сервисов:
   * Умные исключения: Приложения банков, госуслуг и локальных маркетплейсов автоматически работают напрямую (Direct), остальной трафик идет через шифрованный туннель.
   * Возможность ручного выбора приложений для VPN.

  ---

  🛠 Технические спецификации


  ┌───────────────┬───────────────────────────────────────────────────────────────────┐
  │ Компонент     │ Технологии                                                        │
  ├───────────────┼───────────────────────────────────────────────────────────────────┤
  │ Протоколы     │ VLESS Reality (TCP + XTLS-Vision / gRPC / WS / HTTPUpgrade)       │
  │ Безопасность  │ uTLS (Randomized/Chrome/iOS fingerprints), Anti-Active Probing    │
  │ Маршрутизация │ GeoIP, Geosite, Custom Rulesets                                   │
  │ Диагностика   │ Встроенный True-Speedtest (Download/Upload/Jitter) внутри туннеля │
  └───────────────┴───────────────────────────────────────────────────────────────────┘

  ---

  🗺 Roadmap & Статус разработки

  ✅ Реализовано (v1.1+)
   - [x] Zero-Copy TUN Routing (Сверхбыстрый стек)
   - [x] Multi-Path Handover (Авто-смена сети Wi-Fi/4G)
   - [x] CDN-Edge Selection (Выбор лучшего узла)
   - [x] Динамическая фрагментация (Hello Client randomizer)

  🚧 В разработке (v1.1+)
   - [ ] Network Health Monitor (Анализ потерь пакетов 24/7)
   - [ ] Протокольный "Double-Hop" (Цепочка из двух серверов для полной анонимности)
   - [ ] Web-Parrot (Генерация фонового "шума" для имитации веб-серфинга)

  ---

  📥 Установка и Обновление

  Актуальные сборки доступны в разделе Releases.
  Приложение совместимо с устройствами на базе Android 8.0 (Oreo) и выше.

  <img src="https://img.shields.io/badge/Download-APK-blue?style=for-the-badge&logo=android"> (https://github.com/leo20112022/wortex-vpnclient/releases/latest)

  ---

  ⚠️ Disclaimer

  Wortex и ядро Xcore являются инструментами для защиты приватности данных и обеспечения доступа к информации. Используя данное программное обеспечение, вы обязуетесь соблюдать законодательство страны вашего пребывания.

  ---
  <div align="center">

  Developed by Leo
  Telegram (https://t.me/Niktoworking)

  </div>
