# YouTube Video Metadata Scraper

Proyek ini bertujuan untuk mengumpulkan metadata dari video YouTube milik seorang kreator tertentu dan menyimpannya ke dalam file Excel. Metadata yang dikumpulkan termasuk jumlah interaksi, tanggal publikasi, dan nama video.

## Persyaratan

- Python 3.6 atau lebih baru
- Pandas
- Requests
- BeautifulSoup
- Openpyxl

## Instalasi

1. Clone repositori ini:
    ```bash
    git clone https://github.com/username/repo.git
    cd repo
    ```

2. Instal dependensi yang diperlukan:
    ```bash
    pip install pandas requests beautifulsoup4 openpyxl
    ```

## Penggunaan

1. Buka dan jalankan Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Buka file `.ipynb` di Jupyter Notebook.

3. Sesuaikan variabel `creator` dengan nama pengguna YouTube yang ingin Anda ambil datanya:
    ```
    creator = '@#YOUTUBEUSERNAME'
    ```

4. Jalankan semua sel di notebook untuk mengumpulkan metadata video dan menyimpannya ke dalam file Excel.