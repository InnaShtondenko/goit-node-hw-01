# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list" https://monosnap.com/file/skNebGWPSfwDyefAee80NHHPVlPzGp

# Отримуємо контакт по id

node index.js --action="get" --id=5 https://monosnap.com/file/BpSCm2PdgQxrNS50BBWOLCcsy2fM4v

# Додаємо контакт

node index.js --action="add" --name="Mango" --email="mango@gmail.com" --phone="322-22-22" https://monosnap.com/file/LLcv1DGdn1lhKCbotBAlw55rmLAoT8

# Видаляємо контакт

node index.js --action="remove" --id=3 https://monosnap.com/file/hQFWsciUC31FZIRkL1XxZGo5c2Os5D
