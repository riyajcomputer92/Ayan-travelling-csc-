AYAN TRAVELLING AND CSC CENTRE - Android App

এই project-এ মূল HTML file একই রাখা হয়েছে। WebView app localStorage/DOM storage চালু রাখে এবং file chooser upload সমর্থন করে। App update করলে app data clear করা হয় না।

ফোন দিয়ে APK বানানোর নিয়ম:
1. GitHub-এ নতুন repository বানান।
2. এই ZIP-এর সব file/folder repository-তে upload করুন।
3. Actions tab > Build Android APK > Run workflow চাপুন।
4. কাজ শেষ হলে Actions-এর successful run খুলে Artifacts থেকে Ayan-Travelling-APK.zip নিন।
5. ZIP খুলে app-debug.apk install করুন।

গুরুত্বপূর্ণ: পুরনো browser-এর localStorage সরাসরি নতুন Android app-এ নিজে থেকে আসবে না, কারণ app-এর storage আলাদা। তবে Google Cloud sync-এ থাকা data app খুললে একই cloud source থেকে আসতে পারে, এবং app-এর ভিতরে নতুন data normal update-এ মুছে যাবে না। App uninstall করলে Android app data মুছে যেতে পারে; তাই গুরুত্বপূর্ণ data-এর cloud sync/backup রাখুন।
