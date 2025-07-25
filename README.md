# Alikhan_Grafana-installer
Bash-скрипт для автоматической установки и запуска Grafana на Debian/Ubuntu.

# Alikhan Grafana Installer

> Bash-скрипт для автоматической установки и запуска Grafana на Debian/Ubuntu.

##  Что делает скрипт

- Обновляет систему
- Устанавливает необходимые зависимости
- Добавляет GPG-ключ и репозиторий Grafana
- Устанавливает последнюю версию Grafana OSS
- Запускает и активирует `grafana-server`
- Показывает IP-адрес для входа в веб-интерфейс

---

##  Быстрый запуск

```bash
curl -o grafana.sh https://raw.githubusercontent.com/AlikhanKarabaevNEWPROJECT/Alikhan_Grafana-installer/main/grafana.sh
chmod +x install-grafana.sh
sudo ./install-grafana.sh
