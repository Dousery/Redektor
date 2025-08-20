<p align="center">
  <img src="https://github.com/user-attachments/assets/33f8bf94-5a46-4560-8a0a-b18add2bfbac" alt="Redektör Logo" width="850"/>
</p>

## Otomasyon Hakkında
**Redektör**, iş veya staj başvurusu sürecini sizin için kolaylaştıran bir **n8n otomasyonudur**. Gelen kutunuzdaki ilgili mailleri otomatik olarak tanır, sonucunu analiz eder ve size eğlenceli bildirimler gönderir. Bu sayede, sürekli mail kontrol etme derdinden kurtulur ve önemli gelişmeleri anında öğrenirsiniz.

---

## Nasıl Çalışır?
- Maillerinizi otomatik olarak kontrol eder ve iş veya staj ile ilgili olanları tespit eder.
- Başvurunuzun **olumlu** mu **olumsuz** mu olduğunu belirler.
- Sonucu **web/mobil üzerinden** anında bildirim olarak gönderir.
- Maillerinizi ilgili klasörlere (**Ret / Kabul**) otomatik olarak taşır.

---

## Kurulum
Redektör'ü kullanmaya başlamak için aşağıdaki adımları takip edin:

1. **Şablonu n8n'e aktarın.**
2. **Gmail ve Pushover Kimlik Bilgilerinizi Ekleyin:**  
   Her bir düğümün (`Gmail Trigger`, `Kabul tagine ekle`, `Ret tagine ekle`, `Notification Yolla`) içinde **Credentials** bölümüne kendi hesaplarınızı bağlayın.
3. **Pushover Kullanıcı Anahtarını Güncelleyin:**  
   `Notification Yolla` düğümünün **parameters** bölümündeki `userKey` değerini kendi Pushover kullanıcı anahtarınızla değiştirin.
4. **Gmail Etiket ID'lerini Girin:**  
   Gmail hesabınızda "Kabul" ve "Ret" etiketlerini oluşturun. Daha sonra bu etiketlerin ID'lerini bulup, `Kabul tagine ekle` ve `Ret tagine ekle` düğümlerindeki `labelIds` bölümüne yapıştırın.

---

## Gereksinimler
- n8n platformu
- Gmail hesabı
- Pushover hesabı ve kullanıcı anahtarı

---

## Katkıda Bulunma
Bu projeye katkıda bulunmak isterseniz, pull request gönderebilir veya issues üzerinden öneri ve hata bildirebilirsiniz.
