# مورفیس پروٹیکشن فنڈ کی تجویز
## تعارف
مورفیس وائٹ پیپر "پروٹیکشن فنڈ" کے مقصد کے لیے تمام MOR اخراجات کا 4% مختص کرتا ہے اور اس کے وسائل کی ضرورت ہونے کی صورت میں کوڈ پرووائیڈرز کو اوریکلز کے طور پر عمل کرنے کا اختیار دیتا ہے۔
عمل کی قسمیں:
- حملوں سے بچنے کے لیے بگ باؤنٹی کی ادائیگی۔
- نئے سمارٹ کانٹریکٹس کو ڈپلائے کرنے سے پہلے آڈٹس کی ادائیگی۔
- جاری حملے کی صورت میں سمارٹ کانٹریکٹس کو روکنا۔
- حملے کے بعد ادائیگی کے لیے سگنلنگ اور میکانزم۔
- اہم نقصان کی واقعہ کی صورت میں منصوبہ (ہارڈ فورک سیناریو)
## معمولی ادائیگیوں کے لیے مقرر شدہ حالات کا ٹرگر
سمارٹ کانٹریکٹس ایتھریم نیٹ ورک پر زندہ ہونے سے پہلے یہاں مقرر کردہ حالات ہیں جن کے تحت پروٹیکشن فنڈ MOR یا stETH ادا کرے گا۔
## ادائیگیوں کی قسمیں:
1. بگز جو دریافت کی گئیں اور مورفیس کیپٹل، کوڈ، کمپیوٹ، کمیونٹی یا پروٹیکشن فنڈ سمارٹ کانٹریکٹ کے ڈویلپرز کو ذمہ دارانہ طور پر ظاہر کی گئیں۔
2. نئے سمارٹ کانٹریکٹس کو مورفیس نیٹ ورک پر ڈپلائے کرنے سے پہلے آڈٹس کی ادائیگی۔
3. مورفیس سمارٹ کانٹریکٹ کے استحصال کی صورت میں MOR یا stETH کے صارفین کے نقصانات۔
4. ان پرووائیڈرز کو مکمل بنانا جنہوں نے مورفیس سمارٹ کانٹریکٹ کی ناکامی کی صورت میں MOR اخراجات وصول نہیں کیے۔
پروٹیکشن فنڈ سے ادائیگیوں کی رقمیں بگ، نقصان یا اخراجات کی غلطی کے تناسب میں ہونی چاہیے۔
## سمارٹ کانٹریکٹس کے لیے روکنے کی حالات
نقصانات کی ادائیگیوں کے لیے حالات کا تعین کرنے سے پہلے، جاری حملے کی صورت میں سمارٹ کانٹریکٹس کو روکنے کے لیے حالات کا ٹرگر ہونا چاہیے۔
## ادائیگی کے لیے سگنلنگ اور میکانزم
کوڈ پرووائیڈرز ادائیگی کے ٹرگر ہونے پر سگنلنگ میں حصہ لیں گے۔ پہلے ایک واقعہ کی تفصیل بیان کی جائے گی اور متاثرہ سمارٹ کانٹریکٹ کے GitHub ریپوزٹری پر پوسٹ کی جائے گی۔ اس میں متاثرہ ایڈریسز اور MOR اور / یا stETH کی مقداروں کی ایک فہرست شامل ہوگی۔
اگر کوڈ پرووائیڈرز کی اکثریت (ان کے ہولڈ کردہ MOR ٹوکنز کے وزن کے ذریعہ ناپا گیا) جو سگنلنگ کی مدت (زیادہ سے زیادہ 7 دن) میں حصہ لیتے ہیں، رپورٹ کو TRUE کے طور پر تصدیق کرتے ہیں، تو ایک ادائیگی کا ٹرگر ہو جائے گا۔
ایک بار جب ادائیگی کا ٹرگر ہو جاتا ہے تو سافٹ ویئر ڈویلپرز کو متاثرہ ایڈریسز کو مخصوص مقداروں میں ادائیگی کی اجازت دینے کے لیے پیغام بھیجے گا۔
## اہم نقصان کی واقعہ کی صورت میں منصوبہ
اہم نقصان کی واقعہ ایسے واقعہ کے طور پر معین کی گئی ہے جس میں MOR کے نقصانات پروٹیکشن فنڈ کے کل وسائل سے تجاوز کر جائیں۔ اس صورت میں، MOR کی ادائیگی کے بجائے کوڈ پرووائیڈرز کو نئے سمارٹ کانٹریکٹس کو ڈپلائے کرنا چاہیے اور دستی طور پر متاثرہ MOR بیلنسز کو درست کرنا چاہیے۔ یہ عملی طور پر کوڈ / MOR بیلنسز میں ایک ہارڈ فورک کا باعث بنے گا اور تمام پرووائیڈرز، ٹوکن ہولڈرز اور دیگر انفراسٹرکچر پرووائیڈرز کو نئے سمارٹ کانٹریکٹس کے لیے اپنے کوڈ کو اپ ڈیٹ کرنا ہوگا۔
اہم نقصان کی واقعہ میں stETH کے نقصان کی صورت میں، پروٹیکشن فنڈ ہر ایک کے نقصانات کی مقدار کے تناسب میں زیادہ سے زیادہ حد تک ادائیگی کرے گا۔
## نتیجہ
سافٹ ویئر میں بگز اور غلطیاں ایک حقیقت ہیں اور بٹ کوائن کے دو غیر ارادی ہارڈ فورکس سے لے کر ایتھریم کے ابتدائی دنوں میں ڈاؤ کے تاریخ کو نشان زد کرتی ہیں۔
لہذا مختلف منظرناموں اور معاملات کے لیے پہلے سے منصوبہ بندی کرنا اور ان کا انتظام کرنے کا طریقہ ایک دانشمندانہ نقطہ نظر ہے جو خطرات کے خلاف تحفظ فراہم کرتا ہے اور دوسری صورت میں خطرات کو کم کرتا ہے۔ خوش قسمتی سے، پروٹیکشن فنڈ میں پہلے سے وسائل مختص کرنے کے ساتھ، اور پروٹیکشن فنڈ کا حصہ AMM میں LP انعامات حاصل کرنے کے ساتھ، صارفین کے تحفظ کے لیے مختص وسائل کے ساتھ وقت کے ساتھ بڑھنے کی توقع کی جاتی ہے۔
