# Загварын талаар

Энэхүү загвар нь [Ghost](https://github.com/TryGhost/Ghost) -ийн Headline гэх загвар дээр суурилсан болно.

# Хөгжүүлэх

Та хөгжүүлэлтийн машин дээрээ [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/), [Gulp](https://gulpjs.com) -г global тохиргоогоор суулгасан байх хэрэгтэй.

```bash
# Загварын кодыг татаж авах
git clone https://github.com/nomungegee/ghost-cms-theme.git

cd ghost-cms-theme

# Шаардлагатай програмуудыг суулгах
yarn

# Кодыг багцлах & өөрчлөлтүүдийг хянах
yarn dev
```

Өөрчлөлтүүдээ хийж дууссан үедээ дараах командыг ашиглан Gulp -ийн `zip` task -аар загварын файлуудыг `dist/headline-nomungegee.zip` руу багцлана. Уг файлыг та өөрийнхөө ghost сайт руу хуулаад л загвараа ашиглах боломжтой

```bash
yarn zip
```

## Copyright & License

Copyright (c) 2013-2022 Ghost Foundation - Released under the [MIT license](LICENSE).
