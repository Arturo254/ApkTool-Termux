# ApkTool Termux
![Picsart_23-08-01_00-06-04-281](https://github.com/Arturo254/ApkTool-Termux/assets/87346871/f561c021-ba48-4c53-8d6a-d9e16a9cd816)


Install 

```bash
git clone https://github.com/Arturo254/Apktool-Termux

cd ApkTool-Termux

dpkg -i apktool_2.3.4_all.deb
```
### APK Tool es una herramienta que permite modificar y decomplilar un archivo .apk, y compilarlo nuevamente cambiando la Verificación de firma y la keystore 
Decompile

```bash
apktool d yourapk 
```

Recompile 

```bash
apktool b yourfolder/ --output out.apk
```

Sign use apksigner

```bash
pkg install apksigner
apksigner -p yourpassword keystore yourapk newapkname
```
