proses serialize
pickle - 1. joblib / 2. pickle
bisa simpen variabel apapun (model, dataframe, dll)
keunggulan bisa gabungin yang sifatnya numeric sama string
misal angka dan label
resikonya filenya lebih besar

npz: bisa langsung dari numpy, hanyabisa angka tidak bisa string

contoh menyimpan pake joblib

model akan dipanggil terus ketika ada koneksi minta prediksi

ketika hasil testing nya bagus baru dianggap patokan bagus