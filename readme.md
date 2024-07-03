# Tek Harfli GPT (Single-Letter GPT)

Bu proje, Türkçe harflerle tek harfli metin üreten bir GPT (Generative Pre-trained Transformer) modelini içerir. GPT modeli, eğitim aşamasında verilen tek harfli girişlere dayanarak devamındaki harfleri tahmin eder ve bu şekilde yeni metinler oluşturur.

## Özellikler

- **Model:** GPT-2 mimarisi kullanılarak oluşturulmuştur.
- **Veri:** Eğitim ve doğrulama için özel olarak oluşturulmuş Türkçe harf veri kümesi kullanılmıştır.
- **Eğitim:** Model, belirtilen parametrelerle eğitilmiş ve örneğin eğitim ve doğrulama işlemleri görülebilir.
- **Kullanım:** Model, tek harfli girişlerle yeni metinler üretmek için kullanılabilir.

## Kullanım

Proje dosyalarını yükledikten sonra, aşağıdaki adımları izleyerek modeli kullanabilirsiniz:

1. **Çalıştırma:** `calistir()` fonksiyonunu çağırarak modelin bir örneğini çalıştırabilirsiniz.
2. **Eğitim:** Eğitim ve doğrulama işlemleri için uygun veri dosyalarını kullanabilirsiniz (`egitim_jetonlari.bin`, `dogrulama_jetonlari.bin`).
3. **Model Yükleme:** Eğitilmiş model dosyalarını (`gpt2_*.bin`) yükleyerek veya yeni modeller oluşturarak denemeler yapabilirsiniz.

## Örnek

Aşağıda, modelin bir tek harfli girişle nasıl metin ürettiğini gösteren bir örnek bulunmaktadır:

```

---

Example input: a
Generated output: alışı

---

```

## Katkıda Bulunma

Bu proje açık kaynaklıdır ve katkıda bulunmaktan memnuniyet duyarız. Her türlü geri bildirimi ve katkıyı bekliyoruz!

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına göz atabilirsiniz.

```

```
