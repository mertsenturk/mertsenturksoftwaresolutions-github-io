# GitHub Pages – app-ads.txt ve geliştirici sitesi

Bu klasördeki dosyaları **yeni bir GitHub deposunun köküne** yükleyip GitHub Pages açacaksınız. AdMob doğrulaması için `app-ads.txt` adresiniz hazır olacak.

---

## Adım adım

### 1. GitHub’da yeni repo oluştur

1. [github.com](https://github.com) → giriş yap.
2. **New repository** (Yeni depo).
3. **Repository name:** İstediğiniz isim, örneğin:
   - `username.github.io` → Site adresiniz **https://username.github.io** olur (önerilen).
   - veya `imanvakti` → Site adresiniz **https://username.github.io/imanvakti** olur.
4. **Public** seçin, **Create repository** deyin.

### 2. Dosyaları repo’ya yükle

1. Oluşan boş repo sayfasında **“uploading an existing file”** veya **“Add file” → “Upload files”**.
2. Bu klasördeki **tüm dosyaları** sürükleyip bırakın:
   - `app-ads.txt`
   - `index.html`
   - (README.md isteğe bağlı)
3. **Commit changes** ile kaydedin.

### 3. GitHub Pages’i aç

1. Repo içinde **Settings** → sol menüden **Pages**.
2. **Source:** “Deploy from a branch”.
3. **Branch:** `main` (veya `master`), klasör **/ (root)**.
4. **Save**. Birkaç dakika sonra site yayında olur.

### 4. Adresleriniz

| Repo adı            | Ana sayfa                  | app-ads.txt adresi (AdMob için)      |
|---------------------|----------------------------|--------------------------------------|
| `username.github.io` | https://username.github.io | **https://username.github.io/app-ads.txt** |
| `imanvakti`         | https://username.github.io/imanvakti | **https://username.github.io/imanvakti/app-ads.txt** |

**Önemli:** AdMob ve mağaza sayfalarında “Geliştirici web sitesi” olarak **tam bu adresi** yazın (app-ads.txt olmadan, sadece site kökü):

- `username.github.io` kullandıysanız: **https://username.github.io**
- `imanvakti` kullandıysanız: **https://username.github.io/imanvakti**

### 5. AdMob’da

1. AdMob → Uygulama ayarları / Doğrulama.
2. Geliştirici web sitesi alanına yukarıdaki kök adresi yazın.
3. “Güncellemeleri kontrol edin” deyin. Birkaç dakika–birkaç saat sürebilir.

---

## Özet

- Bu klasördeki `app-ads.txt` ve `index.html` dosyalarını yeni repo’nun **köküne** yükleyin.
- Repo adı `username.github.io` ise: **https://username.github.io/app-ads.txt**
- Farklı repo adı ise: **https://username.github.io/repo-adi/app-ads.txt**
- Google Play ve App Store’da “Web sitesi” olarak aynı kök adresi (https://…) kullanın.
