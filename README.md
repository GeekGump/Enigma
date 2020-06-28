# Enigma machine ماشین انیگما
(this repositore is writed based on a video by [jadi](https://github.com/jadijadi) on youtube)
این مخزن بر اساس فیلمی که [جادی](https://github.com/jadijadi) در یوتیوب گذاشته ساخته شده

# requirements: نیازمندی ها

```
python2 پایتون ۲
pickle پیکل
```

# Generate new rotor settings: تولید کردن تنظیمات روتور جدید
my settings are setted in `rotor_state.rotor` but if you want your new rotors settings just run:
تنظیمات من در فایل بالا موجود هست ولی اگه خواستین میتونین برا خودتون بسازین دوباره با دستور زیر
```bash
python rotor_generator.py
```
if you use this for a chat or anything else you need to send your rotor settings to your client.
برا چت و این ریخت چیزا میتونین تنظیمات خودتونو که همون فایل روتور هست رو براشون بفرستین

# Run enigma: اجرا کردن انیگما
first enter your text in: اول متن زیر رو تغیر بدین فک کنم خط ۴۲ هست
```python
plain = "anything"
```
and run `python enigma.py` output for "anything" with my settings will be: "pbqdwlqk"
بعدش با دستوری که میبینین خروجی میگیرین که برای کلمه همه چیز با تنظیمات من شده اون قاطی پاتی که میبینین

and for decode this "pbqdwlqk" just change the ` plain = "pbqdwlqk"` to "anything"
برای دیکد کردنش کافیه همون متن خروجی رو بزارین داخل اون متغیر و دوباره انیگما رو ران کنین 
have problem? contact: [razyar](https://khoderazyar.ir) اگه مشکلی داشتین 
