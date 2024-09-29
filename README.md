# PowerShell ile DNS Over HTTPS (DoH) Sorgulama

Bu proje, PowerShell kullanarak Google DNS sunucusu üzerinden DNS over HTTPS (DoH) protokolü ile DNS kayıtlarını sorgulamanızı sağlar. Kullanıcı, bir alan adı (domain) ve DNS kayıt türü (A, AAAA, MX, CNAME, TXT, SOA, NS, PTR, DNSKEY, SRV vb.) girerek ilgili DNS kayıtlarına ulaşabilir. "ALL" parametresi ile tüm DNS kayıt türlerini tek bir komutla sorgulayabilirsiniz.

## Özellikler

- Google DNS over HTTPS desteği.
- A, AAAA, MX, CNAME, TXT, SOA, NS, PTR, DNSKEY ve SRV kayıt türlerini sorgulama.
- Tüm DNS kayıt türlerini ("ALL" parametresi ile) tek bir komutla sorgulama.
- JSON formatında dönen yanıtları işleyerek anlaşılır bir şekilde ekrana yazdırma.
- Hata yakalama ve sorgu URL'sini kontrol etme imkanı.

## Gereksinimler

- PowerShell 5.1 veya daha güncel bir sürüm.
- İnternet bağlantısı (Google DNS sunucusuna erişim için).

## Kurulum

Bu projeyi yerel makinenize klonlamak için aşağıdaki komutu kullanabilirsiniz:

```bash
https://github.com/mutkus/Powershell-SOA-Sorgusu.git
