# YOLOv8 ile COVID-19 Görüntü Sınıflandırma

Bu proje, YOLOv8 kullanarak COVID-19 görüntü sınıflandırma sistemi uygulamaktadır. Model, göğüs röntgeni görüntülerini üç kategoride sınıflandırır: COVID-19, Normal ve Viral Zatürre.

[Click here for English README](README.md)

## Veri Seti

Veri seti, göğüs röntgeni görüntülerini üç kategoride toplamaktadır:
- COVID-19
- Normal
- Viral Zatürre

Veri seti dağılımı:
- Eğitim: 12.121 görüntü
- Doğrulama: 1.514 görüntü
- Test: 1.518 görüntü

## Proje Yapısı

```
├── data/
│   ├── covid_classification/
│   │   ├── train/
│   │   ├── val/
│   │   └── test/
│   └── covid_dataset/
├── runs/
│   └── classify/
└── requirements.txt
```

## Gereksinimler

- Python 3.8+
- YOLOv8
- Diğer bağımlılıklar requirements.txt dosyasında listelenmiştir

## Kurulum

1. Depoyu klonlayın:
```bash
git clone https://github.com/Semihkulekcioglu/covid19_xray_classification_yolov8.git
cd covid19_xray_classification_yolov8
```

2. Bağımlılıkları yükleyin:
```bash
pip install -r requirements.txt
```

## Kullanım

Proje aşağıdaki betikleri içerir:
- Veri hazırlama: `find_images.py`
- Veri seti bölme: `split.py`
- YOLOv8 kullanarak model eğitimi ve değerlendirme

## Sonuçlar

Model performans metrikleri ve görselleştirmeler `runs/classify/yolov8_covid_classification/` dizininde bulunabilir.

## Lisans

Bu proje açık kaynaklıdır ve MIT Lisansı altında kullanıma sunulmuştur.
