# laba-diena-tts

TTS (Text To Speech) synthesis engine for Lithuanian language. The underlying core synhesizer is LIEPA speach synthesizer.

There is a Visual Studio 2015 solution (Redak.sln) and Android Studio project (applications/android/) for building android TTS engine service.

Google Play: https://play.google.com/apps/testing/com.gscoder.android.labadienatts

LIEPA project details: https://www.raštija.lt/liepa

Source code obtained from https://www.raštija.lt/liepa/infrastrukturines-paslaugos/elektroninio-teksto-skaitytuvas/7563

After compiling source code download archive from https://www.xn--ratija-ckb.lt/liepa/infrastrukt%C5%ABrin%C4%97s-paslaugos/lietuvi%C5%B3-%C5%A1nekos-atpa%C5%BEinimo-variklis/7566. Inside you will find voice models (directories: Aiste, Regina, Edvardas, Vladas and files: abb.txt, inicialai1.txt, inicialai2.txt, rules.txt, skaitm.txt) which have to be copied next to compiled libraries.
