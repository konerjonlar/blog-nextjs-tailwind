![tailwind-nextjs-banner](/public/static/images/twitter-card.png)

# Tailwind Nextjs Başlangıç Blogu

[![GitHub Repo stars](https://img.shields.io/github/stars/timlrx/tailwind-nextjs-starter-blog?style=social)](https://GitHub.com/timlrx/tailwind-nextjs-starter-blog/stargazers/)
[![GitHub forks](https://img.shields.io/github/forks/timlrx/tailwind-nextjs-starter-blog?style=social)](https://GitHub.com/timlrx/tailwind-nextjs-starter-blog/network/)
[![Twitter URL](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2Ftimlrxx)](https://twitter.com/timlrxx)
[![Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&link=https://github.com/sponsors/timlrx)](https://github.com/sponsors/timlrx)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/timlrx/tailwind-nextjs-starter-blog) => projeyi kolayca deploy edebilirsiniz.

[Benim sitem](https://orhancansu.vercel.app/)- projenin yayınlanmış hali.

[Klonlamış Olduğum Repo](https://github.com/timlrx/tailwind-nextjs-starter-blog)

Bu proje [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/) kullanılarak yapılmış bir blog sitesidir. Güzel özelliklere sahip olan Next.js markdown blog şablonu olarak tasarlanmıştır. Amacım projeyi geliştirirken projedeki kodları açıklayıcı bloglar ile birlikte kişisel blog hesabımı bu proje üzerinden sürdürmek. Projeyi kullanmak isteyip nasıl yapacağını bilmeyenler iletişime geçmekten çekinmesinler yardımcı olmaktan memnuniyet duyarım.

# Projeyi indirme

- [Use template](https://github.com/konerjonlar/blog-nextjs-tailwind/generate) butonuna tıklayarak kendi github reponuza klonlayın
- Daha sonra [versel](https://vercel.com/) sitesine giderek Github reponuzu seçip deploy işlemini başlatın.
- Proje dosyalarındaki yazıları kendinize göre uyarlayarak dosyaları güncelleyin.
- Siteniz otamatik güncellenecektir. Güle güle kullanın. :)


# Giscus ile yorumların oluşturulması

Giscus'ın kullanılabilmesi için 3 şart var:

1. Repo açık(public) olmalı
  - Settings
    - Danger Zone
      - Change repository visibility
        - [x] Make public

2. Marketplace [Giscus](https://github.com/apps/giscus) indirilmiş olmalı. 

3. Reponun ayarlarından discuss'ı açık olmalı
  - Settings
    - Options
      - Features
        - [x] Discussions

[Şartlar](https://giscus.app/#repository) sağlandıysa eğer .env.example diye bir klasörümüz var. (devamı gelecek)

- NEXT_PUBLIC_GISCUS_REPO= "https://github.com/konerjonlar/blog-nextjs-tailwind"
- [NEXT_PUBLIC_GISCUS_REPOSITORY_ID](https://stackoverflow.com/questions/13902593/how-does-one-find-out-ones-own-repo-id/13902640)= 441723495
  - name = "octolytics-dimension-repository_id" olan meta etiketindeki sağeri yazıyoruz.
- NEXT_PUBLIC_GISCUS_CATEGORY= "Blog Comments"
- NEXT_PUBLIC_GISCUS_CATEGORY_ID= 65315135

 
