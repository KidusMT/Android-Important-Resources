Important Android Open-Source Resources and Blogs 
=======
Best android materials link and resource websites and repos.

## QR CODE
Scanning:
  * https://demonuts.com/scan-barcode-qrcode/
  * https://github.com/zxing/zxing
  
Generating:
  * Blog for [sample code](https://www.mysamplecode.com/2012/09/android-generate-qr-code-using-zxing.html#comment-form_3020102673987308109)
  * ZXing ("Zebra Crossing") [Repo](https://github.com/zxing/zxing)
  * Sample [code](https://github.com/phishman3579/android-quick-response-code)
## Image compression for decreasing resource file size
 * [Tinypng](https://tinypng.com/)
 
## SVG to XML Converter online
 * [Free and works well](https://inloop.github.io/svg2android/)
 * [Paid but better with some vectors](https://svg2vector.com/)
 
## Architectures 
 MVP:
  * Mindork: [Github](https://github.com/MindorksOpenSource/android-mvp-architecture) and [Website](https://mindorks.com/)

## Android Patterns
 * https://unitid.nl/androidpatterns/

## Android Printing
 * github repos [android-printer](https://github.com/topics/android-printer)
 * Android Developers [Documentation](https://developer.android.com/training/printing)

## Icons for free
 * [Flaticon](https://www.flaticon.com/)

## Time Picker
 * [Blog](https://www.codingdemos.com/android-timepicker-edittext/)
 * stackoverflow [style](https://stackoverflow.com/questions/11077530/how-to-change-the-default-color-of-datepicker-and-timepicker-dialog-in-android) [setting time when poping up](https://stackoverflow.com/questions/12494074/android-setting-time-in-time-picker-with-the-time-shown-in-text-view)
 * time picker restrictions [stackoverflow](https://stackoverflow.com/questions/13516389/android-timepickerdialog-set-max-time) and also [this answer](https://stackoverflow.com/questions/34253379/datepicker-and-timepicker-set-max-and-min-values) and [library on github](https://github.com/wdullaer/MaterialDateTimePicker#timepickerdialog-setdisabledtimestimepoint-times)
 
 ## OpenID Authorization
  * [AppAuth](https://github.com/openid/AppAuth-Android/)
  
 ## Time Related 
  * [Joda-Time](https://github.com/dlew/joda-time-android) and [Documentation](https://www.joda.org/joda-time/userguide.html) and [Operations with JodaTime](https://www.mkyong.com/java/how-to-calculate-date-time-difference-in-java/) and many related [examples](https://www.programcreek.com/java-api-examples/?ClassName=joda&action=search&submit=Search)
  * Compareing two dates with JodaTime library from [stackOverflow](https://stackoverflow.com/questions/13764106/comparing-two-dates-using-joda-time) answer best answer from [JB Nizet](https://stackoverflow.com/users/571407/jb-nizet) or the code below
  
   ```java
   System.out.println(d.toDateMidnight().isEqual(e.toDateMidnight()));
   ```
   or
    
   ```java
   System.out.println(d.withTimeAtStartOfDay().isEqual(e.withTimeAtStartOfDay()));
   ```
   
## 25 BEST Android Library collections blog
 * From [FreeCodeCamp](https://www.freecodecamp.org/news/25-new-android-libraries-which-you-definitely-want-to-try-at-the-beginning-of-2017-45878d5408c0/)
 
## GreenDAO ORM database
 * [Documentation](http://greenrobot.org/greendao/documentation/) and [Best Practices](http://greenrobot.org/android/benchmarking-on-android/)
 * Updating Model Classes(Entity classes) from [stackoverflow from Pedro Okawa's Answer](https://stackoverflow.com/a/30334668/6021740) particularly [this answer](https://stackoverflow.com/a/38984100/6021740) with [additional instructions](https://github.com/cyrilpillai/GreenDao-Migrator) and library on [github for updating](https://github.com/yuweiguocn/GreenDaoUpgradeHelper) or it you're using Mindorks starter follow this instration [STEP 7](https://blog.mindorks.com/powerful-android-orm-greendao-3-tutorial) email [group on GreenDAO](https://groups.google.com/forum/#!forum/greendao) if you want to see implementation check [my blog about it](https://medium.com/@kidusmamuye/migration-with-greendao-android-8f940b5ef58d)
 
 ## SnakBar Library
  * a very customized and elegant snackbar on [github](https://github.com/TonnyL/Light) from [Tonny](https://github.com/TonnyL)
 
