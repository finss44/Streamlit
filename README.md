# Dashboard E-commerce Public Dataset Analysis

## Pipreqs pada Proyek Google Colab
!pip install pipreqs

from google.colab import drive
drive.mount('/content/drive')

!pipreqs "/content/drive/MyDrive/Colab Notebooks/Demo" --scan-notebooks

## Run Streamlit App
dashboard/dashboard.py
streamlit run dashboard.py
