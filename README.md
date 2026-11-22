# हाज़िरी रजिस्टर - APK kaise banaye

## Tareeka 1: GitHub se (bina Android Studio ke, free)
1. github.com par free account banao -> New repository (naam: HazriRegister).
2. Is poore folder ki saari files (".github" folder samet) us repo mein upload karo.
3. Repo mein "Actions" tab kholo -> "Build APK" khud chalega (2-4 minute).
4. Complete hone par us run par click karo -> neeche "Artifacts" mein
   "HazriRegister-apk" download karo -> zip khol ke `app-debug.apk` milegi.
5. APK ko WhatsApp / Drive se kisi ko bhi bhejo. Phone mein tap karke install karo
   (Settings mein "Install unknown apps" allow karna padega).

## Tareeka 2: Android Studio se
Folder ko Android Studio mein kholo -> Build -> Build APK(s).

## Dhyan do
- Data har phone ke andar hi save hota hai (localStorage). Do phone ka data alag rahega.
- App uninstall karne par data chala jaata hai.
- Code badalna ho to `app/src/main/assets/index.html` edit karo, phir dobara build karo.
