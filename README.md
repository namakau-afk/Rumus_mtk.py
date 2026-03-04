print("*" * 55)
print("   20 RUMUS MATEMATIKA DAN PENJELASANNYA")
print("   (Program ini gw buat untuk lu yang males MTK)")
print("*" * 55)

print("\n🔷 BANGUN DATAR:")
print("1.  Keliling Persegi Panjang")
print("2.  Luas Persegi Panjang")
print("3.  Keliling Persegi")
print("4.  Luas Persegi")
print("5.  Keliling Segitiga")
print("6.  Luas Segitiga")
print("7.  Keliling Jajar Genjang")
print("8.  Luas Jajar Genjang")
print("9.  Keliling Trapesium")
print("10. Luas Trapesium")

print("\n🔷 BANGUN RUANG:")
print("11. Volume Kubus")
print("12. Volume Balok")

print("\n🔷 ARITMATIKA & SATUAN:")
print("13. Kecepatan Rata-rata")
print("14. Debit")
print("15. Skala pada Peta")
print("16. Konversi Suhu (C ke F)")
print("17. Konversi Suhu (C ke R)")
print("18. Konversi Suhu (C ke K)")

print("\n🔷 STATISTIKA SEDERHANA:")
print("19. Rata-rata (Mean) 3 Angka")
print("20. Perbandingan Senilai")

print("*" * 55)

choice = input("\nMasukkan pilihan [1-20]: ")

print()  
def input_angka(pesan):
    while True:
        try:
            nilai = input(pesan)
            if nilai.strip() == "":
                print("❌ Input tidak boleh kosong!")
                continue
            return float(nilai)
        except ValueError:
            print("❌ ERROR: Masukkan ANGKA saja, jangan huruf/simbol!")

if choice == '1':
    print("=" * 50)
    print("📐 RUMUS KELILING PERSEGI PANJANG")
    print("=" * 50)
    print("Rumus: K = 2 × (p + l)")
    print("Keterangan: p = panjang, l = lebar")
    print("-" * 50)
    
    panjang = input_angka("Masukkan panjang (cm): ")
    lebar = input_angka("Masukkan lebar (cm): ")
    
    keliling = 2 * (panjang + lebar)
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   K = 2 × (p + l)")
    print(f"   K = 2 × ({panjang} + {lebar})")
    print(f"   K = 2 × {panjang + lebar}")
    print(f"   K = {keliling}")
    print("-" * 50)
    print(f"✅ JAWABAN: Keliling = {keliling} cm")

elif choice == '2':
    print("=" * 50)
    print("📐 RUMUS LUAS PERSEGI PANJANG")
    print("=" * 50)
    print("Rumus: L = p × l")
    print("Keterangan: p = panjang, l = lebar")
    print("-" * 50)
    
    panjang = input_angka("Masukkan panjang (cm): ")
    lebar = input_angka("Masukkan lebar (cm): ")
    
    luas = panjang * lebar
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   L = p × l")
    print(f"   L = {panjang} × {lebar}")
    print(f"   L = {luas}")
    print("-" * 50)
    print(f"✅ JAWABAN: Luas = {luas} cm²")

elif choice == '3':
    print("=" * 50)
    print("📐 RUMUS KELILING PERSEGI")
    print("=" * 50)
    print("Rumus: K = 4 × s")
    print("Keterangan: s = sisi")
    print("-" * 50)
    
    sisi = input_angka("Masukkan panjang sisi (cm): ")
    
    keliling = 4 * sisi
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   K = 4 × s")
    print(f"   K = 4 × {sisi}")
    print(f"   K = {keliling}")
    print("-" * 50)
    print(f"✅ JAWABAN: Keliling = {keliling} cm")

elif choice == '4':
    print("=" * 50)
    print("📐 RUMUS LUAS PERSEGI")
    print("=" * 50)
    print("Rumus: L = s × s = s²")
    print("Keterangan: s = sisi")
    print("-" * 50)
    
    sisi = input_angka("Masukkan panjang sisi (cm): ")
    
    luas = sisi * sisi
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   L = s × s")
    print(f"   L = {sisi} × {sisi}")
    print(f"   L = {luas}")
    print("-" * 50)
    print(f"✅ JAWABAN: Luas = {luas} cm²")

