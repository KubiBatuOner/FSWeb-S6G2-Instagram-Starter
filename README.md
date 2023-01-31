# React Bileşenleri- Insta Klonu

## React Bileşenleri Oluşturma ve Props Aracılığıyla Veri Aktarma

## Giriş

- Bu proje için, React kullanarak basit bir Instagram klonu oluşturacaksınız.
- Bazı sahte veriler içeren `sahte-veri.js` adlı bir dosya var. Sahte verilerdeki her nesne, sahte bir Instagram gönderisini temsil eder.
- React uygulamanız, sahte gönderi verileri alacak ve her birini ayrı bir Instagram gönderisi olarak işleyecektir.

## Talimatlar

### Görev 1: Proje Kurulumu

Bu proje, create-react-app (CRA) kullanılarak oluşturuldu. Bu projenin çalışması için CRA'yı kurmanız gerekmeyecek. Projeyi uygun bağımlılıklarla kurmak için aşağıdaki adımları izleyin.

- [x] Projeyi forklayarak bir kopyasını oluşturun.
- [x] Terminalden klonlayın
- [x] Projenin ana dizinine gidin
- [x] `npm install --no-audit` komutuyla bağımlılıkları indirin
- [x] `npm start` ile çalıştırın
- [x] Push commits: git push origin `main`.

### Görev 2a: MUÜ

- [x] Bu uygulama, bu proje için gereken iki ana bölüme ayrılabilir: Arama Çubuğu ve Gönderiler.
- [x] Bu projeyi tamamlamak için, sayfanın üst kısmında oluşturulan Arama Çubuğunun tek bir örneğinin yanı sıra `sahte-veri.js` dizisindeki her nesne için ayrı bir gönderi oluşturan bir Gönderi bileşeni olacaktır.
- [x] Gönderileri takip etmek ve stateleri belirlemek için dün öğrendiklerinizi kullanın.
- [x] Gönderilerdeki "beğeni sayısını" artırmak için bir callback uygulayacak ve bunu birkaç seviyeden iç içe geçmiş bir bileşene aktaracaksınız.
- [x] Başlamadan önce kodu gözden geçirin. Bir sürü dosya var. Hepsine kod eklenmesi gerekli değil. App.js dosyasında başlayın ve oradaki talimatları okuyun.

---

Projenin son görüntüsü şu şekilde olmalıdır: [bu](/project-output.png)

### Görev 3: Ek Görevler

- [x] sahte-veri.js dosyasında daha fazla sahte veri oluşturun ve arama çubuğuna arama işlevi ekleyin. Bunu yapmanın bir yolu filtre yöntemidir.
- [ ] Bir input kullanarak bir gönderiye yorum ekleme özelliğini uygulayın.
- [ ] Tüm uygulamanın stilini tamamlayın ve instagram klonunuzun verilen tasarım özelliklerine çok benzemesini sağlayın.
