# Three.js İlə 3D Grafika İnfrastrukturu

## Giriş

[Three.js](https://threejs.org/), veb səhifələr üçün 3D grafika tərtib etmək üçün istifadə edilən bir JavaScript kitabxanasıdır. Bu güclü və sərfəli alət, veb proqramçılarına müstəqil olaraq vəziyyətləri və animasiyaları əlavə etmək imkanı verir. Əgər siz də veb tətbiqlərinizdə gözəl 3D effektlər əldə etmək istəyirsinizsə, three.js sizin üçün ən yaxşı seçim ola bilər.

## Three.js Haqqında Əsas Məlumatlar

Three.js, WebGL texnologiyası üçün bir wrapper kimi fəaliyyət göstərir. WebGL, brauzerdəki 3D grafika tərtib etmək üçün optimallaşdırılmış bir API-dir və Three.js bu funksiyaları daha asan istifadə üçün əlavə edir.

Kitabxananın əsas xüsusiyyətləri şunlardır:

- 3D obyektlərin tərtibatı və idarə olunması
- Kamera və işıq idarəetməsi
- Material və texture təyin etmək
- Animasiyaların tərtibatı və idarə olunması
- VR (Virtual Reality) tətbiqləri üçün dəstək

## Three.js Quraşdırılması

Three.js kitabxanasını istifadə etmək üçün, brauzerdəki səhifənizə aşağıdakı kodu əlavə edin:

```html
<script type="module">
  import * as THREE from "https://unpkg.com/three@110.0.0/build/three.module.js";
</script>
```