elif choice == '5':
    print("=" * 50)
    print("📐 RUMUS KELILING SEGITIGA")
    print("=" * 50)
    print("Rumus: K = a + b + c")
    print("Keterangan: a, b, c = panjang ketiga sisi")
    print("-" * 50)
    
    a = input_angka("Masukkan sisi a (cm): ")
    b = input_angka("Masukkan sisi b (cm): ")
    c = input_angka("Masukkan sisi c (cm): ")
    
    keliling = a + b + c
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   K = a + b + c")
    print(f"   K = {a} + {b} + {c}")
    print(f"   K = {keliling}")
    print("-" * 50)
    print(f"✅ JAWABAN: Keliling = {keliling} cm")

elif choice == '6':
    print("=" * 50)
    print("📐 RUMUS LUAS SEGITIGA")
    print("=" * 50)
    print("Rumus: L = ½ × a × t")
    print("Keterangan: a = alas, t = tinggi")
    print("-" * 50)
    
    alas = input_angka("Masukkan alas (cm): ")
    tinggi = input_angka("Masukkan tinggi (cm): ")
    
    luas = 0.5 * alas * tinggi
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   L = ½ × a × t")
    print(f"   L = ½ × {alas} × {tinggi}")
    print(f"   L = ½ × {alas * tinggi}")
    print(f"   L = {luas}")
    print("-" * 50)
    print(f"✅ JAWABAN: Luas = {luas} cm²")

elif choice == '7':
    print("=" * 50)
    print("📐 RUMUS KELILING JAJAR GENJANG")
    print("=" * 50)
    print("Rumus: K = 2 × (a + b)")
    print("Keterangan: a = alas, b = sisi miring")
    print("-" * 50)
    
    a = input_angka("Masukkan alas (cm): ")
    b = input_angka("Masukkan sisi miring (cm): ")
    
    keliling = 2 * (a + b)
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   K = 2 × (a + b)")
    print(f"   K = 2 × ({a} + {b})")
    print(f"   K = 2 × {a + b}")
    print(f"   K = {keliling}")
    print("-" * 50)
    print(f"✅ JAWABAN: Keliling = {keliling} cm")

elif choice == '8':
    print("=" * 50)
    print("📐 RUMUS LUAS JAJAR GENJANG")
    print("=" * 50)
    print("Rumus: L = a × t")
    print("Keterangan: a = alas, t = tinggi")
    print("-" * 50)
    
    alas = input_angka("Masukkan alas (cm): ")
    tinggi = input_angka("Masukkan tinggi (cm): ")
    
    luas = alas * tinggi
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   L = a × t")
    print(f"   L = {alas} × {tinggi}")
    print(f"   L = {luas}")
    print("-" * 50)
    print(f"✅ JAWABAN: Luas = {luas} cm²")

elif choice == '9':
    print("=" * 50)
    print("📐 RUMUS KELILING TRAPESIUM")
    print("=" * 50)
    print("Rumus: K = a + b + c + d")
    print("Keterangan: a, b, c, d = keempat sisi")
    print("-" * 50)
    
    a = input_angka("Masukkan sisi a (cm): ")
    b = input_angka("Masukkan sisi b (cm): ")
    c = input_angka("Masukkan sisi c (cm): ")
    d = input_angka("Masukkan sisi d (cm): ")
    
    keliling = a + b + c + d
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   K = a + b + c + d")
    print(f"   K = {a} + {b} + {c} + {d}")
    print(f"   K = {keliling}")
    print("-" * 50)
    print(f"✅ JAWABAN: Keliling = {keliling} cm")

elif choice == '10':
    print("=" * 50)
    print("📐 RUMUS LUAS TRAPESIUM")
    print("=" * 50)
    print("Rumus: L = ½ × (a + b) × t")
    print("Keterangan: a, b = sisi sejajar, t = tinggi")
    print("-" * 50)
    
    a = input_angka("Masukkan sisi sejajar a (cm): ")
    b = input_angka("Masukkan sisi sejajar b (cm): ")
    t = input_angka("Masukkan tinggi (cm): ")
    
    luas = 0.5 * (a + b) * t
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   L = ½ × (a + b) × t")
    print(f"   L = ½ × ({a} + {b}) × {t}")
    print(f"   L = ½ × {a + b} × {t}")
    print(f"   L = ½ × {(a + b) * t}")
    print(f"   L = {luas}")
    print("-" * 50)
    print(f"✅ JAWABAN: Luas = {luas} cm²")

