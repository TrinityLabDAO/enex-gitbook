---
description: Birden Fazla Blok Zinciri Bağlayan Yeni Bir AMM DEX
---

# ENEX.SPACE’e hoş geldiniz

## Genel Bakış

**ENEX,** [**Enecuum Network**](https://enecuum.com/) ****tarafından desteklenen ilk geliştirilmiş AMM DEX’tir.

**Ödünsüz güvenlik ve son derece düşük ücretlerle ENEX.SPACE’te ticaret yapın, kazanın, yayınlayın ve artırın.**

**ENEX.SPACE**, Enecuum blok zinciri üzerine inşa edilmiş **DeFi** platformudur. **ENEX.SPACE** işlevi $ ENX belirtecine göre çalışıyor.  $ ENX, ENEX.SPACE’deki genel likiditeyi temsil eder ve ticaret işlemlerinden kar elde etmek için kullanılabilir.  Kullanıcı açısından ENEX.SPACE likidite havuzları, hazine  ve Space Station oluşur.

## Likidite havuzları \(LP\)

Likidite havuzu, otomatik piyasa yapma \(AMM\) mekanizmasına sahip alım satım çiftidir.  Herhangi bir kullanıcı, herhangi iki varlığın yeni likidite havuzunu oluşturabilir veya mevcut herhangi bir LP’ye varlık ekleyebilir.  Likidite havuzu oluşturulur oluşturulmaz, ilgili likidite havuzu jetonu \(LP jetonu\) otomatik olarak oluşturulur.  Kullanıcı LP’ye likidite \(her iki varlık\) eklediğinde, karşılık gelen LP jetonunu alır.  Varlıklar, havuza bir varlık eklenerek ve karşılığında başka bir varlık alınarak takas edilebilir.  Alınan jeton miktarı, otomatik olarak AMM formülü ile hesaplanır.  Her işlemden sonra işlem hacminin  **%0,35’i** ücret olarak alınır.  % 0.30 likidite olarak havuza geri döner ve **%0.05 LP** tokenleri şeklinde ENEX hazinesine geçer.  Kullanıcı, herhangi bir anda ilgili LP jetonunu havuza iade ederek likidite havuzundan varlıkları çıkarabilir.

## Commander ENEX

Commander, hazineye tam erişimi olan bir varlıktır.  [Hazine](https://app.gitbook.com/@enex/s/enex-space/~/drafts/-MZWwNX-NdDxSnLJDSbo/v/tuerkce-1.0.0/treasury-fund/treasury-fund), LP tokenleri şeklinde havuz alım satımlarından alınan ücretlerle doldurulur \(bkz. [Likidite havuzları](https://app.gitbook.com/@enex/s/enex-space/~/drafts/-MZWwNX-NdDxSnLJDSbo/v/tuerkce-1.0.0/exchange-1/liquidity-pools) bölümü\).  Bu token’lardan bazıları likidite havuzları aracılığıyla ENX ile işlem görüyor.  Commander ENEX, zaman zaman ENX için bu LP jetonlarını satmaktadır.  ENX ile takas edilemeyen jetonlar adres yazmak için gönderilir.  Değiştirilen tüm ENX’ler dağıtım [Space Station](https://app.gitbook.com/@enex/s/enex-space/~/drafts/-MZWwNX-NdDxSnLJDSbo/v/tuerkce-1.0.0/space-station-pool) gönderilir.

![](.gitbook/assets/photo_2021-03-17-16.01.33.jpeg)

Yukarıdaki resimde üç likidite havuzu var.  Alım satım ücretleri hazinede LP şeklinde toplanır: 

* LPwc likidite jetonlu whiskey / cola, 
* LPgt likidite jetonlu gin / tonic,
* LPwc \* likidite belirteci ile LPwc / ENX.

Hazine zamanla LPwc, LPgt ve LPwc \* ile dolar. 

Takip eden LPwc / ENX çifti olduğu sürece, LPwc tokenleri ENX ile takas edilirken LPgt ve LPwc \* yakılır.

## Space Station

Space Station, belirli miktarda ENX’in ENX hissedarlarına dağıtım mekanizmasıdır.  Herhangi bir kullanıcı keyfi miktarda ENX yatırabilir.  Bazen, bazı ENX’ler dağıtım için Space Station taşınır \(commander ENEX bölümüne bakın\).  Bu ENX’ler tüm hissedarlar arasında orantılı olarak dağıtılır.

Örneğin, sırasıyla 10 ve 40 ENX hisselerine sahip iki A ve B hissedarı vardır.  Yani A payı% 20 ve B payı% 80’dir.  Bir süre boyunca İstasyona 60 ENX gönderilsin.  Ardından, A hissedarı 12 ENX \(60 ENX’in% 20’si\) ile ödüllendirilecek ve hissedar B 48 ENX \(60 ENX’in% 80’i\) ile ödüllendirilecektir.

## Anahtar noktaları

Geleneksel Uniswap benzeri AMM DEX’leri kullandığınızda, her zaman sözde “onaylama” işlemini yaparsınız.  Varsayılan olarak onaylarsanız, tüm olası miktardaki onaylanmış jetonun DEX akıllı sözleşmesi tarafından yönetilmesine izin vermiş olursunuz.  Bu, bir kripto para biriminin ana ilkelerinden birini ihlal ettiği için ciddi bir güvenlik sorunudur – varlıkların sahibi ve yalnızca sahibi varlıklar üzerinde tam kontrole sahip olmalıdır.  Ethereum tabanlı blok zincirlerinin aksine onay işlevi olmayan Enecuum Network mimarisi, havuzlarınızı güvenli hale getirir ve fonlar üzerinde tam kontrol sahibi olmanızı sağlar.

_**Daha fazla ayrıntı almak için şu adrese gidin:**_

{% page-ref page="core-math/appendix.md" %}

{% hint style="info" %}
**Bu Dokümanlar ENEX.SPACE V.1.0'ı açıklar**
{% endhint %}

