## Installation
- You need to install the package on your project
```sh-session
npm install echo.db
yarn add echo.db
```
## How To Use
```js
const db = require('echo.db');

db.set('key','value');// لتعيين البيانات لقاعدة البيانات.
db.get('key');// للحصول على البيانات 
db.delete('key');// لحذف مفتاح من قاعدة البيانات.
db.has('key','value');// إرجاع "صواب" أو "خطأ".

db.add('key', 12;);// لإضافة رقم إلى المفتاح.
db.substract('key', 6);// لطرح رقم من المفتاح.
db.push('key', 12);// لتعيين البيانات في النهاية.
db.math("key","+",6);// لحساب الأرقام.

db.fetch(); // لجلب البيانات من قاعدة البيانات.
db.fetchAll();// لجلب جميع البيانات.
db.all();// للحصول على جميع البيانات في قاعدة البيانات.

db.backup("Filename");// لعمل ملف نسخ احتياطي.
db.reset();// لحذف جميع البيانات وقاعدة البيانات.

```