elif choice == '11':
    print("=" * 50)
    print("🎲 RUMUS VOLUME KUBUS")
    print("=" * 50)
    print("Rumus: V = s × s × s = s³")
    print("Keterangan: s = rusuk")
    print("-" * 50)
    
    sisi = input_angka("Masukkan panjang rusuk (cm): ")
    
    volume = sisi ** 3
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   V = s × s × s")
    print(f"   V = {sisi} × {sisi} × {sisi}")
    print(f"   V = {sisi * sisi} × {sisi}")
    print(f"   V = {volume}")
    print("-" * 50)
    print(f"✅ JAWABAN: Volume = {volume} cm³")

elif choice == '12':
    print("=" * 50)
    print("🧱 RUMUS VOLUME BALOK")
    print("=" * 50)
    print("Rumus: V = p × l × t")
    print("Keterangan: p = panjang, l = lebar, t = tinggi")
    print("-" * 50)
    
    p = input_angka("Masukkan panjang (cm): ")
    l = input_angka("Masukkan lebar (cm): ")
    t = input_angka("Masukkan tinggi (cm): ")
    
    volume = p * l * t
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   V = p × l × t")
    print(f"   V = {p} × {l} × {t}")
    print(f"   V = {p * l} × {t}")
    print(f"   V = {volume}")
    print("-" * 50)
    print(f"✅ JAWABAN: Volume = {volume} cm³")

elif choice == '13':
    print("=" * 50)
    print("🚗 RUMUS KECEPATAN RATA-RATA")
    print("=" * 50)
    print("Rumus: v = s ÷ t")
    print("Keterangan: v = kecepatan, s = jarak, t = waktu")
    print("-" * 50)
    
    jarak = input_angka("Masukkan jarak (km): ")
    waktu = input_angka("Masukkan waktu (jam): ")
    
    if waktu == 0:
        print("-" * 50)
        print("❌ ERROR: Waktu tidak boleh 0 (nol)!")
        print("   Pembagian dengan 0 tidak diperbolehkan.")
    else:
        kecepatan = jarak / waktu
        
        print("-" * 50)
        print("📝 CARA PENGERJAAN:")
        print(f"   v = s ÷ t")
        print(f"   v = {jarak} ÷ {waktu}")
        print(f"   v = {kecepatan}")
        print("-" * 50)
        print(f"✅ JAWABAN: Kecepatan = {kecepatan} km/jam")

elif choice == '14':
    print("=" * 50)
    print("💧 RUMUS DEBIT")
    print("=" * 50)
    print("Rumus: D = V ÷ t")
    print("Keterangan: D = debit, V = volume, t = waktu")
    print("-" * 50)
    
    volume = input_angka("Masukkan volume (liter): ")
    waktu = input_angka("Masukkan waktu (menit): ")
    
    if waktu == 0:
        print("-" * 50)
        print("❌ ERROR: Waktu tidak boleh 0 (nol)!")
    else:
        debit = volume / waktu
        
        print("-" * 50)
        print("📝 CARA PENGERJAAN:")
        print(f"   D = V ÷ t")
        print(f"   D = {volume} ÷ {waktu}")
        print(f"   D = {debit}")
        print("-" * 50)
        print(f"✅ JAWABAN: Debit = {debit} liter/menit")

elif choice == '15':
    print("=" * 50)
    print("🗺️  RUMUS SKALA PADA PETA")
    print("=" * 50)
    print("Rumus: Jarak Sebenarnya = Jarak Peta × Skala")
    print("Catatan: 1 km = 100.000 cm")
    print("-" * 50)
    
    jarak_peta = input_angka("Masukkan jarak pada peta (cm): ")
    skala = input_angka("Masukkan skala (contoh: 100000 untuk 1:100000): ")
    
    jarak_cm = jarak_peta * skala
    jarak_km = jarak_cm / 100000
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   Jarak Sebenarnya = {jarak_peta} × {skala}")
    print(f"                    = {jarak_cm} cm")
    print(f"                    = {jarak_cm} ÷ 100.000")
    print(f"                    = {jarak_km} km")
    print("-" * 50)
    print(f"✅ JAWABAN: Jarak sebenarnya = {jarak_km} km")

