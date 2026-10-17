# 🏎️ 1.5 Adana Formula — Otonom Sürüş Sistemleri Departmanı

> *"Sensör verisini algıya, algıyı karara, kararı ise pistte milisaniyeler içinde hassas ve güvenli bir sürüşe dönüştürüyoruz."*

---

### 💡 Biz Kimiz?
Biz **1.5 Adana Formula** ekibinin otonom yarış aracı ve robotik yazılım mimarisinden sorumlu departmanıyız (**birbucukformula-Autonomous**). Formula Student Driverless (FSD) standartlarına uygun olarak, sürücüsüz bir yarış aracının ihtiyaç duyduğu tüm otonom boru hattını (pipeline) sıfırdan tasarlıyor, simülasyon ortamında modelliyor ve gerçek pist koşullarında hayata geçiriyoruz.

Sadece algoritma geliştirmiyoruz; LiDAR, kamera, GNSS/RTK ve IMU gibi sensörlerden gelen gerçek zamanlı verileri işleyerek aracın pist sınırlarını (koni) algılamasını, santimetre hassasiyetinde harita üzerinde konumlanmasını, en uygun yarış çizgisini hesaplamasını ve eyleyicilere milisaniyelik hassasiyetle komut vermesini sağlıyoruz.

---

### 🛠️ Otonom Sürüş Mimarimiz & Teknoloji Yığını

Yazılım mimarimiz, modüler ve genişletilebilir ROS 2 tabanlı gerçek zamanlı bir boru hattı üzerine kuruludur:

| Disiplin | Odak Noktası ve Teknolojiler |
| :--- | :--- |
| **Algılama (Perception)** | YOLO (Formula Student Koni Tespiti), Kamera & LiDAR Füzyonu, Şerit ve Zemin Segmentasyonu |
| **Konumlandırma & SLAM (Localization)** | EKF (Extended Kalman Filter), LiDAR Odometri, GNSS/RTK, IMU Sensör Füzyonu, Haritalama |
| **Yol Planlama (Path Planning)** | Global Rota / Yarış Çizgisi (A*, Dijkstra), Dinamik Engelden Kaçma, Yerel Yörünge Üretimi |
| **Hareket Kontrolü (Motion Control)** | Pure Pursuit, Stanley Kontrolcü, PID, MPC (Model Predictive Control) |
| **Robotik Altyapı & Simülasyon** | ROS 2 Humble Hawksbill, RViz2, Gazebo, Foxglove Studio, Turtlesim |
| **Diller & Kütüphaneler** | Python 3.10+, C++17/20, PyTorch, OpenCV, NumPy, SciPy |

---

### 📂 Proje ve Depo Yapımız

Organizasyonumuzdaki çalışmalar şu ana başlıklar altında yürütülmektedir:

1. **🚗 [otonom-26-27](https://github.com/birbucukformula-Autonomous/otonom-26-27):** 
   * **`src/`:** Çekirdek otonom yazılım boru hattı (algılama, konumlandırma, planlama, hareket kontrolü ve ROS 2 düğümleri).
   * **`training-program/`:** Yeni üyeler için hazırlanan 4 aşamalı uygulamalı eğitim ve oryantasyon kampı.
2. **🧠 Yapay Zeka & Model Eğitimi:** Formula Student pistlerinde sarı, mavi ve turuncu konileri yüksek doğrulukla tespit eden derin öğrenme modelleri ve veri setleri.
3. **🌐 Simülasyon & Doğrulama:** Algoritmalarımızın fiziksel araç üzerine aktarılmadan önce test edildiği Gazebo ve 2D sanal pist simülasyonları.

---

### 🚀 Ekibe Katılım ve Oryantasyon Süreci

Otonom sürüş dünyasına ve robotik yazılımlarına adım atmak isteyen geliştiriciler için:

* **Eğitim Kampı:** Ekibe yeni katılan adaylar, doğrudan [`training-program/`](https://github.com/birbucukformula-Autonomous/otonom-26-27/tree/main/training-program) altındaki 4 aşamalı görevi (Otonom Mimari Araştırması, ROS 2 Temelleri, YOLO Koni Tespiti, Hareket Kontrolü) tamamlar.
* **Katkı (Contribution):** Görev teslimleri profesyonel Git akışı (Branch & Pull Request) ile yapılır. Mentör değerlendirmesini geçen üyeler ana otonom mimarisine (`src/`) **Contributor** ve çekirdek geliştirici olarak dahil edilir.

---

### 📈 Organizasyon Görünümü

![ROS 2](https://img.shields.io/badge/ROS_2-Humble-22314E?logo=ros)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-17%2F20-00599C?logo=c%2B%2B&logoColor=white)
![GitHub Top Languages](https://img.shields.io/github/languages/top/birbucukformula-Autonomous/otonom-26-27?color=E53935)
![Total Stars](https://img.shields.io/github/stars/birbucukformula-Autonomous/otonom-26-27?style=social)

---

🏠 **Bağlantılar:**
* 🏎️ **Otonom Deposu:** [birbucukformula-Autonomous / otonom-26-27](https://github.com/birbucukformula-Autonomous/otonom-26-27)
* 🌐 **Yazılım Portalı:** [1.5 Adana Formula Software](https://github.com/birbucukformula-Software)
