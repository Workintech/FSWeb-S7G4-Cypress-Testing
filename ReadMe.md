# Sprint Gün Projesi Görevi: Cypress Testi

Gün Projesi görevi, öğrencilerin bağımsız olarak üzerinde çalıştıkları öğleden sonraki proje veya görevdir. Bu görev, eğitmenle daha önce tamamlanan projeyi geliştirir.

## Tek Sayfa Uygulamaları

## Cypress.io

## Hedefler

- uçtan uca testin ne olduğunu ve önemini açıklamak
- testler yazmak ve Elementler ile etkileşim kurmak için Cypress GUI'yi kullanmak
- kontrollü inputları test etmek için Cypress'i kullanmak
- tüm testleri herhangi bir kullanıcı arayüzü olmadan çalıştırmak

## Talimatlar

Bu challenge'da, son yaptığınız form uygulamanızın hatalarını ayıklamak için Cypress ile testler yazacaksınız.

## Talimatlar

### Görev 1: Projeyi Kurun

Bu proje bir önceki yaptığınız uygulamanın devamıdır.

- [ ] Önceki projenizin klasörüne girin
- [ ] Değişiklikler yapın ve aynı brancha yükleyin

Cypress kurulumu için `npm install cypress --save-dev` komutunu girin ve  `npx cypress open` yazın. Bu, "Cypress 10'a Hoş Geldiniz!" başlığı ve altında "Cypress 10'a Devam Et" yazan buton içeren bir diyalog açacaktır. Bu butona tıklayın, ardından bir sonraki ekranın en altına gidin ve arka arkaya üç geçiş butonuna tıklayın (birini tıkladıktan sonra sonraki bölüm genişleyecek ve bir sonraki geçiş seçimini tıklamanıza izin verecektir). Bir sonraki ekranda 'e2e' seçeneğini seçin ve bir sonraki ekranda 'Scaffold Example Specs' seçeneğini seçin, ardından istediğiniz bir tarayıcı seçin ve 'E2E Testini Başlat' düğmesine tıklayın.

Oradan, VSCode'da yeni oluşturduğunuz cypress klasöründe, e2e klasörüne gidin ve `form.cy.js` adlı yeni bir dosya oluşturun. Artık testlerinizi yazmaya hazırsınız! (Dosya isminde ".cy" olduğundan emin olun, aksi takdirde Cypress testlerinizi bulamaz!)

### Görev 2a: Testleri yazmak ve çalıştırmak (MVP)

Bu görevi tamamlamak için aşağıdaki testleri yazmanız ve çalıştırmanız gerekecek. Testlerin başarısız olma nedeni mantıklıysa, testi geçmek önemli değildir.

Şunları yapacak testleri ayarlayın:

- [ ] `isim` inputunu alın ve bir isim yazın.
- [ ] Girilen metnin sağladığınız adı içerip içermediğini kontrol etmek için bir assertion kullanın. (İpucu: .should assertion)
- [ ] `email` inputunu alın ve bir email adresi girin
- [ ] `şifre` inputunu alın ve bir şifre girin
- [ ] Kullanıcının kullanım koşulları kutusunu işaretlediğini kontrol edecek bir test oluşturun
- [ ] Kullanıcının form verilerini gönderip gönderemeyeceğini test edin 
- [ ] Bir input boş bırakılırsa form doğrulamasını test edin

### Görev 3: Esnek Görevler

Vaktiniz varsa, son birkaç gündür bu kod üzerinde çalışırken karşılaştığınız yaygın sorunlara dayalı olarak farklı testler yazın ve çalıştırın.

## SSS

**Ya tüm testlerim geçemezse?**

*Önceki derslerdeki kodunuzun kalitesine bağlı olarak testleriniz geçemeyebilir. Bu oldukça iyi! Bu projenin amacı, hataları işaret eden testler tasarlamaktır. Bu nedenle, test kodunuzla ilgili değil, web sayfası kodunuzla ilgili sorunlar nedeniyle testlerin başarısız olduğundan emin olmanız gerekir.*

****

## Kaynaklar

📚 [Cypress Dökümanı](https://www.cypress.io/how-it-works/)

🤔 [Blog: Cypress (Javascript) ile nasıl UI test yazarız ?](https://medium.com/testkaynak/ui-test-nas%C4%B1l-yaz%C4%B1l%C4%B1r-cypress-javascript-ile-nas%C4%B1l-ui-test-yazar%C4%B1z-efe8e1699d5e#:~:text=1%2D%20Google%20url'ine%20ba%C4%9Flan%C4%B1yor,butonunun%20%C3%BCzerine%20gidip%20butona%20t%C4%B1kl%C4%B1yor.)

