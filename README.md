## Ümumi məlumat
Bu lahiyə .env faylı daxilində verilmiş istifadəçi məlumatlarına görə AzTU-nun KOİCA səhifəsindən "Davamiyyət" məlumatlarının cədvəl formatında çıxarılmasını təmin edir

## .env faylının sturukturu
.env faylının daxilindəki məlumatlar aşağıdakı kimi olmaldır:
```bash
   NAME="İstifadəçi-adı"
   PASSWORD="Şifrə"
   ```
Məsələn:
```bash
   NAME=Nuran
   PASSWORD=Nuran123
   ```

## Quraşdırma təlimatları
1. **GitHub-dan layihəni klonlayın:**
   ```bash
   git clone https://github.com/Nuranss/LAB3.git   
   ```

2. **Virtual mühitin yaradılması:**
   Layihənin qovluğunda virtual mühit yaratmaq üçün:
   ```bash
   python -m venv venv
   ```

3. **Virtual mühitin aktivləşdirilməsi:**
   - Windows-da:
     ```bash
       venv\Scripts\activate
     ```
   - macOS/Linux-da:
     ```bash
     source venv/bin/activate
     ```

4. **Tələb olunan kitabxanaların quraşdırılması:**
   Layihənin tələb etdiyi kitabxanaları quraşdırmaq üçün:
   ```bash
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```

5. **Proqramı işə salın:**
   Layihəni işə salmaq üçün aşağıdakı əmri daxil edin:
   ```bash
   python main.py
   ```

## Nəticə
Nəticədə istifadəçinin davamiyyət məlumatlarından müvafiq tarixlərə uyğun olaraq cədvəl hazırlayır

## Əlaqə:
Əgər hər hansı bir sualınız varsa, mənimlə əlaqə saxlaya bilərsiniz: nuransgrov@gmail.com
