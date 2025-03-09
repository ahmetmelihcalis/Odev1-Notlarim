#Buraya Git/Github notlarımı tutacağım.

📌 Git Nedir?
Git, dağıtık bir versiyon kontrol sistemidir. Kodları takip etmeye, sürümleri yönetmeye ve ekip içinde iş birliği yapmaya yarar.

📌 GitHub Nedir?
GitHub, Git ile yönetilen projeleri barındıran bir platformdur. Projelerini çevrimiçi paylaşmanı ve diğer geliştiricilerle iş birliği yapmayı sağlar.

📌 Temel Git Komutları

📍 Başlangıç Komutları

git init            # Yeni bir Git deposu oluşturur.
git clone <repo>    # Var olan bir repo’yu indirir.
git status          # Çalışma alanının durumunu gösterir.

📍 Değişiklikleri Kaydetme

git add <dosya>      # Belirtilen dosyayı ekler.
git add .            # Tüm değişiklikleri ekler.
git commit -m "Açıklama"  # Değişiklikleri kaydeder.

📍 Değişiklikleri Geri Alma

git checkout -- dosya.txt  #Bir dosyayı son commit’ten önceki hâline döndürmek
git reset --hard     #Tüm değişiklikleri iptal etmek (Staging'de ve Çalışma Alanında)
git reset dosya.txt  #Staging’den dosyayı çıkarmak ama değişiklikleri korumak
git revert           #GitHub’dan commit’i geri almak (Eski commit’e dönmek ama geçmişi silmemek)

📍 GitHub’a Gönderme & Güncelleme

git remote add origin <repo_linki>  # Uzak repo ekler.
git push -u origin main  # Değişiklikleri GitHub’a gönderir.
git pull origin main  # Güncellemeleri çeker.
