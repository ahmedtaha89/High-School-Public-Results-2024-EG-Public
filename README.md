# High School Results Scraper

This project is a web scraping tool designed to fetch and extract high school results data from the website `shbabbek.com`. The tool iterates over a range of seat numbers, fetches the HTML content for each seat, extracts the relevant data, and saves it to a CSV file.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.12
- `requests`
- `beautifulsoup4`
- `pandas`
- `lxml`

You can install the required Python packages using the following command:

```sh
pip install requests beautifulsoup4 pandas lxml


Usage
1.Clone the repository:
git clone https://github.com/yourusername/high-school-results-scraper.git
cd high-school-results-scraper

python scraper.py

2.Run the script:
he script will perform the following steps:

Initialize an empty list to store the responses.
Iterate over a range of seat numbers (from 552075 to 552331).
For each seat number, fetch the HTML content from the specified URL.
Append the successful responses to the list.
Extract the required data fields from the HTML content using BeautifulSoup.
Store the extracted data in a Pandas DataFrame.
Save the DataFrame to a CSV file at the specified path (D:\natega\r.csv).
Error Handling
The script handles HTTP request errors and skips any seat numbers that result in an error.
It also handles data extraction errors and continues processing the next response in the list.
Output
The extracted data is saved to a CSV file located at D:\natega\r.csv. The CSV file contains the following fields:

رقم الجلوس
الأسم
مجموع الدرجات
النسبة المئوية
المدرسة
الأدارة التعليمية
حالة الطالب
الشعبة
اللغة العربية
اللغة الأجنبية الأولى
اللغة الأجنبية الثانية
مجموع الرياضيات البحتة
التاريخ
الجغرافيا
الفلسفة والمنطق
علم النفس والاجتماع
الكيمياء
الأحياء
الجيولوجيا وعلوم البيئة
الرياضيات التطبيقية
الفيزياء