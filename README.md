# kotlin Reference Links

- Get started:
  - Fundamentals: https://www.tutorialkart.com/kotlin-tutorial/
  - Videos: https://www.youtube.com/watch?v=iC8LRjd67Ds&list=RDCMUC0FPjuZLQ16UpvLtbs6LYpg&start_radio=1

- Visibility Modifiers:https://www.journaldev.com/20235/kotlin-visibility-modifiers-public-protected-internal-private
  
- var / val / const
  - https://stackoverflow.com/questions/37595936/what-is-the-difference-between-const-and-val
  - https://blog.mindorks.com/what-is-the-difference-between-const-and-val

- lateinit vs lazy
  - lateinit can only be used with a var property whereas lazy will always be used with val property. 
  - A lateinit property can be reinitialised again and again as per the use whereas the lazy property can only be initialised once.
  - https://blog.mindorks.com/learn-kotlin-lateinit-vs-lazy
  
- Scop Function [let, run, also, apply]
  - Overview: https://play.kotlinlang.org/byExample/06_scope_functions/01_let
  - Video: https://www.youtube.com/watch?v=AiFBEH54Xpw  

- Companion object: https://blog.mindorks.com/companion-object-in-kotlin  
- Extention function: https://antonioleiva.com/extension-functions-kotlin/
- Higher-Order Functions: https://play.kotlinlang.org/byExample/04_functional/01_Higher-Order%20Functions
- Inline Function: https://www.javatpoint.com/kotlin-inline-function

- Special Class: [Data,Enum,Sealed,Object]
  - https://play.kotlinlang.org/byExample/03_special_classes/01_Data%20classes
  - Example - API Response: https://medium.com/@bhavnathacker14/dealing-with-multiple-apis-via-retrofit-learn-how-to-use-sealed-classes-effectively-eee01b2bff45
  
- Collection
  - Overview: 
    - https://www.javatpoint.com/kotlin-collections
    - https://play.kotlinlang.org/byExample/05_Collections/01_List
  - Videos:
    - https://www.youtube.com/watch?v=XeRt2ZZ-jkA
    - https://www.youtube.com/watch?v=aFXfZH4RRfQ
    - https://www.youtube.com/watch?v=Je_YXshSFmY
    - https://www.youtube.com/watch?v=73RTzuFWqm4
  
 - Volatile	https://steemit.com/volatile/@sharpchain/how-to-use-volatile-in-kotlin
  
## Kotlin Coroutine
  - Fundamentals: https://www.geeksforgeeks.org/kotlin-coroutines-on-android/
  - Videos: https://www.youtube.com/watch?v=eUfSmd-ntUI&list=PLk7v1Z2rk4hj6PpRhOLPNuNorZk2zaSF5
   
- Suspend Function: https://www.geeksforgeeks.org/suspend-function-in-kotlin-coroutines/
   
- runBlocking: https://www.geeksforgeeks.org/runblocking-in-kotlin-coroutines-with-example/?ref=rp
   
- Dispatchers: https://www.geeksforgeeks.org/dispatchers-in-kotlin-coroutines/?ref=rp
   
- Launch vs Async: 
     - https://www.geeksforgeeks.org/launch-vs-async-in-kotlin-coroutines/?ref=rp
     - Video: https://www.youtube.com/watch?v=nC30UiDv8Xc

- withcontext vs async-await: https://blog.mindorks.com/kotlin-withcontext-vs-async-await
     
## Kotlin Fow API
- OverView: https://blog.mindorks.com/what-is-flow-in-kotlin-and-how-to-use-it-in-android-project
- PlayList: 
  - https://www.youtube.com/playlist?list=PL4EnMCc01RC0UA33dTubhauq_ksTFHm4X
  - https://www.youtube.com/watch?v=kOpRhtbhftI&list=PLRKyZvuMYSIPJ84lXQSHMn8P-0J8jW5YT
  - https://www.youtube.com/watch?v=UOxFGp-rgBc&list=PLdFC34ba_zA46uv1QteVWur1nHs6iTSIJ
- StateFlow vs Flow vs SharedFlow vs LiveData: https://www.youtube.com/watch?v=6Jc6-INantQ

## Examples:
  - MVVM + Coroutines + Retrofit: 
    - https://www.javacodemonk.com/kotlin-coroutines-with-retrofit-and-livedata-790f6376
    - https://blog.mindorks.com/using-retrofit-with-kotlin-coroutines-in-android
    - https://github.com/unaisulhadi/MVVM-Retrofit-Coroutine
        
  - MVVM + Room + Coroutines + DataBinding: https://github.com/AnushkaMadusanka/RoomDemo

- MVVM + DaggerHilt + Retrofit + Coroutines + Flow
    - Video : https://www.youtube.com/watch?v=5OrK81ZRoNY
    - Code: https://github.com/nameisjayant/MVVM-DaggerHilt-Retrofit-Sealed-Class-StateFlow-Coroutines-In-Android

 - MVVM + DaggerHilt + Retrofit + Coroutines + Flow + Room
    - https://github.com/nameisjayant/Dagger-hilt-with-RoomDatabase-and-Retrofit-in-Android     
  
 - Other Operation [Series Network Calls, Parallel Network Calls etc]
    - https://github.com/MindorksOpenSource/Kotlin-Coroutines-Android-Examples


# Interview Questions:

  - Questions: https://www.journaldev.com/20567/kotlin-interview-questions
  
  - Singleton Class: https://blog.mindorks.com/how-to-create-a-singleton-class-in-kotlin
  
  - Null safety: https://www.geeksforgeeks.org/kotlin-null-safety/
  
  - Elvis Operator(?:) https://www.geeksforgeeks.org/kotlin-elvis-operator/
  
  - Sealed classes: https://www.journaldev.com/18719/kotlin-sealed-class
  
  - Map vs Flatmap kotlin: https://blog.mindorks.com/flatmap-vs-map-in-kotlin

  - @JVMStatic and @JVMField : 
     - https://blog.mindorks.com/jvmstatic-jvmoverloads-and-jvmfield-in-kotlin
     - https://www.geeksforgeeks.org/jvmstatic-jvmoverloads-and-jvmfield-in-kotlin/
  
  - What is Lambda: Function is also known as anonymous function because it has no name. Parameters are in the left side of the arrow and actual code is on the right side of the arrow.
  
  - How to call extension functions from XML: https://stackoverflow.com/questions/49898669/kotlin-extension-functions-databinding

- Kotlin Flow vs LiveData : https://stackoverflow.com/questions/58773453/kotlin-flow-vs-android-livedata
  - Example: https://proandroiddev.com/flow-livedata-what-are-they-best-use-case-lets-build-a-login-system-39315510666d




