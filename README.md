# Capstone_Module3_JCDS
Hotel_Booking_Demands


### Attribute Information

| Attribute | Data Type, Length | Description |
| --- | --- | --- |
| country | str | Negara Asal Pelanggan |
| market_segment | str | Segmen Pasar |
| previous_cancellations | int64 | Berapa kali melakukan pembatalan pemesanan |
| booking_changes | int64 | Berapa kali melakukan prubahan pemesanan |
| daposit_type | str | Tipe deposit |
| days_in_waiting_list | int64 | hari menunggu dalam waiting list |
| customer_type | str | Tipe pemesanan |
| reserved_room_type | str | Tipe kamar yang disewa |
| required_car_parking_space | int64 | Jumlah perminataan lahan parkir |
| total_of_special_request | int64 | Permintaan Tambahan |
| is_canceled(target) | int64 | Pembatalan pemesanan,0 – Tidak batal, 1 – Batal |

Sebuah hotel ingin menyiapkan kamar untuk calon pelanggannya. Hotel ingin mengetahui pelanggan mana yang akan benar - benar menginap dan mana yang tidak.


Target :

0 : Tidak membatalkan booking

1 : Membatalkan Booking

**Problem Statement :**

Proses penyiapan fasilitas seperti kamar pada hotel memakan waktu dan sumber daya. Seandainya hotel menyiapkan semua fasilitas tetapi tidak digunakan maka akan sia - sia

Perusahaan mengasumsikan biaya sebagai berikut
        - Biaya yang dikeluarkan oleh Hotel untuk menyiapkan fasilitas kepada calon Customer (Kondisi False Negative): $50 / orang
        - Biaya yang dikeluarkan Hotel untuk biaya marketing: $30 / orang

        - Oleh karena biaya yang dikeluarkan akan lebih tinggi ketika pada saat kondisi False Negative maka hotel akan berusaha untuk menurunkan biaya yang telah dikeluarkan tersebut. Kemudian metrik yang dapat kita gunakan untuk melakukan pemilihan terhadap model Machine Learning yaitu Recall.
