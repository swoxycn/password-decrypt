# password-decrypt


`password-decrypt`, tarayıcıda saklanan şifreleri okumak ve şifrelere erişmek için Python ile yazılmış bir araçtır. Bu araç, kullanıcıların tarayıcılarından alınan veritabanı dosyalarındaki kayıtlı şifreleri çözerek erişim sağlar.

> **UYARI:** Bu araç sadece yetkilendirilmiş ve izinli erişim için kullanılmalıdır. İzin alınmadan başkalarının verilerine erişmek yasal değildir.

## Özellikler
- Tarayıcı veritabanından şifreleri çözme.
- Şifreleri ve ilgili kullanıcı adlarını görüntüleme.

## Gereksinimler
- Python 3
- `pycryptodome` ve `pysqlcipher3` kütüphaneleri

## Kurulum / Kullanım
Projeyi klonlayın:

   ```bash
   git clone https://github.com/swoxycc/password-decrypt.git
   cd password-decrypt
   python main.py
