# GIT-Bash-GIT-Temel-Komutlar
GIT Bash GIT Temel Komutlar

## Başlıca bilinmesi gereken komutlar
untracked (izlenmeyen):GIT tarafından henüz takip edilmeyen,yani yebi oluşturulmuş ifade eder.
unstaged(hazırlanmamış):güncellenmiş ancak commit'lenmek için hazırlanmamış dosyaları ifade eder.
staged(hazırlanmış):commit'lenmeye hazır olan dosyaları ifade eder.
deleted(silinmiş):Projeden silinmiş ancak GIT üzerinden kaldırılmamış dosyaları ifade eder.

git add: yebi eklenen veya üzerinde değişiklik yapılan dosyaları staged ortamına göndermek için kullanılır.

git add . :tüm dosya uzantılarını ifade eder.
git add -A : A (all) anlamındadır.

git rm :staged ortamına eklenmiş bir dosyanın takibinin bırakılması yani untracked hale getirilmesi sağlayan komuttur.

git rm --cached
git status : Projenin o anki durumu hakkında bilgi verir.Yapılan değişikler eklenenve silinen dosyalar gibi bilgiler listelenir.

git commit -m :(m message anlamına gelmektedir.)Staged ortamına alınan dosyaları Local Repository'e gönderilmesidir.En iyi uygulama yöntemi her kayıt sırasında yapıaln değişiklikleri açıklayıcı bir mesaj eklemektir.

git log:Projede commit geçmişini görmenizi sağlar.
git branch:TÜm yerel ve uzak brachları listelemek için 
git branch -a: Bir branch'ı silmek için
git checkout: Brach'lar arası veya commit'ler arası geçiş yapmak istediğimizde kullanılır.
git merge:başka bir brach'ta olan değişiklikleri, bulunduğumuz brach ile birleştirmek için kullanılır.
git clone: mevcut bir remote repository'de bulunan dosyaların bilgisayarımızda bir kopyasının oluşturulmasını sağlar.

git push: projemizde aldığımız commitleri remote repository'e göndermk için kullanılır.

origin kök dizinini belirtir ve sabit bir isimdir. 
Master ise sizin çalıştığınız brach(dal)'ı belirtir.


gif diff :repository üzerinden yapılan değişikliklerden sonra dosyalar arasında oluşan farklılıkları gösterir.

git diff HEAD: ikicommit arasındaki  farklılığı görmek için kullanılır.

ekleme yapılmıştır.
