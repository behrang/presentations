# Tosan Tech Talk - Node.js

هدف Node ساختن برنامه‌های شبکه Scalable است. Node به تعداد Connectionهای بسیار زیادی می‌تواند سرویس دهد. هر Connection بار بسیار کمی روی سرور می‌گذارد. این روش در برابر روش‌های امروزی سیستم عامل‌ هاست که برای هر Connection یک Thread می‌گیرند. برنامه‌های شبکه برپایه Thread به نسبت، کارایی پایینی دارند و به کار گیری آن‌ها سخت است. Node از دیدگاه حافظه، نسبت به سامانه‌هایی که برای هر Thread نزدیک ۲ مگابایت فضا می‌گیرند کارایی بالاتری در فشار بالا ‌‌دارد. از آن گذشته کاربران Node نگران بن بست‌ها (Dead-lock) و قفل‌ها نیستند. تقریبا هیچ تابعی در Node مستقیم به I/O دسترسی ندارد و بنابراین هیچگاه پروسه نمی‌ایستد. چون هیچ چیز نمی‌ایستد، برنامه نویسان کم تجربه‌تر هم می‌توانند برنامه‌های سریع بسازند.

برای دیدن اسلایدها به این نشانی بروید: http://behrang.github.com/presentations/node.js/2011-09-07/

Licensed under [MIT License](http://en.wikipedia.org/wiki/MIT_License), see [license page](https://github.com/pepelsbey/shower/wiki/License) for details.
