Here's the step-by-step guide for Python installation on Debian in both English and Turkish:

**ENGLISH:**

1. **System Update:**
```bash
sudo apt update
sudo apt upgrade
```

2. **Installing Python 3** (usually pre-installed):
```bash
sudo apt install python3
```

3. **Installing Pip (Python Package Manager):**
```bash
sudo apt install python3-pip
```

4. **Python Development Tools:**
```bash
sudo apt install build-essential libssl-dev libffi-dev python3-dev
```

5. **Python Virtual Environment Tools:**
```bash
sudo apt install python3-venv
```

6. **Version Check:**
```bash
python3 --version
pip3 --version
```

7. **Basic Python Packages (Optional):**
```bash
pip3 install numpy
pip3 install pandas
pip3 install jupyter
```

8. **Python IDEs (Optional):**
```bash
# Visual Studio Code
sudo apt install code

# PyCharm
sudo snap install pycharm-community --classic
```

9. **Installing Virtualenv (Optional):**
```bash
pip3 install virtualenv

# Creating new virtual environment
python3 -m venv myenv

# Activating virtual environment
source myenv/bin/activate
```

10. **Basic System Tools:**
```bash
sudo apt install git wget curl
```

**Important Notes:**
- Prefer Python 3 over Python 2
- Using virtual environments is a good practice
- Install packages per project instead of system-wide
- Use requirements.txt to manage dependencies

**Using Requirements.txt:**
```bash
# Save current packages to requirements.txt
pip3 freeze > requirements.txt

# Install packages from requirements.txt
pip3 install -r requirements.txt
```

**TÜRKÇE:**

1. **Sistem Güncelleme:**
```bash
sudo apt update
sudo apt upgrade
```

2. **Python 3 Kurulumu** (genellikle önyüklü gelir):
```bash
sudo apt install python3
```

3. **Pip (Python Paket Yöneticisi) Kurulumu:**
```bash
sudo apt install python3-pip
```

4. **Python Geliştirme Araçları:**
```bash
sudo apt install build-essential libssl-dev libffi-dev python3-dev
```

5. **Python Sanal Ortam Araçları:**
```bash
sudo apt install python3-venv
```

6. **Versiyon Kontrolü:**
```bash
python3 --version
pip3 --version
```

7. **Temel Python Paketleri (İsteğe Bağlı):**
```bash
pip3 install numpy
pip3 install pandas
pip3 install jupyter
```

8. **Python IDE'leri (İsteğe Bağlı):**
```bash
# Visual Studio Code
sudo apt install code

# PyCharm
sudo snap install pycharm-community --classic
```

9. **Virtualenv Kurulumu (İsteğe Bağlı):**
```bash
pip3 install virtualenv

# Yeni sanal ortam oluşturma
python3 -m venv myenv

# Sanal ortamı aktif etme
source myenv/bin/activate
```

10. **Temel Sistem Araçları:**
```bash
sudo apt install git wget curl
```

**Önemli Notlar:**
- Python 2 yerine Python 3 kullanmayı tercih edin
- Projelerde sanal ortam kullanmak iyi bir pratiktir
- Sistem geneli yerine proje bazlı paket kurulumu yapın
- Requirements.txt kullanarak bağımlılıkları yönetin

**Requirements.txt Kullanımı:**
```bash
# Mevcut paketleri requirements.txt'ye kaydetme
pip3 freeze > requirements.txt

# Requirements.txt'den paket kurulumu
pip3 install -r requirements.txt
```
