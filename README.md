# WİNDOWS KOMUTLARI

Bu projede, Windows'ta sık kullanılan 20 temel ve ileri düzey komut, işlevleri ve örnek kullanımlarıyla ele alınmıştır.

## Klasör Komutları

#### CD Komutu
Bu komut klasöre girmek için kullanılır.<br>
>Kullanım Şekli: cd  Klasör_Adı

cd belgelerim

![cd](https://github.com/user-attachments/assets/dae98637-1ea0-40ed-9eca-3a6cd3d554da)
>[!WARNING]
>Klasör adı yazarken klasörün adını hatasız yazının büyük harf küçük harf uyumuna dikkat ediniz!

#### DİR Komutu
Bu komut cmdnin konumundaki dosyanın içerisinde bulunan şeyleri listeler.<br>
>Kullanım Şekli : dir

dir

![dir](https://github.com/user-attachments/assets/c8adbd48-08ce-4c56-bc89-7c3971c79d47)


#### MKDİR Komutu
Bu komut klosör içerisinde yeni bir klasör açmak için kullanılır.<br>
>Kullanım Şekli: mkdir Klasör_Adı

mkdir windows_komutları

![mkdir](https://github.com/user-attachments/assets/3f7f00d4-7e59-4b74-8bdb-91d13ecbf8aa)

>[!TIP]
>CD ile dosyaya girerken <ins>Tab</ins> tuşu ile son kaydedilen belge adını anında yazabilirsiniz.

#### COPY Komutu
Bu komut kopyalama komutu olarak geçer bir belgeyi kopyalamaya yarar.<br>
>Kullanım Şekli : copy NUL dosyaadı

copy NUL yeni

![copy](https://github.com/user-attachments/assets/ff094d58-b310-4bf0-b7d9-1dadddb68328)
>[!NOTE]
>Belge oluşturmak için bir kod bulunmadığı için <ins>copy</ins> komudu kullanılır.

#### MOVE Komutu
Bu komut belgenin veya klasörün adını değiştirmeye yarar.<br>
>Kullanım şekli : move dosyaadı yenidosyaadı

move yeniisim isimdeğişme

![move](https://github.com/user-attachments/assets/41f88e07-8ee3-4311-9cb8-ee9d4fbc104c)

#### ECHO Komutu
Bu komut belgenin içerisine yazı yazmaya yarar.<br>
>Kullanım Şekli : echo yazı > dosyaadı

echo "merhaba dünya" > Kişiler

![echo](https://github.com/user-attachments/assets/a18c7657-021d-4cd9-b936-0a95e14306f6)
>[!TIP]
>İşlem çıktısı aşağıdaki gibidir.
>![çıktı](https://github.com/user-attachments/assets/5bd29902-525a-4f3d-bd39-baf2f5181060)

#### FİND Komutu
Bu komut belgede metin aramaya yarar.<br>
>Kullanım Şekli : find aranacakmetin dosyaadı

find "Merhaba" kişiler.txt

![find](https://github.com/user-attachments/assets/cfa2efb9-b49e-49e9-99ff-0d1fe57fa4e7)
>[!IMPORTANT]
>Burda aranacak metin bire bir aynı olmalıdır büyük küçük harfe dikkat edilmelidir.

## Sistem Komutları

#### DRİVERQUERY Komutu
Bu komut bilgisayarınızda yüklü sürücüleri listelemeye yarar.<br>
>Kullanım şekli : driverquery

driverquery

![driverquery](https://github.com/user-attachments/assets/220fdec8-19d8-49f2-9d6b-64d282262e27)

#### TASKLIST Komutu
Bu komut çalışan işlemleri listeler.<br>
>Kullanım Şekli : tasklist

tasklist

![tasklist](https://github.com/user-attachments/assets/3bb264be-89b3-4560-bafa-3a1c20a16752)

#### DATE Komutu
Bu komut bilgisayarınızın tarihini değiştirir.<br>
>Kullanım Şekli : date

date

>[!TIP]
>
>date /T
>
>Kodu ile mevcut tarihi görebilirsiniz.

![date](https://github.com/user-attachments/assets/9143eee5-7301-4326-adb2-e41b1c8e8927)
>[!IMPORTANT]
>Bu başlık altındaki komutlar yönetici yetkilerine ihtiyaç duyar.
>Bu nedenle uygulamadan önce komut istemini yönetici olarak başlatmanız gerekiyor.
>Aksi takdirde erişim engellendi hatası alacaksınız.

#### TİME Komutu
Bu komut bilgisayarınızın saatini değiştirir.<br>
>Kullanım Şekli : time

time

>[!TIP]
>
>time /T
>
>Kodu ile mevcut saati görebilirsiniz.

![time](https://github.com/user-attachments/assets/d41a7dff-887c-46c7-abf3-55a1477fc6e5)
>[!IMPORTANT]
>Bu başlık altındaki komutlar yönetici yetkilerine ihtiyaç duyar.
>Bu nedenle uygulamadan önce komut istemini yönetici olarak başlatmanız gerekiyor.
>Aksi takdirde erişim engellendi hatası alacaksınız.

#### DİSKPART Komutu
Bu komut disk yönetim merkezini açar.<br>
>Kullanım Şekli : diskpart

diskpart

![diskpart](https://github.com/user-attachments/assets/5d41869e-ce96-4f5e-969a-450c4bc15ae6)

#### LIST DISK Komutu
Bu komut bilgisayarınızdaki diskleri listeler.<br>
>Kullanım Şekli : list disk

list disk

>[!TIP]
>Bu komut disk yönetim merkezinde çalışır.

![disklist](https://github.com/user-attachments/assets/d9d55d62-f3d5-4fa7-81f8-00f993c654ee)

## CMD ile Uygulama açma

#### Notepad.exe Komutu
Bu komut notlar uygulamasını açar.<br>
>Kullanım şekli : notepad.exe

notepad.exe

![notepad exe](https://github.com/user-attachments/assets/7ceae548-5e6f-4b8d-b6ae-5d1c733c98cf)

#### Taskmgr.exe Komutu
Bu komut görev yöneticisini çalıştırır.<br>
>Kullanım Şekli : taskmgr.exe

taskmgr.exe

![taskmgr exe](https://github.com/user-attachments/assets/73b165ba-95af-4b13-87ea-7c011c3cbab0)

#### Cleanmgr.exe Komutu
Bu komut disk temizleme uygulamasını açar.<br>
>Kullanım Şekli : cleanmgr.exe

cleanmgr.exe

![cleanmgr exe](https://github.com/user-attachments/assets/e78eca73-1eef-42c5-90c1-708b24932796)

#### Devmgmt.msc Komutu
Bu komut aygıt yöneticisini açar.<br>
>Kullanım Şekli : devmgmt.msc

devmgmt.msc

![aygıt](https://github.com/user-attachments/assets/5dbff3f3-04a3-46c4-9d01-c6304e16f678)


#### Mspaint.exe Komutu
Bu komut paint uygulamasını açar.<br>
>Kullanım Şekli : mspaint.exe

mspaint.exe

![paint](https://github.com/user-attachments/assets/e12370de-1af9-4bde-b2f9-96a7c8368315)


#### Calc.exe Komutu
Bu komut hesap makinesini açar.<br>
>Kullanım Şekli : calc.exe

calc.exe

![calc](https://github.com/user-attachments/assets/83f9639d-11ce-43aa-aa5a-f507341c906e)



#### Msconfig.exe Komutu
Bu komut sistem ayarları uygulamasını açar.<br>
>Kullanım Şekli : msconfig.exe

msconfig.exe

![config](https://github.com/user-attachments/assets/0540869c-1146-4740-9cfc-398f576052a5)
