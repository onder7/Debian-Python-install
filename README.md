Debian üzerinde Python kurulumu için adım adım rehber:

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

Bu adımları tamamladıktan sonra Python geliştirme ortamınız hazır olacaktır.

