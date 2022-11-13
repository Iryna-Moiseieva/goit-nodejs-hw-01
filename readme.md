# Start run CLI
node -v - version of node
npm -v - version of npm
npm init - initializes npm and create package.json
npm init -y - create package.json
npm install --save-dev nodemon - install nodemon
npm start - run CLI
npm run dev - run the development server

# Получаем и выводим весь список контактов в виде таблицы (console.table)
node index.js --action list
https://monosnap.com/file/Ixl7YiCrlIEVn3pStUg2zndmcbudF7

# Получаем контакт по id
node index.js --action get --id 5
https://monosnap.com/file/qhASBVmbGg89HQYDEr9YHqAwXwTvbW

# Добавялем контакт
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/Kki6HcR2Pwq8MvQJGNVyoXYkuVLeSW

# Удаляем контакт
node index.js --action remove --id=3
https://monosnap.com/file/UlytyA7fNyo9JYPLYQ2HBAQaWzV1Kx