elif choice == '16':
    print("=" * 50)
    print("🌡️  KONVERSI SUHU: CELCIUS KE FAHRENHEIT")
    print("=" * 50)
    print("Rumus: F = (9/5 × C) + 32")
    print("-" * 50)
    
    c = input_angka("Masukkan suhu (°C): ")
    
    f = (9/5 * c) + 32
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   F = (9/5 × C) + 32")
    print(f"   F = (9/5 × {c}) + 32")
    print(f"   F = {9/5 * c} + 32")
    print(f"   F = {f}")
    print("-" * 50)
    print(f"✅ JAWABAN: {c}°C = {f}°F")

elif choice == '17':
    print("=" * 50)
    print("🌡️  KONVERSI SUHU: CELCIUS KE REAMUR")
    print("=" * 50)
    print("Rumus: R = 4/5 × C")
    print("-" * 50)
    
    c = input_angka("Masukkan suhu (°C): ")
    
    r = 4/5 * c
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   R = 4/5 × C")
    print(f"   R = 4/5 × {c}")
    print(f"   R = {r}")
    print("-" * 50)
    print(f"✅ JAWABAN: {c}°C = {r}°R")

elif choice == '18':
    print("=" * 50)
    print("🌡️  KONVERSI SUHU: CELCIUS KE KELVIN")
    print("=" * 50)
    print("Rumus: K = C + 273")
    print("-" * 50)
    
    c = input_angka("Masukkan suhu (°C): ")
    
    k = c + 273
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   K = C + 273")
    print(f"   K = {c} + 273")
    print(f"   K = {k}")
    print("-" * 50)
    print(f"✅ JAWABAN: {c}°C = {k} K")

elif choice == '19':
    print("=" * 50)
    print("📊 RUMUS RATA-RATA (MEAN)")
    print("=" * 50)
    print("Rumus: Rata-rata = (a + b + c) ÷ 3")
    print("-" * 50)
    
    a = input_angka("Masukkan angka pertama: ")
    b = input_angka("Masukkan angka kedua: ")
    c = input_angka("Masukkan angka ketiga: ")
    
    rata_rata = (a + b + c) / 3
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   Rata-rata = (a + b + c) ÷ 3")
    print(f"             = ({a} + {b} + {c}) ÷ 3")
    print(f"             = {a + b + c} ÷ 3")
    print(f"             = {rata_rata}")
    print("-" * 50)
    print(f"✅ JAWABAN: Rata-rata = {rata_rata}")

elif choice == '20':
    print("=" * 50)
    print("⚖️  RUMUS PERBANDINGAN SENILAI")
    print("=" * 50)
    print("Rumus: a/b = c/d  →  a × d = b × c")
    print("Contoh: Jika 2 buku harga Rp 10.000, berapa 5 buku?")
    print("-" * 50)
    
    print("Masukkan nilai yang diketahui:")
    a = input_angka("Nilai a (contoh: 2 buku): ")
    b = input_angka("Nilai b (contoh: Rp 10000): ")
    c = input_angka("Nilai c (contoh: 5 buku): ")
    
    x = (b * c) / a
    
    print("-" * 50)
    print("📝 CARA PENGERJAAN:")
    print(f"   {a}/{b} = {c}/x")
    print(f"   x = (b × c) ÷ a")
    print(f"   x = ({b} × {c}) ÷ {a}")
    print(f"   x = {b * c} ÷ {a}")
    print(f"   x = {x}")
    print("-" * 50)
    print(f"✅ JAWABAN: Nilai x = {x}")
    tc8
    
else:
    print("=" * 50)
    print("❌ ERROR: Pilihan tidak valid!")
    print("   Silakan pilih angka 1 sampai 20 saja.")
    print("=" * 50)

print()
print("=" * 55)
print("  **TERIMA KASIH TELAH MENGGUNAKAN PROGRAM INI** ")
print("   **DAN MAAF KALO ADA EROR DLL..**")
print("=" * 55)
