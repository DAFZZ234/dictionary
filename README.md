# dictionary

profile_1 = {
    "name": "gem", #key: value
    "is male": False,
    "age": 14,
    "hobbies": ["gaming", "learning"]
}
print(profile_1["name"])
print(profile_1["name"]) #dictionary_name[key]
print("umur ", profile_1["name"], ":", profile_1["age"])

karyawan = {
    "nama": "gem",
    "pekerjaan": "penasihat"
}
print(karyawan)
karyawan["pekerjaan"] = "mentor"
print(karyawan)
karyawan["instansi"] = "technonatura jogja"
print(karyawan)

karyawan.pop("nama")
print(karyawan)

buku = {}
judul = "laskar pelangi"
penulis = "lil budi"
tahun = 2024
buku["judul"] = judul
buku["penulis"] = penulis
buku["tahun"] = tahun
print(buku)
