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
 
## PNG to SVG
 * [website](https://www.pngtosvg.com/)
 
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
 * [SimpleDateFormats](https://docs.oracle.com/javase/10/docs/api/java/text/SimpleDateFormat.html)
   
## 25 BEST Android Library collections blog
 * From [FreeCodeCamp](https://www.freecodecamp.org/news/25-new-android-libraries-which-you-definitely-want-to-try-at-the-beginning-of-2017-45878d5408c0/)
 
## GreenDAO ORM database
 * [Documentation](http://greenrobot.org/greendao/documentation/) and [Best Practices](http://greenrobot.org/android/benchmarking-on-android/)
 * Updating Model Classes(Entity classes) from [stackoverflow from Pedro Okawa's Answer](https://stackoverflow.com/a/30334668/6021740) particularly [this answer](https://stackoverflow.com/a/38984100/6021740) with [additional instructions](https://github.com/cyrilpillai/GreenDao-Migrator) and library on [github for updating](https://github.com/yuweiguocn/GreenDaoUpgradeHelper) or it you're using Mindorks starter follow this instration [STEP 7](https://blog.mindorks.com/powerful-android-orm-greendao-3-tutorial) email [group on GreenDAO](https://groups.google.com/forum/#!forum/greendao) if you want to see implementation check [my blog about it](https://medium.com/@kidusmamuye/migration-with-greendao-android-8f940b5ef58d)
 
 ## SnakBar Library
  * a very customized and elegant snackbar on [github](https://github.com/TonnyL/Light) from [Tonny](https://github.com/TonnyL)

## int vs Integer -> most basic question
 * [wapper vs primitive classes](http://mindprod.com/jgloss/intvsinteger.html)
 
## Fragment Back stack
 * [github](https://github.com/ChintanRathod/Fragment-Back-Stack) from [Chintan Rathod](https://github.com/ChintanRathod) ; if you're checking by cloning his project like I did, you're going to face gradle problem becuase of his project being done on eclipse. So check [this out](https://developer.android.com/studio/intro/migrate.html#import_eclipse_projects_to_android_studio) this is how I fixed it.
 
 
## Handling Networking
 * Retrofit - from [Square Open Source](https://square.github.io/)- [official documentation](https://square.github.io/retrofit/) and best tutorials from [Future studio](https://futurestud.io/tutorials/retrofit-getting-started-and-android-client)
 * handling custome error types on response: [woolha](https://www.woolha.com/tutorials/android-retrofit-2-custom-error-response-handling) - has a neat way of handling this issue
 * [FAST ANDROID NETWORKING](https://github.com/amitshekhariitbhu/Fast-Android-Networking) from [AMIT SHEKHAR](https://github.com/amitshekhariitbhu) co-founder of [Mindorks](https://mindorks.com)
 * [Volley](https://developer.android.com/training/volley) from google. their [Github](https://github.com/google/volley)

## TIPS ON UI/UX DESIGN - BY [Nick Babich](https://www.smashingmagazine.com/author/nickbabich/) 
 * [A Comprehensive Guide To Mobile App Design](https://www.smashingmagazine.com/2018/02/comprehensive-guide-to-mobile-app-design/)
 * [10 Do’s and Don’ts of Mobile UX Design](https://theblog.adobe.com/10-dos-donts-mobile-ux-design/)
 * [You Are Not the User: The False-Consensus Effect](https://www.nngroup.com/articles/false-consensus/) - by [Raluca Budiu](https://www.nngroup.com/articles/author/raluca-budiu/)
 * [Minimalistic Design With Large Impact: Functional Minimalism For Web Design](https://www.smashingmagazine.com/2017/10/functional-minimal-web-design/)
 * [The 11 Screens You’ll Find in Many of the Most Successful Mobile Apps](https://theblog.adobe.com/11-screens-youll-find-many-successful-mobile-apps/)
 * [Emotionally Intelligent Design Is The Future of Mobile UX](https://theblog.adobe.com/emotionally-intelligent-design-future-mobile-ux/)

## File Browser Intents & Providers
 * [a blog by Uncle Code Monkey](http://www.blackmoonit.com/android/filebrowser/intents/)
 * [File manager on github](https://github.com/openintents/filemanager) and their [website](https://f-droid.org/packages/org.openintents.filemanager/)
 
## Excel sheet Generator
 * [POI library](https://www.javatpoint.com/apache-poi-merging-cells) and [blog](https://howtodoinjava.com/library/readingwriting-excel-files-in-java-poi-tutorial/) and on [read/write blog](https://www.viralpatel.net/java-read-write-excel-file-apache-poi/)
 
## Sharing file with Intent
 * [Sharing Content with Intents - blog - CODEPATH](https://guides.codepath.com/android/Sharing-Content-with-Intents) for file sharing NOTE [here](https://guides.codepath.com/android/Sharing-Content-with-Intents#sharing-files-with-api-24-or-higher)
 * [CommonsWare's blog](https://commonsware.com/blog/2017/06/27/fileprovider-libraries.html)
 * [nice question on stackoverflow regarding this topic](https://stackoverflow.com/questions/38200282/android-os-fileuriexposedexception-file-storage-emulated-0-test-txt-exposed)
 * [another blog from Author: nuuneoi ](https://inthecheesefactory.com/blog/how-to-share-access-to-file-with-fileprovider-on-android-nougat/en)
## RecyclerView
 * [from Javier González Cabezas - FullRecyclerView](https://github.com/thedeveloperworldisyours/FullRecyclerView)
 
## CodeStarter
 * [Android Starters](https://androidstarters.com/) and on their [github](https://github.com/androidstarters/androidstarters.com)
## RxJava
 * [Exploring RxJava in Android — Introduction](https://proandroiddev.com/exploring-rxjava-in-android-e52ed7ef32e2) - nice blog on medium by Anitaa Murthy
