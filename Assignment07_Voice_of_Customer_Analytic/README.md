# Voice of Customer Analytic

## 1. Import Dataset

"Wongnai Reviews - Small.csv"

## 2. Clustering using K-Means

![Clustering](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment07_Voice_of_Customer_Analytic/07_2_Clustering%20using%20K-Means.JPG)

## 3. Define words and remove as well as new words for tokenization

removed_words = ['u', 'b', 'n', 'nn', 'nn-', '\n', 'ร้าน','กิน','อร่อย','ทาน','รีวิว','ซอย','ผม','สวัสดี','กก','กา','ศ','นะคะ']

new_words = {"สตารบัก","กวงทะเลเผา","ชานมไข่มุก"} 

## 4. Result Discussion

clustering using K-Means result

![Result](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment07_Voice_of_Customer_Analytic/07_4_result.JPG)

### Group 0 (Traveler)

จะมีคำที่เกี่ยวข้องทั้งร้านอาหาร, ร้านกาแฟ และจะมีคำที่ทำให้ประเมิณได้ว่ากลุ่มนี้จะเป็น คอมเม้น จากคนที่เข้าร้านโดยความบังเอิญ หรือ มาเป็นครั้งแรก

### Group 1 (Zap Zap)

จะเป็นคำที่เกี่ยวข้องร้านอาหาร และเป็นอาหารอีสานที่มากินกับเพื่อนมีเมนู อย่างเช่นส้มตำ เป็นหลัก

### Group 2 (Cafe Hopping)

เป็นคอมเม้นของร้านกาแฟ-เบเกอรี่ ทางด้านที่ดี 

### Group 3 (Kaimook Lover)

จะเป็นกลุ่มคอมเม้นที่เกี่ยวข้องกับเครื่องดื่มโดยเฉพาะชานมไข่มุกที่เรารักส์

