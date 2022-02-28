

# جملة الدوران ForEach

  

## في هذا التمرين سنقوم بعمل صور الإيموجي كما هو موضح بالصورة.

<p align="center">
<img width="285" alt="emoji" src="https://user-images.githubusercontent.com/60436597/155885124-1c3c03d9-eded-42fc-9270-f9d02e1d60c4.png">
</p>


### عمل كود للمصفوفة :

```
var emooji = ["your emojis here"] 
```
<p dir="rtl">

### عمل كود forEach :
</p>

```
ForEach(0..<3) { oneEmoji in

Text("\(emooji[oneEmoji])")

}
```

---


## تمرين



### قم بعمل fork من رابط gitHub ، ثم قم بإنشاء تطبيق جديد في XCode.
### 1. قم بعمل مصفوفة تحتوي على أشكال الإيموجي، ستكون من نوع string.


### 2. سيكون هناك ٣ من ForEach و ٣ hstack .وكل ForEach ستكون في hstack ، وهذه الثلاثه ستكون داخل vstack .


### 3. طريقة ترتيب العناصر المصفوفه موجوده تحت 
<p dir="rtl">
<strong>مساعدة صغيرة :  لإظهار نص الإيموجي بجميع اشكاله، فيجب عمل الدوران بهذه الطريقة .</strong></p>


// لعمل الصف الأول للثلاث ٣ ايموجي
```
ForEach(0..<3) { oneEmoji in

                Text("\(emooji[oneEmoji])")

}
```

// لعمل الصف الثاني للثلاث ٣ ايموجي، نغير الدوران نخليه من ٣ إلى أقل من ٦

// لعمل الصف الثالث للثلاث ٣ ايموجي، نغير الدوران نخليه من ٦ إلى أقل من ٩


---



## بونس ✨✨✨



### يمكن عمل واختصار الخطوة الثانية ب اثنان من ForEach في داخل بعض ، أحدهما سيكون عمودي والآخر أفقي.



### مساعدة صغيرة : لإظهار نص الإيموجي بجميع اشكاله، فيجب إدخال هذه العمليات الحسابية البسيطة.

```
Text("\(emoji[(horizontalForEach+verticalForEach)+verticalForEach+verticalForEach])")
```

### حيث ان horizontalForEach هو forEach الافقي ، و verticalForEach هو forEach العمودي.
