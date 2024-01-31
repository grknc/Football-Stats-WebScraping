# Premier Lig İstatistikleri Web Scraping

## Proje Hakkında
Amaç: 2022-2023 Premier Lig sezonuna ait takım ve oyuncu istatistiklerinin çıkarılması.
Yöntem: Python ile FBref.com'dan web scraping.

## Kullanılan Kütüphaneler ve Araçlar
Bu projede, web scraping işlemi için aşağıdaki Python kütüphanelerinden yararlanılmıştır:

* BeautifulSoup: Web sayfalarından veri çekmek için kullanılan bir Python kütüphanesidir. HTML ve XML dosyalarını ayrıştırmak için kullanılır.
* Requests: Python için basit bir HTTP kütüphanesidir. Web sayfalarına HTTP istekleri göndermek için kullanılır.

## Kullanım
Notebook'ta yer alan kodları çalıştırmak için gerekli Python kütüphaneleri `requirements.txt` dosyasında belirtilmiştir. Projeyi çalıştırmadan önce bu kütüphanelerin kurulması gerekmektedir.

### Kurulum Adımları
1. Gerekli kütüphaneleri kurmak için aşağıdaki komutu terminalinizde çalıştırın:

pip install -r requirements.txt


## Web Scraping Hakkında
Web scraping, web sitelerinden veri çekme işlemidir. Bu yöntem, belirli bir web sayfasındaki bilgileri otomatik olarak toplamak ve düzenlemek için kullanılır. 
Projemizde, Python programlama dili kullanılarak FBref.com'dan Premier Lig takımlarının 2022-2023 sezonuna ait istatistiksel verileri çekiyoruz.


## Faydalı Kaynaklar
Web scraping konusunda daha fazla bilgi edinmek isteyenler için aşağıdaki kaynaklar faydalı olabilir:

BeautifulSoup Dokümantasyonu: BeautifulSoup, Python ile web scraping yapmak için en popüler kütüphanelerden biridir. Resmi dokümantasyon, kütüphanenin nasıl kullanılacağına dair temel bilgileri ve ileri düzey teknikleri içerir.
https://www.crummy.com/software/BeautifulSoup/bs4/doc/
https://tedboy.github.io/bs4_doc/

Requests Kütüphanesi Dokümantasyonu: Web scraping için veri çekme işlemlerinde sıklıkla kullanılan Requests kütüphanesinin resmi dokümantasyonu, HTTP istekleri yapma yöntemleri hakkında kapsamlı bilgi sunar.
https://requests.readthedocs.io/en/latest/


Scrapy Kütüphanesi: Daha büyük ve karmaşık web scraping projeleri için Scrapy, güçlü bir çerçeve sunar. Resmi dokümantasyon, Scrapy ile nasıl etkili bir şekilde çalışılacağını anlatır.
https://scrapy.org/

"Web Scraping with Python" Kitabı - Ryan Mitchell: Python kullanarak web scraping konusunda kapsamlı bir rehber arayanlar için bu kitap, temelden ileri düzeye kadar konuları ele alır.
https://edu.anarcho-copy.org/Programming%20Languages/Python/Web%20Scraping%20with%20Python,%202nd%20Edition.pdf


"Automate the Boring Stuff with Python" Kitabı - Al Sweigart: Bu kitap, Python programlamayı öğrenirken pratik beceriler kazanmayı amaçlar ve web scraping bölümü, bu konuya yeni başlayanlar için mükemmeldir.
https://github.com/thisisreallife/automate-the-boring-stuff-with-python/blob/master/Al%20Sweigart%20-%20Automate%20the%20Boring%20Stuff%20with%20Python_%20Practical%20Programming%20for%20Total%20Beginners-No%20Starch%20Press%20(2015).pdf

Bu kaynaklar, web scraping'in temellerini öğrenmek, Python ile web scraping yapma tekniklerini keşfetmek ve web scraping'in yasal yönleri hakkında bilgi sahibi olmak için mükemmel başlangıç noktalarıdır.


