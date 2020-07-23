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
 * Very Common but time taking to find the bug you might face during android N print from [stackoverflow](https://stackoverflow.com/a/43775680/6021740) and [Chinese blog](https://www.vvzixun.com/index.php/code/2361e7465889d765dbbe14c4b082585f)

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
 * [Apache POI Documentation - Quick Guide](https://poi.apache.org/components/spreadsheet/quick-guide.html)
 
## Sharing file with Intent
 * [Sharing Content with Intents - blog - CODEPATH](https://guides.codepath.com/android/Sharing-Content-with-Intents) for file sharing NOTE [here](https://guides.codepath.com/android/Sharing-Content-with-Intents#sharing-files-with-api-24-or-higher)
 * [CommonsWare's blog](https://commonsware.com/blog/2017/06/27/fileprovider-libraries.html)
 * [nice question on stackoverflow regarding this topic](https://stackoverflow.com/questions/38200282/android-os-fileuriexposedexception-file-storage-emulated-0-test-txt-exposed)
 * [another blog from Author: nuuneoi ](https://inthecheesefactory.com/blog/how-to-share-access-to-file-with-fileprovider-on-android-nougat/en)
## RecyclerView
 * [from Javier González Cabezas - FullRecyclerView](https://github.com/thedeveloperworldisyours/FullRecyclerView)
 * Fast-scrolling [github](https://github.com/danoz73/RecyclerViewFastScroller) and [stackoverflow](https://stackoverflow.com/questions/38507825/android-alphabetical-fast-scrollview-in-recyclerview-with-collapsing-toolbar/39295074) and a [blog](https://blog.stylingandroid.com/recyclerview-fastscroll-part-2/#comment-67201)
 
## CodeStarter
 * [Android Starters](https://androidstarters.com/) and on their [github](https://github.com/androidstarters/androidstarters.com)
## RxJava
 * [Exploring RxJava in Android — Introduction](https://proandroiddev.com/exploring-rxjava-in-android-e52ed7ef32e2) - nice blog on medium by Anitaa Murthy
 * [RxJava, RxAndroid Complete Beginner Course](https://www.androidhive.info/RxJava/tutorials/) by Ravi Tamada
 * RxJava Centralized Error handling in network [RxJava github Doc](https://github.com/ReactiveX/RxJava/wiki/Error-Handling-Operators#doonerror-example) , [stackoverflow best answer](https://stackoverflow.com/a/26201962/6021740) and [the best blog](https://androidwave.com/retrofit-globally-error-handling/) here is another [blog on medium](https://medium.com/mindorks/rxjava2-and-retrofit2-error-handling-on-a-single-place-8daf720d42d6)
 
 Snippet of code from the first best blog. 
  ```java
   public void handleApiError(Throwable error) {
        if (error instanceof HttpException) {
            switch (((HttpException) error).code()) {
                case HttpsURLConnection.HTTP_UNAUTHORIZED:
                    mView.onError("Unauthorised User ");
                    break;
                case HttpsURLConnection.HTTP_FORBIDDEN:
                    mView.onError("Forbidden");
                    break;
                case HttpsURLConnection.HTTP_INTERNAL_ERROR:
                    mView.onError("Internal Server Error");
                    break;
                case HttpsURLConnection.HTTP_BAD_REQUEST:
                    mView.onError("Bad Request");
                    break;
                case API_STATUS_CODE_LOCAL_ERROR:
                    mView.onError("No Internet Connection");
                    break;
                default:
                    mView.onError(error.getLocalizedMessage());
            }
        } else if (error instanceof WrapperError) {
            mView.onError(error.getMessage());
        } else if (error instanceof JsonSyntaxException) {
            mView.onError("Something Went Wrong API is not responding properly!");
        } else {
            mView.onError(error.getMessage());
        }
    }
   ```
 
 
## Language change 
`* [1st best blog](https://proandroiddev.com/change-language-programmatically-at-runtime-on-android-5e6bc15c758) with [github](https://github.com/YarikSOffice/LanguageTest) and [2nd best blog](https://fevziomurtekin.github.io/2018-10-21-how-to-change-app-language/) and finally [best stackoverflow answer by ](https://stackoverflow.com/questions/4985805/set-locale-programmatically)[Ricardo](https://stackoverflow.com/users/4266957/ricardo)

## Network security policy on the Latest API with http and https issue (Cleartext HTTP traffic not permitted)
 * [stackoverflow](https://stackoverflow.com/questions/45940861/android-8-cleartext-http-traffic-not-permitted) and a blog on [Android M and the war on cleartext traffic](https://koz.io/android-m-and-the-war-on-cleartext-traffic/) with [google code-lab](https://codelabs.developers.google.com/codelabs/android-network-security-config/index.html#0)
 
 
## Android - TESTING
 * [Android Documentation](https://developer.android.com/training/testing)
 * [Tutorialspoint](https://www.tutorialspoint.com/android/android_testing.htm)
 * [techbeacon](https://https://www.tutorialspoint.com/android/android_testing.htmhttps://www.tutorialspoint.com/android/android_testing.htm.com/app-dev-testing/android-developers-guide-mobile-testing-tools)
 * [Vogella](vogella.com/tutorials/AndroidTesting/article.html)
 * [guru99](https://www.guru99.com/why-android-testing.html)
 
## Dynamic Form Handling 
 * [Litho](https://fblitho.com/)
 * stackoverflow
   - [Dynamic Form Builder In Android](https://stackoverflow.com/questions/28984078/dynamic-form-builder-in-android)
   - [Solution to build dynamic forms with Android](https://stackoverflow.com/questions/45061731/solution-to-build-dynamic-forms-with-android)
   - [Approach for rendering Dynamic Forms on Android?](https://stackoverflow.com/questions/43237904/approach-for-rendering-dynamic-forms-on-android)
 * github links:
   - [JASONETTE-Android](https://github.com/Jasonette/JASONETTE-Android) with [website](http://jasonette.com/) and [docs](http://docs.jasonette.com/)
   - [json2view](https://github.com/Avocarrot/json2view)
   - [SurveyKit](https://github.com/quickbirdstudios/SurveyKit?utm_source=android-arsenal.com&utm_medium=referral&utm_campaign=7910)
   - [FormSimpleIGB](https://github.com/LordSaac/FormSimpleIGB?utm_source=android-arsenal.com&utm_medium=referral&utm_campaign=7428)
   - [EasyForm](https://github.com/emmasuzuki/EasyForm?utm_source=android-arsenal.com&utm_medium=referral&utm_campaign=3474)
   - [NexusDialog](https://github.com/dkharrat/NexusDialog?utm_source=android-arsenal.com&utm_medium=referral&utm_campaign=1947)
   - [NexusData](https://github.com/dkharrat/NexusData)
   - [IBM Blog](https://developer.ibm.com/technologies/mobile/tutorials/x-andddyntut/)
   - [a blog by veskoiliev ](https://www.veskoiliev.com/how-to-handle-dynamic-json-response-with-retrofit/)
   - [Handling dynamic key for JSON response](https://riptutorial.com/android/example/15273/handling-dynamic-key-for-json-response)
 
https://codinginflow.com/

## Collapsing Toolbar
 - [Best blog on ScrollFlags](https://medium.com/martinomburajr/android-design-collapsing-toolbar-scrollflags-e1d8a05dcb02)
 - [Mastering the Coordinator Layout - Blog](http://saulmm.github.io/mastering-coordinator)
 
## Bottom Navigation 
 - [UX Design for Mobile: Bottom Navigation](http://babich.biz/perfect-bottom-navigation-for-mobile-app/)
 
## Offline - First Architecture
 - [Hasura - blog](https://hasura.io/blog/design-guide-to-offline-first-apps/)
 - [CouchDB - Conflic Resolution](https://guide.couchdb.org/draft/conflicts.html)
 - [Dzone - conflict resolution - blog](https://dzone.com/articles/handling-write-conflicts-server-side-in-offline-en)
 - [Offline-first application architecture](https://codete.com/blog/offline-first-application-architecture/)
 - [PouchDB & Apache CouchDB™ part 1 ](https://medium.com/codait/making-your-app-awesome-when-the-network-isnt-part-1-3ed530c2523)
 - [PouchDB & Apache CouchDB™ part 2 ](https://medium.com/codait/making-your-app-awesome-when-the-network-isnt-part-2-669ee36e2f81)
 - [Access Data Offline - Firebase](https://firebase.google.com/docs/firestore/manage-data/enable-offline#configure_offline_persistence)
 - [Offline First Mobile Apps Pt 1: The Blueprint](https://medium.com/@jeremyrempel/offline-first-applications-pt-1-the-blueprint-9f518aa374dd)
 - [Offline First Resources](https://medium.com/offline-camp/offline-first-resources-2acc5836e9d4)
 - [How to Easily Build Syncable Offline-First Apps with Vuejs and PouchDB](https://scotch.io/@timtech4u/how-to-easily-build-syncable-offline-first-apps-with-vuejs-and-pouchdb)
 - [Designing Offline-First Web Apps](https://alistapart.com/article/offline-first/)
 - [Main site](http://offlinefirst.org/)
 - [How to Design Offline-first Approach in a Mobile App](https://www.netguru.com/blog/how-to-design-offline-first-approach-in-mobile-app)
 - [Offline-first web and mobile apps: Top frameworks and components](https://techbeacon.com/app-dev-testing/offline-first-web-mobile-apps-top-frameworks-components)
 
## ProGuard
 - [Android's Built-in ProGuard Rules: The Missing Guide](https://www.zacsweers.dev/android-proguard-rules/)
 - [GuardSquare](https://www.guardsquare.com/en/products/proguard/manual/introduction)
 
## Chrome Custom Tab
 - [JournalDEV](https://www.journaldev.com/21723/android-chrome-custom-tabs)
 - [Mindorks](https://blog.mindorks.com/android-browser-lets-launch-chrome-custom-tabs-with-kotlin)
 - [Youtube](https://www.youtube.com/watch?v=QOxIdbNwpx0)
 
 
## Change file to base64 encoding before uploading
 - [How to convert attach file to base64 in Android? - codeplayon](http://www.codeplayon.com/2020/05/how-to-convert-attach-file-to-base64-in-android/#:~:text=How%20to%20convert%20a%20file%20to%20Base64%3F&text=Complete%20code%20for%20Converting%20File,you%20can%20convert%20into%20base64.)
