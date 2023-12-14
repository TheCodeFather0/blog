# Three.js İlə 3D Qrafika İnfrastrukturu

![Threejs](https://miro.medium.com/v2/resize:fit:1200/1*vU5ADFn2mH-N7y_ZvJBZDg.png)

Three.js ilk dəfə 2010-cu ilin aprelində GitHub-da Rikardo Kabello tərəfindən paylaşılmışdır.
Kod əvvəlcə Adobe Flash tərəfindən istifadə edilən ActionScript dilində işlənib hazırlanmış, sonra 2009-cu ildə JavaScript-ə köçürülmüşdür.

![Ricardo Cabello](https://media.rhizome.org/blog/8117/doob.png)

Three.js, veb səhifələrinə 3D qrafika əlavə etmək üçün istifadə olunan açıq mənbəli bir JavaScript kitabxanasıdır. Bu texnologiya, veb səhifələri daha interaktiv və gözəl etmək üçün istifadə edilir və yeni dizayn imkanları yaradır.

![](https://janakiev.com/assets/videos-and-gifs-with-threejs_files/webgl_01.gif)

## Three.js brauzerdə necə işləyir?

![](https://media.tenor.com/BdcwU6gstRoAAAAC/pooh-think.gif)

Bunun üçün WebGl-dən istifadə edilir. WebGl Veb brauzerdə interaktiv 2D və 3D qrafika göstərmək üçün JavaScript API -dir

![](https://avatars.githubusercontent.com/u/20603608?s=280&v=4)

## Three.js-in Əsas xüsusiyyətləri:

- 3D Modelerlərin İnteqrasiyası
  Three.js, Blender, Maya və 3ds Max kimi populyar 3D modelerlər ilə inteqrasiya edilə bilir. Bu, 3D modelerin veb səhifələrində rahatca göstərilməsinə imkan verir.

- Shaderlər və Materiallar
  Three.js rəng və material effektlərini yaratmağa imkan verən güclü bir shader sistemi ilə gəlir..

---

### Materiallar

Materiallar Three.js-də 3D obyektlərin rəngini, görüntüsünü və bu kimi başqa xüsusiyyətlərini tənzimləmək üçün istifadə olunan funksiyalardır.
Materiallar obyektin fiziki görünüşünü müəyyənləşdirmək üçün istifadə olunurlar.
Nümunə olaraq, bir materialın aşağıdakı xüsusiyyətləri göstərmək olar:

    - Color: Obyektin rəngini tənzimləmək üçün istifadə olunur
    - Bump Map: Obyektin qabarma xüsusiyyətini tənzimləyir
    - Opacity vƏ Transparency: Materialın şəffaflığını tənzimləyir

![](https://blog.logrocket.com/wp-content/uploads/2020/12/threejs-meshnormalmaterial.png)

### Shader-lər

    Shaderlar, 3D obyektlərin materiallarını tənzimləmək üçün istifadə edilən daha ətraflı və əlverişli alətlərdir. Shaderlar gözəl material effektləri, rənglər və interaktiv animasiya yaratmağa imkan verir. Shaderlar obyektlərin görünüşünü daha kompleks və ya müasir effektlər əldə etmək üçün kodla tənzimləməyə imkan verir.

      #### Shaderlər iki yerə bölünür

        - Vertex Shader: Bu shader 3D obyektlərin konfiqurasiyasını və mövqeyini tənzimləmək üçün istifadə edilir. Obyektlərin hansı bölgələrə düzələcəyi və necə hərəkət etdiyi kimi şeyləri tənzimləməyə kömək edir.
        - Fragment Shader: Bu shader obyektlərin görüntüsünü və rəngini tənzimləmək üçün istifadə edilir. Materiallar və görüntünün detallarını tənzimləməyə imkan verir.

![](https://img-c.udemycdn.com/course/750x422/5178164_f390.jpg)

- VR və AR Dəstəyi

  Three.js, Virtual Reality (VR) və Augmented Reality (AR) tətbiqlər üçün dəstək verir.Bu, istifadəçilərinizə ən son texnologiyaları təcrübə etmək imkanı yaradır.

---

- Open Source olması
  Three.js, open source layihədir və GitHub-da ictimai olaraq paylaşılır. Bu, texnologiyanı inkişaf etdirmək və məsləhətləşmək üçün böyük bir mənbədən istifadə etmək imkanı yaradır.

---
