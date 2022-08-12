# Marketing-Improvement-for-Cultivation-Technology-Startup-

## Context
eShrimp adalah sebuah startup yang bergerak dibidang teknologi budidaya udang vannamei. Startup ini didirikan bertujuan untuk membantu petambak dalam berbudidaya udang. eShrimp membuat webapp bernama eCultivation yang membantu petambak untuk:

- Memanage budidaya udang/ Farm Management System (FMS)
- Mengakses harga udang
- Mengakses informasi berita/informasi terkait budidaya udang vannamei (Shrimp Magazine)
- Mengakses informasi terkait penyakit udang

Untuk mencapai tujuan tersebut, eCultivation memiliki dua fitur utama, yaitu Farm Management System (FMS) dan Portal Informasi. 

## Problem
Saat ini eShrimp mengalami masalah dalam hal Human Resource. Di bagian tim product development, eShrimp tidak memiliki SDM yang cukup untuk memaintain seluruh product yang ada. Selain itu, tim sales and marketing juga kekurangan SDM untuk melakukan aktivitas sales, yaitu sales call dan live demo produk.

Dari permasalahan itu, sebagai Business Intelligence anda diminta untuk memberikan insight mengenai apa yang perlu dilakukan untuk mengoptimalkan jumlah siklus pro yang teraktivasi oleh masing-masing tambak. Anda dapat menggunakan data yang disediakan di

| Variables                        | Type | Keterangan                                                                                                                                                                                             |
| -------------------------------- | ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| farm_id                          | INT  | ID Tambak                                                                                                                                                                                              |
| registered_since                 | date | tanggal registrasi di eCultivation                                                                                                                                                                     |
| account_age                      | INT  | Umur akun tambak di eCultivation                                                                                                                                                                       |
| fms_access                       | INT  | Rerata penggunaan dalam satu minggu platform management budidaya dalam 4 bulan terakhir yang mencakup:<br><br>- View Data (Table and analytics)<br>- Create Data (Feed, Sampling, Kualitas Air, Panen) |
| shrimp_price_access              | INT  | Rerata visit fitur harga udang dalam satu minggu dalam 4 bulan terakhir                                                                                                                                |
| shrimp_news_access               | INT  | Rerata visit fitur shrimp magazine dalam satu minggu dalam 4 bulan terakhir                                                                                                                            |
| shrimp_diseaseInformation_access | INT  | Rerata visit fitur shrimp disease information dalam satu minggu dalam 4 bulan terakhir                                                                                                                 |
| registered_ponds                 | INT  | Jumlah kolam yang terdaftar di tambak tersebut                                                                                                                                                         |
| live_demo                        | Bool | Apakah user pernah diberikan live demo tentang produk atau tidak:<br>1: Pernah<br>0: Tidak Pernah                                                                                                      |
| followedup_call                  | Bool | Apakah user pernah menjadi target sales-call atau tidak:<br>1: Pernah<br>0: Tidak Pernah                                                                                                               |
| Finished_premium                 | INT  | Jumlah siklus premium yang pernah diselesaikan oleh suatu tambak                                                                                                                                       |
| Finished_basic                   | INT  | Jumlah siklus basic yang pernah diselesaikan oleh suatu tambak                                                                                                                                         |
| ongoing_premium                  | INT  | Jumlah siklus premium yang saat ini sedang berjalan di suatu tambak                                                                                                                                    |
| ongoing_basic                    | INT  | Jumlah siklus basic yang saat ini sedang berjalan di suatu tambak                                                                                                                                      |
