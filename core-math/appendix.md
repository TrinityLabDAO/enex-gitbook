# Inside the ENEX

### Takaslar ve Likidite havuzları 

#### Temel kavramlar

DEX dijital varlık değişimi için tasarlanmıştır. Varlıklar bağımsız likidite havuzları içinde değiştirilir. Her çift için yalnızca bir havuz bulunabilir. Havuzdaki değişim işlemleri için ücret, oluşturma anında otomatik olarak ayarlanır. Her kullanıcı havuz oluşturabilir, mevcut havuzlara likidite ekleyebilir, önceden eklenen likiditeyi kaldırabilir ve varlıkları değiştirebilir. Her işlem, ilgili akıllı sözleşme çağrılarak gerçekleştirilir.

Likidite işlemi yürütme ekleme sırasında oran değişebileceğinden, bir varlığın tutarını düzeltir ve diğerinde sınırlar belirlersiniz. Yani bu örnekte aslında **20 $ENX ve 201.72 $ENQ** aktarabilirsiniz. ****

### Space Drops

#### Temel kavramlar

Havuzlar, $ENX keyfi varlıkla yatıran kullanıcıları ödüllendirmek için bir mekanizmadır. Havuz herhangi bir kullanıcı tarafından oluşturulabilir. Havuz oluşturulduktan sonra varlıkla doldurulabilir ve $ENX bahisler konulabilir. Havuzun varlığı olduğu ve $ENX stake edildiği\(yatırmak\) sürece, tüm paydaşlar hisseleriyle orantılı olarak varlıkla ödüllendirilir. Zaman başına dağıtılmış ödül havuz oluşturucu tarafından ayarlanır. Her paydaş, hissesiyle herhangi bir işlem yapabilir \(arttırma, azaltma veya alabilir\) veya istediğiniz zaman ödül alabilir.

Bir havuzu, suyun varlığı temsil ettiği, havuzun stake edlilen\(yatırılmış\) $ENX temsil ettiği, haznenin\(rezervuar\) dağıtılacak varlık miktarını temsil ettiği ve lavabo çapının blok başına ödülü temsil ettiği hazneden\(rezervuar\) dökülen su ile dolu gerçek bir havuz olarak düşünebilirsiniz. Hazne\(rezervuar\) boş olmadığı sürece su dökülecektir. Havuz alanı ne kadar çok olursa, su seviyesi o kadar yavaş yükselir.

Başlangıçta stake yoktur \(havuz alanı sıfırdır\), bu nedenle hazneden su dökülmez \(varlık harcanmaz\). İlk yatırım yapıldıktan sonra\(stake\), havuz alanı boyutuna eşit hale gelir. Örneğin hisse 10 $ENX.

Su dökülmeye başlar \(ödüller yatırıma\(stake\) eklenir\), su seviyesi yükselir ve haznedeki su hacmi azalır \(varlık harcamadır\). Blok başına ödül blok başına 1 belirteçse, water\_level\(su seviyesi\) 100 blok sonra 10 birimdir.

Ödül boyutu su hacmi ile temsil edilir ve stake  _water\_level\(su seviyesi\) olarak hesaplanabilir. Örneğimizde bir ödül 10_  10 = 100 jetondur.

Blokta 100 iki kazık \(B ve C\) 10 $ENX havuza eklenir. Şu andan itibaren yeni ödül üç bahis arasında da paylaşılmalı. Ancak yeni bahislerin A ödülü üzerinde etkisi olmamalıdır. Bu yüzden havuzumuzun alanını artırıyoruz, ancak mevcut su seviyesinde adımlar atıyoruz.

Böylece, 300 bloktan sonra yeni bahis üzerine 300 jeton dağıtılacak ve su 300 / 30 = 10 birim artırılacak ve 20 olacaktır.

Yani, bir ödül 10  _20 = 200, B ve C ödülü ise her biri 10_  10 olacaktır.

Eğer stake edilmiş $ENX \(örnek A\) kaldırılırsa, ödül A \(A alanı üzerindeki su sütunu ile temsil edilir\) paydaş dengesine geçer. Hisse bırakırken ödül almak, hisseyi kaldırmak ve tekrar eklemekle eşdeğerdir ve paydaş için şeffaf bir şekilde tek bir işlemde yapılabilir.



### 

### 



