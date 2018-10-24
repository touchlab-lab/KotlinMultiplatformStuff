# KotlinMultiplatformStuff

## Libraries

### [Ktor](https://github.com/ktorio/ktor)

Client/Server networking

### [Coroutines](https://github.com/Kotlin/kotlinx.coroutines)

Support library for coroutines. Native are single-threaded only, so kind of a
waiting situation.

### [SqlDelight](https://github.com/square/sqldelight/)

Multiplatform SQLite model facilitation library. DIY iOS support available.
Official coming soon.

### [Knarch.db](https://github.com/touchlab/knarch.db)

SQLite access library with Android-like structure and interface. Pair with
SqlDelight for shared mobile sql [See Droidcon app](https://github.com/touchlab/DroidconKotlin/)

### [Multiplatform Settings](https://github.com/russhwolf/multiplatform-settings)

Multiplatform access to "Shared Preferences" and "NSUserDefaults". Single value
data storage for mobile.

### [Stately](https://github.com/touchlab/Stately)

State and threading facilitation library for Multiplatform. Not public yet...

### [Atomic-fu](https://github.com/Kotlin/kotlinx.atomicfu)

Atomic helper. Native in progress.

### [Timber](https://github.com/JakeWharton/timber)

Multithreaded logging. In progress.

### [kotlinx.io](https://github.com/Kotlin/kotlinx-io)

Kotlin multiplatform I/O library

### [OKIO2](https://github.com/square/okio)

Modern I/O library. Multiplatform in progress.

## Videos

### KotlinConf

**Multiplatform and Native specific**

#### [Conference Opening Keynote by Andrey Breslav](https://www.youtube.com/watch?v=PsaFVLr8t4E)

Important notes about native and discussion of the "Saner Concurrency" future.

#### [Kotlin/Native Concurrency Model by Nikolay Igotti](https://www.youtube.com/watch?v=nw6YTfEyfO0)

About state and threading in Kotlin/Native. You must understand this stuff to be productive
with Native.

#### [A Multiplatform Delight by Jake Wharton and Alec Strong](https://www.youtube.com/watch?v=WkIry790PHI)

SqlDelight, multiplatform.

#### [iOS Architecture with Multiplatform by Kevin Galligan](https://www.youtube.com/watch?v=Dul17VSiejo)

My video. About the current state of the ecosystem.

#### [Making Noise with Kotlin Native by Josh Skeen](https://www.youtube.com/watch?v=vc04QKnryKs)

Life with Kotlin/Native

#### [Live Coding Kotlin/Native Snake by Dmitry Kandalov](https://www.youtube.com/watch?v=U-gdJQeOVAk)

More Kotlin/Native samples.

#### [Effective Multiplatform Kotlin Development by Marcin Moskala](https://www.youtube.com/watch?v=UyTBXEZ983g)

I think this is a bit more about JVM+JS. Library list needs a refresh. Good talk, though.

**General but useful**

#### [Kotlin Coroutines in Practice by Roman Elizarov](https://www.youtube.com/watch?v=a3agLJQ6vt8)

We're waiting on multithreaded coroutines, but this kind of stuff will be super important
once that's available.

#### [Writing Your First Kotlin Compiler Plugin by Kevin Most](https://www.youtube.com/watch?v=w-GMlaziIyo)

API isn't public yet, but this will be very important for library dev.

#### [Dissecting the stdlib by Huyen Tue Dao](https://www.youtube.com/watch?v=Fzt_9I733Yg)

Understanding stdlib, without JVM, will be pretty important.

## Sample Apps

### [Kotlinconf App](https://github.com/JetBrains/kotlinconf-app)

From JetBrains

### [DroidconKotlin](https://github.com/touchlab/DroidconKotlin/)

From Touchlab
