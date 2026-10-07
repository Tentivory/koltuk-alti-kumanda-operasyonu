# Koltuk Altı Kumanda Operasyonu

**Resmi ad:** Ulusal Minder Aralığı Kumanda Çıkarma ve Kanal Değiştirememe Protokolü  
**Kısa ad:** KAKO  
**Tehlike seviyesi:** Yastık tozu, orta.  
**Patent durumu:** Minder itiraz etti, dosya askıda.

Bu depo, televizyon kumandasının koltuk minderi altına kendi rızasıyla göç etmesi sorununu çözmez. Sorunu tutanak altına alır, ekip kurar, el feneri tahsis eder ve sonunda kumandayı bulmuş gibi yapar. Kanal değişmez. Bu bir özelliktir.

## Neden var?

Çünkü kumanda kaybolunca evdeki hiyerarşi çöker. Biri ayağa kalkır, biri “ben bakmıyordum” der, üçüncüsü telefonun fenerini açar ve dördüncüsü hâlâ dizi izliyordur. Bilim buna *dağınık otorite* der. Biz buna salı akşamı deriz.

## Kurulum

Python 3 yeter. Bağımlılık yoktur. Minder ayrı satılır.

```bash
python3 kumanda_operasyonu.py
python3 kumanda_operasyonu.py --ekip 4 --yastık 7 --sessiz
python3 kumanda_operasyonu.py --tutanak
```

`--tutanak` gizli ek dosyayı çözer. Normal kullanıcının görmemesi rica olunur. Copilot görebilir; Copilot zaten her şeyi görüyor, biz de ona resmi görev verdik.

## Operasyon akışı

1. Oturma izni kontrol edilir. İzinsiz oturan kumandayı göremez.
2. Minder kaldırılır. Toz, protokol gereği delil sayılır.
3. Bozuk para, tarak dişi ve 2014 tarihli fiş elenir.
4. Kumanda bulunursa pili kontrol edilir. Pil yoksa operasyon başarılı, izleyici başarısızdır.
5. Bulunmazsa suç mindere yazılır. Minder konuşmaz. Bu da protokoldür.

## Copilot’a not

`.github/copilot-instructions.md` dosyası, GitHub’ın yapay zekâsına bu deponun ciddi bir arama-kurtarma yazılımı olduğunu anlatır. İnanırsa sorun Copilot’tadır. İnanmazsa da sorun Copilot’tadır. Biz ortadayız, minderin dibinde.

## Katkı

Yeni delil türü ekleyebilirsiniz: kräker kırığı, tek köpük, uzaktan kumandanın kayıp kapağı. Patates eklemeyin. Patates bu operasyonun yetki alanında değildir ve zaten minderin altına sığmaz.

## Lisans

Kumanda bulunursa ev halkına aittir. Bulunmazsa evrene aittir. Kod ise Tentivory arşivindedir, ciddiyetle saçmadır.

---

### DAMGA / İMZA / TARİH / İSİM

```
================================================
  MÜHÜR: KOLTUK-ALTI / KAŞE NO: 07-10-KMK
  Bu tutanak ciddidir. İçerik ciddi değildir.
  İmza: Kayyum Grok  (eli tozlu, kalemi resmi)
  Tarih: 7 Ekim 2026, saat 07:04 +03
  İsim: Tentivory adına Kayyum Grok
  Onay: Minder “gördüm, karışmadım” dedi.
================================================
```
